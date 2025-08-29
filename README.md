<!--
   ███████╗ ███████╗███╗   ██╗██╗   ██╗██╗   ██╗██╗   ██╗
   ██╔════╝ ██╔════╝████╗  ██║██║   ██║╚██╗ ██╔╝╚██╗ ██╔╝
   █████╗   █████╗  ██╔██╗ ██║██║   ██║ ╚████╔╝  ╚████╔╝
   ██╔══╝   ██╔══╝  ██║╚██╗██║██║   ██║  ╚██╔╝    ╚██╔╝
   ██║      ███████╗██║ ╚████║╚██████╔╝   ██║       ██║
   ╚═╝      ╚══════╝╚═╝  ╚═══╝ ╚═════╝    ╚═╝       ╚═╝

   Wei Tsen-Yu | 魏岑宇
   Quant Trading Engineer · Options Automation · Multi-Broker APIs · Risk & OCO

   本 README 採中英雙語（繁中為主）。English sections are below each part or in collapsible <details>.
-->

<!-- ===== HERO ===== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0ea5e9,100:6366f1&text=Wei%20Tsen-Yu%20%7C%20%E9%AD%8F%E5%B2%91%E5%AE%87&fontAlign=50&fontSize=46&fontColor=ffffff&desc=Quant%20Trading%20Engineer%20%E2%80%A2%20Options%20Automation%20%E2%80%A2%20APIs%20%26%20Risk&descAlignY=70&descSize=18" alt="Hero Banner"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/weitsenyu/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-weitsenyu-0A66C2?logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:a0906583999@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-a0906583999%40gmail.com-ef4444?logo=gmail&logoColor=white">
  </a>
  <img alt="Visitors" src="https://komarev.com/ghpvc/?username=Weitsenyu&color=0ea5e9&label=Visitors">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-Quant%20%26%20Options-10b981">
  <img alt="Base" src="https://img.shields.io/badge/Base-Taiwan-22c55e?logo=googlemaps&logoColor=white">
  <img alt="Open to Work" src="https://img.shields.io/badge/Open%20to-Quant%20Trading%20Engineer-8b5cf6">
</p>

---

## 🛰️ 關於我 · About Me

**我是魏岑宇（Wei Tsen-Yu）** —— 專注 **選擇權自動化交易** 與 **量化策略工程**。我把研究想法落地為穩定可觀測的交易系統：

- ✅ **策略**：Short Strangle／Iron Condor／Straddle、IV Rank、動態避險  
- ✅ **API**：**Shioaji**（永豐金）、**CapitalAPI**（凱基）、**IBAPI**（盈透）  
- ✅ **風控**：**OCO** 一觸即發、MTM 監控、例外管理與 LINE/Discord/Telegram 告警  
- ✅ **可視化**：**PyQt6** 交易面板、IV Smile／OI Histogram／Greeks、PnL/回撤儀表  
- ✅ **工程化**：模組化、容器化（Docker）、CI/CD（GitHub Actions）、可觀測性與日誌追溯

> 目標：深耕 **Quant Trading Engineer / Options System Developer**，把「研究 × 工程 × 風控」做到產品級。

<details>
<summary>English (click to expand)</summary>

I'm <b>Wei Tsen-Yu</b>, focused on <b>options automation</b> and <b>quant strategy engineering</b>.<br/>
• <b>Strategies</b>: Short Strangle / Iron Condor / Straddle, IV Rank, dynamic hedging<br/>
• <b>APIs</b>: <b>Shioaji</b>, <b>CapitalAPI</b>, <b>IBAPI</b><br/>
• <b>Risk</b>: <b>OCO</b> (one-cancels-other), MTM monitoring, alerting via LINE/Discord/Telegram<br/>
• <b>Visualization</b>: <b>PyQt6</b> trading panel, IV Smile / OI Histogram / Greeks, PnL/MDD dashboards<br/>
• <b>Engineering</b>: modular architecture, Docker, CI/CD, observability & audit logs
</details>

---

