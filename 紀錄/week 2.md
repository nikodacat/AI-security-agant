本周+下周目標:
將~10個paper的專題全拿來建置看看(完整從頭到尾建置測試)
將目前每個試過的分開來簡述:
1. pentestGPT
  很直接的幾個make就能執行，不過經過測試後，確定基本上要跑這些基於finetone和工具外加的模型需要:
    (1)一個支援api接口的AI供應商(openai, claude/anthropic api key)
    (2)local llm(自己找基礎的llm，但恐怕也要10b以上的模型配合完整的工具庫才有可能)
    (3)自己想辦法把沒有api的用手法接上(捏封包之類的)
  我目前是用第一種/第三種方法，用pentestGPT內建就能用的claude cli登入方法，簡單有效，但之後的paper有出現只能用api key，
  甚至openai api key的，就要再另外修改。
2.
