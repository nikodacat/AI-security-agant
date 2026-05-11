*這兩周因為期中以及維修docker，導致進度不穩定，後來想盡辦法修好一半
# 上次報告補充
-  名詞說明：<br>
  CTF = Capture the flag <br>
    **搶旗題目**，在資安題目最常見的類型，目標是取得放在指定系統(可能是伺服器、映像檔、程式、封包檔、加密訊息)的答案訊息(旗子)，通常有答案格式`ctf{answer_text}`來提示已經找到答案。
    pentestgpt就是針對此格式進行設計。<br>
    居家電腦可以直接加旗子化為ctf題目進行檢測，但要想辦法提供可測試的攻擊面，因為家用電腦的攻擊面不明顯(相比伺服器)。<br>
  gap analysis = **差距分析** <br>
    常用的資安防禦手法，透過將當前檢測範圍與一個企業基準做比對，產生一個比較列表作為安全建議，不一定是硬體，也有可能是針對企業計畫的，不過以硬體或家用主機而言，通常用軟體就可以一鍵完成最基本的功能。<br>
    上次的是比較視覺上比較完整的報告。<br>
  CVE = **Common Vulnerabilities and Exposures** <br>
    中文翻作"通用漏洞披露"，或簡稱漏洞列表，是一個常時維護的安全資料列表，列出各項軟體的最新漏洞敘述跟危險程度，有時比軟體更新更快公告，因此可能會作為提前預防或入侵的參考手段。<br>
    目前用於給模型的資料庫。<br>
  
# 本周進度
實作:<br>
  試著將CVE資料庫整合claude模型來對電腦進行檢查，並且給予安全建議:<br>
    [report](https://github.com/nikodacat/AI-security-agant/blob/main/%E7%B4%80%E9%8C%84/review_uncommented.md)<br>
    [commented](https://github.com/nikodacat/AI-security-agant/blob/main/紀錄/review_commented.md)<br>
  (實際上是KEV 已知利用漏洞資料庫)<br>
  實際上成果看起來可以，但在預期之內(畢竟原文就有提供，相當於只要翻譯即可)<br>
  有很多偽陽和過時的，但格式、接資料庫、給出反應，三樣都確實可行，接下來只要強化這三項，就能做到將CVE檢測用於居家電腦。<br>
  - 先將資料準確率作確保，減少到處亂抓CVE，以及進行版本確認。<br>
    [fixed](https://github.com/nikodacat/AI-security-agant/blob/main/review_reduced.md) <br>
  *以及儲存搜尋紀錄，因為他一次跑了快兩分鐘(api限制) <br>
  接下來是確保回報正確，還有可能將pentestgpt接上這個模型，以及最後的mitre對應，將各種標準攻擊防禦手法對應到該CVE並提出實作解決方法。<br>
  接下來是用測試的映象檔做準確度測試。
  這兩個預計在下三周之內完成(第四周就會開始整合總模型的第一側，最後整合為一個完整的報告和實際建議，以及可以執行修復的介面)
  額外的部分包含希望透過pentestgpt來進行漏洞的確認，以架起最小實例或尋找現有運作服務的方法模擬攻擊。

----------------------------------------------------------------

### **[EXPLOITED]** `CVE-2014-0160` — OpenSSL Information Disclosure Vulnerability

- Installed: `openssl` (version `3.0.13-0ubuntu3.9`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: OpenSSL / OpenSSL
- Date added to KEV: 2022-05-04
- CISA due date: 2022-05-25
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-125

這個 OpenSSL「心淌血」(Heartbleed) 漏洞讓遠端攻擊者可以從您的伺服器記憶體中竊取敏感資訊,包括密碼、加密金鑰、信用卡號碼及其他機密資料,且攻擊過程不會留下任何痕跡。您必須立即將 OpenSSL 更新至修補版本,並在更新後重新產生所有 SSL/TLS 憑證和變更相關密碼。雖然目前未被標記為勒索軟體常用手法,但此漏洞可被遠端利用且影響極廣,攻擊者可輕易取得系統最重要的機密資訊。若您的系統有對外提供網路服務,這個更新極為緊急,延遲修補可能導致大量敏感資料外洩。