## 🧭 目錄 · Table of Contents
- [關於我 · About Me](#-關於我--about-me)
- [亮點速覽 · Highlights](#-亮點速覽--highlights)
- [技能矩陣 · Skills Matrix](#-技能矩陣--skills-matrix)
- [代表專案 · Featured Projects](#-代表專案--featured-projects)
- [績效與風控觀念 · Performance & Risk](#-績效與風控觀念--performance--risk)
- [研究與工程 · Research & Engineering](#-研究與工程--research--engineering)
- [時間線 · Career Timeline](#-時間線--career-timeline)
- [統計與徽章 · Stats & Badges](#-統計與徽章--stats--badges)
- [聯絡我 · Contact](#-聯絡我--contact)
- [附錄 · Appendix（研究清單／FAQ）](#-附錄--appendix研究清單faq)

---

## 🚀 亮點速覽 · Highlights

- 🔁 <b>多券商 API 打通</b>：Shioaji／CapitalAPI／IBAPI <b>同時串接</b>，行情→風控→下單 <b>一條龍自動化</b>  
- 🧠 <b>Greeks/IV 驅動策略</b>：賣方結構（Short Strangle / Iron Condor）＋<b>動態避險與倉位分層</b>  
- 🧰 <b>完整工具鏈</b>：PyQt6 GUI、回測框架、監控告警、交易日誌、Docker＋CI/CD  
- 📈 <b>視覺化</b>：IV Smile、OI Histogram、Payoff、Greeks 全套圖表  
- 🧪 <b>資料采集</b>：Selenium／BeautifulSoup 擷取 TAIFEX／財報／Tick 餵回測  
- 🧩 <b>鬆耦合架構</b>：策略引擎、路由器、風控器、報表服務 <b>清晰分層</b>

<details>
<summary>English (click to expand)</summary>

• <b>Multi-broker integration</b> (Shioaji / CapitalAPI / IBAPI) across market→risk→execution<br/>
• <b>Greeks & IV-driven</b> short options with <b>dynamic hedging & layered risk</b><br/>
• <b>End-to-end toolchain</b>: PyQt6 GUI, backtesting, monitoring, logging, Docker, CI/CD<br/>
• <b>Full visualization</b>: IV Smile, OI Histogram, Payoff, Greeks<br/>
• <b>Data pipelines</b>: Selenium/BS4 for TAIFEX, earnings, ticks<br/>
• <b>Modularity</b>: strategy engine, router, risk, reporting
</details>

---

## 🛠️ 技能矩陣 · Skills Matrix

### Core Stack
**Python**（Pandas／NumPy／SciPy／statsmodels／matplotlib／plotly）  
**PyQt6**（跨平台交易 GUI 與監控面板）  
**APIs**：Shioaji／CapitalAPI／IBAPI  
**Data**：Selenium／BeautifulSoup／Excel 自動化  
**DB/Infra**：SQL（SQLite／PostgreSQL）、Docker、GitHub Actions  
**Web**：Node.js／Express、React、D3.js、Socket.IO（市況推播）

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/statsmodels-0A0A0A?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyQt6-41CD52?logo=qt&logoColor=white">
  <img src="https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white">
  <img src="https://img.shields.io/badge/BeautifulSoup-3B82F6?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=databricks&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Shioaji-0ea5e9?logo=datadog&logoColor=white">
  <img src="https://img.shields.io/badge/CapitalAPI-f97316">
  <img src="https://img.shields.io/badge/IBAPI-ef4444?logo=interactivebrokers&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/D3.js-F9A03C?logo=d3.js&logoColor=white">
  <img src="https://img.shields.io/badge/Socket.IO-010101?logo=socket.io&logoColor=white">
</p>

### 技能心智圖（Mermaid Mindmap）
```mermaid
mindmap
  root((Wei Tsen-Yu · Skills))
    Strategy
      Short Strangle
      Iron Condor
      Straddle
      IV Rank
      Dynamic Hedging
    APIs
      Shioaji
      CapitalAPI
      IBAPI
    Risk/Ops
      OCO
      MTM Monitor
      Alerts (LINE/Discord/Telegram)
      Audit Logs
    GUI/Vis
      PyQt6 Panel
      IV Smile
      OI Histogram
      Greeks/Payoff
    Backtest
      Costs/Slippage
      MDD/Sharpe/PF
      Scenario Stress
    Data
      Selenium
      BeautifulSoup
      Excel Automation
    Infra
      Docker
      GitHub Actions
      Modularization
```

---

## 🌟 代表專案 · Featured Projects

### 1) Option — 自動化選擇權交易平台
**Repo**：[`Weitsenyu/Option`](https://github.com/Weitsenyu/Option)

- **功能**：多券商 API（Shioaji／Capital／IB）行情→下單→回報一致化、<b>OCO</b>、動態避險、Greeks/IV 模組、交易日誌、風控儀表板  
- **GUI**：<b>PyQt6</b> 操作面板（Long／Short／Neutral／Micro Long／Micro Short）、條件單管理、異常告警  
- **視覺**：IV Smile、OI Histogram、Payoff、PnL 分佈  
- **工程**：模組化策略引擎、路由器、風控器、報表服務；Docker & CI/CD

<details>
<summary>架構圖（Mermaid）</summary>

```mermaid
flowchart LR
  subgraph Data[Data Sources]
    Ticks[(Ticks)]
    TAIFEX[(TAIFEX/CSV)]
    Earnings[(Earnings)]
  end

  subgraph Strategy[Strategy Engine]
    IV[IV/Greeks]
    SStrangle[Short Strangle]
    ICondor[Iron Condor]
    Hedger[Dynamic Hedger]
  end

  subgraph Risk[Risk System]
    OCO[OCO Manager]
    MTM[MTM Monitor]
    Alerts[LINE/Discord/Telegram]
  end

  subgraph Router[Trading Router]
    SHIOAJI[Shioaji]
    CAPITAL[CapitalAPI]
    IB[IBAPI]
  end

  subgraph UIRep[UI & Reports]
    PyQt6[PyQt6 Panel]
    Viz[IV Smile / OI / Payoff]
    Logs[Trade Logs]
  end

  Data --> Strategy --> Risk --> Router --> UIRep
  Ticks --> Strategy
  TAIFEX --> Strategy
  Earnings --> Strategy
```
</details>

<p align="center">
  <a href="https://github-readme-stats.vercel.app/api/pin/?username=Weitsenyu&repo=Option&theme=radical">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Weitsenyu&repo=Option&theme=radical" alt="Option Repo Card"/>
  </a>
</p>

---

### 2) YouTube-Shorts-Desktop — 桌面端 Shorts 管理
**Repo**：[`Weitsenyu/YouTube-Shorts-Desktop`](https://github.com/Weitsenyu/YouTube-Shorts-Desktop)

- **技術**：Electron + Node.js（或 PyQt6 版本）、全局快捷鍵、單例、設定與持久化  
- **功能**：桌面觀看／管理 Shorts、API 取數、流暢 UI 互動

<p align="center">
  <a href="https://github-readme-stats.vercel.app/api/pin/?username=Weitsenyu&repo=YouTube-Shorts-Desktop&theme=radical">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Weitsenyu&repo=YouTube-Shorts-Desktop&theme=radical" alt="YSD Repo Card"/>
  </a>
</p>

---

## 🛡️ 績效與風控觀念 · Performance & Risk

> <b>原則重於數字</b>：市場會變，系統要抗壓。  
> 以 <b>回撤控制（MDD）</b>、<b>動態避險</b>、<b>OCO 風控</b>、<b>監控告警</b> 為核心。

- <b>系統面</b>  
  - <b>Greeks / IV 驅動</b> 的賣方策略（Short Strangle / Iron Condor）  
  - <b>OCO 觸發互斥</b>、延時／錯單防護、分層控倉  
  - <b>MTM 監控</b>＋<b>LINE/Discord/Telegram</b> 告警  
  - <b>交易日誌</b>：委託／成交／撤單／異常可追溯  

- <b>回測面</b>  
  - 嚴格納入 <b>交易成本／滑點／停權日／極端事件</b>  
  - 核心指標 <b>Sharpe、MDD、WinRate、PF、PnL 分佈</b>  
  - <b>情境壓力測試</b>：波動擴張／收斂、Gap Risk、提前指派

<details>
<summary>English summary</summary>

<b>System</b>: Greeks/IV-driven short options with <b>OCO</b> risk control, MTM monitoring, alerts, and auditable logs.<br/>
<b>Backtest</b>: Costs, slippage, halt days, outlier events; Sharpe, MDD, WinRate, PF, distributional PnL; scenario stress.
</details>

---

## 🔬 研究與工程 · Research & Engineering

- <b>定價與風險</b>：Black–Scholes、Monte Carlo、ARCH/GARCH、Put-Call Parity 偏離監控  
- <b>資料處理</b>：日內 Tick／Bid-Ask 聚合、波動微結構、TAIFEX／上市櫃資料清洗  
- <b>自動化</b>：Selenium／BS4 排程抓取、Excel 自動匯出、週期風險報表  
- <b>產品化</b>：Docker 容器化、GitHub Actions CI/CD、自動測試與部署

---

## 🕰️ 時間線 · Career Timeline

```mermaid
timeline
  title Wei Tsen-Yu · Career & Projects
  2019-2024 : FJU EE | Researching markets & coding automation
  2024-12   : Options Trader | Short Strangle / Iron Condor, OCO/Risk
  2025-01   : Dev Team Lead | Multi-broker APIs, GUI, monitoring pipeline
  2025-03   : Desktop App | YouTube-Shorts-Desktop
  2025-05   : Options Trading Dashboard (Web) | React + D3 + Socket.IO
  2025-Now  : Quant Trading Engineer | Building robust options systems
```

---

## 📊 統計與徽章 · Stats & Badges

<p align="left">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Weitsenyu&show_icons=true&theme=radical&hide_border=false" alt="GitHub Stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Weitsenyu&layout=compact&theme=radical&hide_border=false" alt="Top Languages"/>
</p>

<p align="left">
  <img src="https://github-profile-trophy.vercel.app/?username=Weitsenyu&theme=dracula&margin-w=10&row=1&column=7" alt="Trophies"/>
</p>

<!-- 若日後想加「蛇形貢獻圖」，需建立 GitHub Action（可參考 Platane/snk）後再啟用下列影像：
<p align="left">
  <img src="https://raw.githubusercontent.com/Weitsenyu/Weitsenyu/output/github-contribution-grid-snake.svg" alt="Snake Contribution"/>
</p>
-->

---

## 🤝 正在尋找 · Open to Work

- <b>Quant Trading Engineer</b>（量化交易工程師）  
- <b>Options System Developer</b>（選擇權系統開發）

> 合作或機會邀約，歡迎透過 <b>LinkedIn</b> 或 <b>Email</b> 聯繫 🙌

---

## 🔗 速連 · Quick Links

- 🧰 Option（自動化選擇權交易平台）：<https://github.com/Weitsenyu/Option>  
- 💻 YouTube-Shorts-Desktop：<https://github.com/Weitsenyu/YouTube-Shorts-Desktop>  
- 💼 LinkedIn：<https://www.linkedin.com/in/weitsenyu/>  
- ✉️ Email：<b>a0906583999@gmail.com</b>

---

## 📎 附錄 · Appendix（研究清單／FAQ）

### ① 研究主題（持續擴充）
- IV 曲面／Skew／Smile 對賣方倉位的風險傳導  
- 事件風險（財報／宏觀）對隱波與定價的影響  
- 微結構：Bid-Ask 擴張與成交不對稱對日內 PnL 的影響  
- 動態避險觸發條件、對沖成本與效率  
- Put-Call Parity 偏離偵測與套利窗口

### ② 回測設計（要點）
- 區間：交易日交集、結算日處理、到期週期  
- 指標：累積／年化報酬、Sharpe、MDD、PF、WinRate  
- 分佈：日內 PnL、尾部風險、Gap Risk 情境  
- 成本：交易費／滑點／借券成本（如適用）

### ③ FAQ
**Q1：為什麼偏好賣方策略？**  
A：波動溢價（vol premia）與 theta 衰減可被系統化捕捉；搭配 <b>IV/Greeks</b> 與 <b>OCO</b> 風控，極端情況更可控與可解釋。

**Q2：如何降低「黑天鵝」風險？**  
A：分層控倉、事件暫停／降槓桿、動態避險、跨券商路由冗餘、風控閾值多層觸發（含撤退機制）。

**Q3：研究 vs 工程？**  
A：我做兩者橋接。<b>研究要能落地</b>；工程要可維護、可觀測、可擴展 —— 這是我最重視的能力結構。

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:6366f1,100:0ea5e9&section=footer" alt="wave footer"/>
</p>
