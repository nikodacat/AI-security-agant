### 初步計畫目標:
  將AI作為介面，來提供用戶在資安上的各項所需，像是居家電腦檢測，差距測試，基本的滲透測試，對於版本和各項軟體的cve確認等
### 實現方案:
  提供基礎的prompt和資料夾結構，類似kali的document，然後額外提供資安標準和報告範本讓AI可以幫助企業內部審查，漏洞分析(可能不包含修復)
### 基礎專案架構:
  將分成三個區域
  
  1. AI
     - 基礎的prompt和提供AI完整規範以及可用的專題架構
  2. 文獻
     - 工具document以及資安架構(例如零信任架構以及網路架構標準等) 說明書
  3. 工具
     - 可運行的工具本體，提供給AI用來實作弱掃
### 可用的參考文獻(暫定):
#### 自動化PT
PentestGPT: An LLM-empowered Automatic Penetration Testing Tool（2023, arXiv:2308.06782）<br>
AutoPenBench: Benchmarking Generative Agents for Penetration Testing（2024, arXiv:2410.03225）<br>
VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework（2025, arXiv:2501.13411）<br>
#### 評估
Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models（2024, arXiv:2408.08926）<br>
PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design（2025, arXiv:2512.14233）<br>
Security Challenges in AI Agent Deployment: Insights from a Large Scale Public Competition（2025, arXiv:2507.20526）<br>
#### CVE參照/報告
VTT-LLM: Advancing Vulnerability-to-Tactic-and-Technique Mapping…（MDPI Mathematics 2024 左右）<br>
#### 企業內部審核
Design and evaluation of an Autonomous Cyber Defence agent using DRL and an augmented LLM（Computer Networks, 2025）<br>
