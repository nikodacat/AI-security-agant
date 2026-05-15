試著讓claude自行從零到有進行全面的掃描，結果好像很完整，從基礎的資料收集、資料庫對應到安全檢測都在三到四個prompt內到位<br>
<br>
<img width="2387" height="669" alt="image" src="https://github.com/user-attachments/assets/b9291bde-06cb-4eb3-8266-4df001e39da1" />
<img width="2469" height="885" alt="image" src="https://github.com/user-attachments/assets/f8b68ad2-9397-4c21-8c52-3531420b134f" />

...可以產生所有的建議行動
其實差不多可以收尾了
目前的這套流程，能抓到CVE漏洞，安全設定問題，組合/有條件的漏洞也都能檢測出來，然後再把旁邊的cve scanner接上線增加準度就可以了。

接上來後再跑一遍

實際拿vm來測試
用windows vm 再裝幾個有已知漏洞的作為基礎測試

接下來的計畫:






## 1.開始鑽研小細節或預定下一個目標
整體的檢測都能完成，剩下的就是優化使用體驗以及客製化，都是比較偏產品化的進步，除非想到有哪些需要額外完成的部分。
但因為純靠AI目前這套軟體已經完成了幾乎全部的工作，因此後面的過程也只是單純的給prompt讓他執行、改呈現方式而已，並不能做到任何創新的方法。

## 2.換專題
目前主意是音樂遊戲譜面的產生器，這個在過去有相關專題，但採用的是diffusion，針對的是4k(下落式音遊):
<img width="600"  alt="image" src="https://github.com/user-attachments/assets/a7c31d5c-8cd4-4981-83b4-61642363a788" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/6728f97c-a268-4119-aaaf-d809ee0b0ed3" />
因為本質上是創作，目前這個領域模型的問題是跟早期AI創作一樣的問題：明顯不像是人創作的。<br>
之前的模型只能基於拍點分析和訓練好的模型來製作，本質上並沒有考慮到音樂的段落性質。<br>
在這方面上，我會試圖透過當前llm已經可以解讀音樂意境的能力，來試圖改善這方面的問題。<br>

同時，我也不想僅限於基本的4k，因為實際上他不需要考慮合理性，譜面的品質不佳並不完全代表不能遊玩，只是單純的提升難度和玩家的反感。<br>
會以更加立體的機台類遊戲*maimai*作為第二階段的計畫。譜面本身是2d的情況下，會多出人體工學和遊玩可能性的問題，而對風格的考驗會更加困難。<br>
實際評測的方式會由想辦法由人工測試。<br>

### 針對MUG-diffusion的分析
MUG-diffusion生成譜面要求指定譜面難度，還有可以調的其他風格相關細節(但只能套用全譜面)。<br>
因此訓練資料集會決定他的上限。<br>
雖然能看到正常的配置，但實際整體表現卻有些撕裂。<br>
拿已知的配置對上了拍子，但沒有考慮實際的遊玩性，因此跟歌曲節拍合，但不一定跟歌本身合。<br>
當然，因為是用有一定品質的資料集，所以可玩性並不低，也有許多合理的配置。<br>
不過受限於難度作為prompt的因素，似乎對於簡化拍子配置或強行塞入不合的配置。<br>
依據難度生成譜面:<br>
3.6星
<img width="1960" height="671" alt="image" src="https://github.com/user-attachments/assets/b025b841-20d1-49ea-9a7b-802894d149f4" />
4星
<img width="2021" height="807" alt="image" src="https://github.com/user-attachments/assets/ec35652a-de99-47cb-83db-b2e98abeff17" />
5星
<img width="2052" height="809" alt="image" src="https://github.com/user-attachments/assets/e9afcb03-e452-4369-bddb-dbe8de5b4762" />
可以改善的部分是，改掉依賴對於拍子和難度的設計，來改善對於某些部分過於刁鑽小拍/副拍的狀況。<br>
以及將透過將歌曲分段落並分析的方式，來實現更有人類譜師風格的設計。<br>
各個段落採用RAG或finetone過的模型，來進行生成<br>
可能會是<br>
拍子分析    => 段落生成 => 段落組合 => 重新
歌曲分段+曲風分析  ^
