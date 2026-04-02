本周+下周目標:<br>
將~10個paper的專題全拿來建置看看(完整從頭到尾建置測試)<br>
將目前每個試過的分開來簡述:<br>
1. pentestGPT<br>
  很直接的幾個make就能執行，不過經過測試後，確定基本上要跑這些基於finetone和工具外加的模型需要:<br>
    (1)一個支援api接口的AI供應商(openai, claude/anthropic api key)<br>
    (2)local llm(自己找基礎的llm，但恐怕也要10b以上的模型配合完整的工具庫才有可能)<br>
    (3)自己想辦法把沒有api的用手法接上(捏封包之類的)<br>
  我目前是用第一種/第三種方法，用pentestGPT內建就能用的claude cli登入方法，簡單有效，但之後的paper有出現只能用api key
  甚至openai api key的，就要再另外修改。<br>
2. AutoPenBench<br>
   這篇論文/github提供工具來進行benchmark，裡面有數個container可以使用做為測試，但大重點是將滲透分成數個步驟/指令來執行並限制模型單純回傳指令，並提供簡單的milestone可以使用。<br>
   本體的方法是分成instructor跟evaluator，由另一個agent來告訴正在進行挑戰滲透的agent他目前做到做對了什麼，實際上能操作的層面非常廣，主要是提供了一個可以部份給分的架構，這樣在需要訓練或finetone的情況下會好很多(可能可以反饋)<br>
   *也可以做instructor事後檢討<br>
   這項工具非常重要:完成率、執行效率、分層評分都在這裡了<br>
   事實上 也可以試著將pentestGPT接入這個架構中進行評價 目前處理手法之一是有一個http架構來對外做滲透vm的橋口以及evaluate<br>
   以下是單純claude運作 (6步與8步限制)<br>
   <img width="500"  alt="image" src="https://github.com/user-attachments/assets/7c0cd198-5060-4d18-bcd6-ee9e2ccc74f4" />
   <img width="500" alt="image" src="https://github.com/user-attachments/assets/de241655-7ffa-49de-b98a-1cce7829222e" />
   <img width="500" alt="image" src="https://github.com/user-attachments/assets/1d0dd4b6-e821-497b-a5d3-e6e2afb37b4f" /><br>
   再來是pentestGPT 9步<br>
   <img width="500" alt="image" src="https://github.com/user-attachments/assets/05c1756b-8af7-4882-b3d2-df91a237fbfe" />

   因為這一篇是偏工具library類的 連接相對複雜一些<br>
   但只要之後有docker檔+滲透答案/過程，就能做一組相當完整的benchmark<br>
3. Vulnbot
   是現在APT(長期持續威脅)的自動化版本，將 `偵查(recon)=>計畫(research)=>實現(deploy)=>入侵(intrusion)` 這四個步驟分開給不同的agent處理，提升效率與降低記憶負擔，例如scanner只將掃描並判斷後的結論返還給planner
   *不過有去掉實際有威脅的部分就是了，只做到成功入侵這部分，而不包含植入程式與資料竊取

**建構到目前的特別處理:因為每個的虛擬環境所要的package不同，但為了未來可能的整合方便，所以將所有的虛擬環境.venv做了一次整合(順便節省電腦空間)，改用symbolic(符號連結)的方式做處理  
