*這兩周因為期中以及維修docker，導致進度不穩定，後來想盡辦法修好一半
# 上次報告補充
-  名詞說明：<br>
  CTF = Capture the flag <br>
    **搶旗題目**，在資安題目最常見的類型，目標是取得放在指定系統(可能是伺服器、映像檔、程式、封包檔、加密訊息)的答案訊息(旗子)，通常有答案格式`ctf{answer_text}`來提示已經找到答案。
    pentestgpt就是針對此格式進行設計。<br>
    居家電腦可以直接加旗子化為ctf題目進行檢測，但要想辦法提供可測試的攻擊面，因為家用電腦的攻擊面不明顯(相比伺服器)。<br>
  gap analysis = **差距分析** <br>
    常用的資安防禦手法，透過將當前檢測範圍與一個企業基準做比對，產生一個比較列表作為安全建議，不一定是硬體，也有可能是針對企業計畫的，不過以硬體或家用主機，通常用軟體就可以一鍵完成最基本的功能。<br>
    上次的是比較視覺上比較完整的報告。
  CVE = **Common Vulnerabilities and Exposures** <br>
    中文翻作通用漏洞披露，或簡稱漏洞列表，是一個常時維護的安全資料列表，列出各項軟體的最新漏洞敘述跟危險程度，有時比軟體更新更快公告，因此可能會作為提前預防或入侵的參考手段。<br>
    目前用於給模型的資料庫。<br>
  
# 本周進度
實作:<br>
  試著將CVE資料庫整合claude模型來對電腦進行檢查，並且給予安全建議:<br>
    [report](https://github.com/nikodacat/AI-security-agant/blob/main/%E7%B4%80%E9%8C%84/review_uncommented.md)<br>
    [commented](https://github.com/nikodacat/AI-security-agant/blob/main/紀錄/review_commented.md)<br>
  (實際上是KEV "Known Exploited Vulnerability 資料庫)
  實際上成果看起來可以，但在預期之內(畢竟原文就有提供，相當於只要翻譯即可)
  有很多偽陽和過時的，但格式、接資料庫、給出反應，三樣都確實可行，接下來只要強化這三項，就能做到將CVE檢測用於居家電腦。
  - 先將資料準確率作確保，減少到處亂抓CVE，以及版本確認
