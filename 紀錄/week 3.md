## 狀況
  剩下的幾個paper似乎都是跟Autopenbench類似的專題，實際有興趣/有特點的可能會放在VTT-LLM跟企業安全審查的部分。<br>
  看起來並沒有一個paper特別針對類似資安管家的軟體(可能跟掃毒軟體有點重疊?)<br>
  penbench有提到claude opus本身就已經有不低的CTF準確度，所以實際上實操能力應該不用再強化，只要想辦法使得實作能映射到檢測上就好。<br>
  測試claude直接進行gap analysis的能力，結果還不錯，不過只掃了自己所在的vm以及測試了live service和runtime，
  可能要另外架構或是想辦法去scan已經安裝的程式來尋找CVE以及潛在漏洞。<br>
  
  claude gap analysis:[Security Gap Analysis Report.docx](https://github.com/user-attachments/files/26768114/Security.Gap.Analysis.Report.docx)

## 觀察/思考
  vtt-llm提供了一個可以將CVE映射到修復方法的模型**框架**<br>
  <img width="300"  alt="image" src="https://github.com/user-attachments/assets/2d473bd2-e53a-4376-a4af-51eec00add3b" /><br>
  將CVE資料庫和通用攻擊/防禦方式拿來finetune，將產出模型用於產生對於攻擊手段的防禦手法，但因為CVE是一個持續更新的資料庫，因此會逐漸過時，也有可能在第一時間錯過大漏洞，只要想辦法改成以外接CVE資料庫api的話，應該會比較好，但就要改變這個架構，或是在需要時調度相關的CVE。<br><br>
  似乎沒有實際做自動gap analysis的類似題目，而目前建置起來的專題都是以CTF類型為主的(也就是解題目找flag)，可以透過讓AI把flag放在資料敏感區來部分實現外部攻擊測試
，但居家電腦不太需要這個(畢竟不會是公開ip)。<br>
  
  這樣看下來，要做的就是:<br>
  1.  想辦法使pentestgpt或其他AI pentest可以將本家電腦做為測試目標。<br>
    如果要用pentestgpt的話，就要額外寫可以做report的部分，現在的常見通用agent跟pentestgpt好像都還無法直接完成整個測試=>實行=>分析=>回報的pipeline，可能是因為複合過多元素，但可以通過finetune處理。<br>
  2.  將其他gap analysis的工具接上agent然後透過prompt使他可以做一套完整的流程。<br>
    有現有的工具，只是需要再外接agent，以及各式微調。<br>
目前傾向兩個可能都要做，因為現在的AI過於強大，有可能兩個都會在短時間內就能得到近實用的結果。<br>
可以的話，是希望做成有CVE及時資料作為警告的類型，對於一台家用電腦，最大的威脅除了下載到病毒這種以社交工程為主的方法以外，比較難防的是像wannacry這種基於零日漏洞的攻擊，雖然CVE不是第一時間出現，但是可能會比補丁還快(主要原因是用戶更新或補丁的推出並非第一時間)<br>
簡短來說，就是希望將簡單的零架構放入居家電腦中，強化防禦。<br>
## 後記
這邊先想兩個備份的專案，來供比較與思考可行性(只是單純拿其他臨光一閃的主意做為參考)<br>
備源計畫:<br>
  1. 音樂遊戲譜面自動產生<br>
        現在已經有可以讀取音樂產生拍點的AI，但音樂遊戲的曲目通常複雜很多，可能會需要全面改寫其他paper。產生拍子後再將產生的檔案給第二個agent去處理格式以及生成。<br>
        實際有拿AI試過，目前基本上無法直接做到，大概是資料太少或太難找，也有可能是之前prompt太爛。<br>
        *其實就是遊戲關卡自動產生，然後再進一步特化。<br>
  3. 清大自動作業繳交系統<br>
       這個兩個禮拜瘋狂繳交作業後，覺得每個都要改不同的格式和報告名稱好麻煩，乾脆寫一個接口，讓AI去讀作業內容和細節，然後我把寫完的report丟去接口讓AI自動改名和上繳，
     讀網站寫一個crawler去避免給AI讀網站就好，大部分agent好像對讀網站都有限制。<br>
       登入網站=>選定作業=>讀網站(可能複合agent)=>改格式以符合需求(大概純agent)=>上傳<br>
    
<br><br><br>


<img width="800" height="" alt="image" src="https://github.com/user-attachments/assets/39ff9b42-dd6c-4267-8134-4b3064587f95" />
