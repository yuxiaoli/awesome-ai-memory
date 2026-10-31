# AI 記憶精選

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | [简体中文](README.zh-CN.md) | **繁體中文**

精選 AI 記憶引擎、智能體、整合工具、知識儲存及學習資源，支援保留、整理、檢索和重用跨對話及跨任務的上下文。

## 記憶引擎及服務

為 AI 應用擷取、維護及檢索長期用戶或智能體上下文的引擎、程式庫和服務。

- [EverOS](https://github.com/EverMind-AI/EverOS) - 本機記憶執行環境，將對話、檔案和智能體經驗儲存為 Markdown，並提供索引檢索及跨對話記憶整合。
- [memU](https://github.com/NevaMind-AI/memU) - 共享記憶系統，將智能體對話歷史提煉為可檢索的個人知識及可重用的 Markdown 技能。
- [Memobase](https://github.com/memodb-io/memobase) - 用戶記憶服務，將對話轉化為可設定的用戶概況及事件時間線，為大型語言模型應用提供個人化上下文。
- [MemOS](https://github.com/MemTensor/MemOS) - 面向大型語言模型及智能體的記憶系統，以圖結構整理多模態長期記憶，支援檢索、編輯、共享及回饋修正。
- [Supermemory](https://github.com/supermemoryai/supermemory) - AI 記憶引擎，可擷取對話事實、維護用戶概況、追蹤資訊變化，並結合文件上下文檢索記憶。
- [TencentDB Agent Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) - 共享智能體記憶平台，保留對話知識及可重用技能，整理文件和程式碼資產，並管理跨對話、跨智能體的存取權限。
- [MindMemOS](https://github.com/mindscale-noah/MindMemOS) - 可遷移的智能體記憶服務，儲存用戶及任務上下文，支援檢索、根據回饋整合記憶，以及將經驗提煉為技能。
- [Mem0](https://github.com/mem0ai/mem0) - 擷取及檢索用戶、對話和智能體資訊的記憶層，為 AI 助手在多次互動中提供個人化上下文。

## 具備持久記憶的智能體及應用

保留個人上下文、項目知識或學習經驗，並在後續互動及任務中重用的智能體和應用。

- [Letta (MemGPT)](https://github.com/letta-ai/letta) - 面向具備持久記憶的有狀態 AI 智能體的歷史程式碼庫，已退役的 Letta V1 伺服器程式保留於 archive 分支。
- [Second Me](https://github.com/Mindverse/Second-Me) - 個人 AI 原型，透過分層記憶建模及本機訓練，根據用戶記憶和上下文建立個人 AI 分身。
- [Codewhale（原 DeepSeek TUI）](https://github.com/Hmbown/DeepSeek-TUI) - 程式開發智能體，可選擇啟用本機記憶，以 Markdown 儲存用戶偏好及程式碼庫慣例，並透過 SQLite 全文檢索跨對話取用。
- [OpenLoopX (LLM4AD Next)](https://github.com/Optima-CityU/LLM4AD_Next) - 由大型語言模型驅動的演算法設計平台，可選擇接入 MindMemOS 長期記憶，在不同任務及項目間檢索和重用經驗、限制與教訓。
- [OpenHuman](https://github.com/tinyhumansai/openhuman) - 以 Rust 開發的智能體執行框架及桌面助手，提供持久化對話和學習內容儲存、上下文檢索，以及記憶檢視和刪除功能。
- [Oh My Pi](https://github.com/can1357/oh-my-pi) - 程式開發智能體，可選擇啟用按項目分隔的記憶，用於保留事實、檢索經驗、編輯已儲存知識，並將對話上下文帶入後續工作。

## 記憶儲存及知識圖譜

以層級結構、本機筆記或知識圖譜整理智能體記憶的儲存工具，讓持久上下文可供檢索及重用。

- [Lithium](https://github.com/0xJaksun/lithium-core) - 以 PostgreSQL 為基礎的智能體上下文儲存工具，提供層級檢索、條目版本管理及 MCP 工具，用於保留決策和項目知識。
- [Flowix](https://github.com/text2future/flowix) - 本機 Markdown 筆記簿，透過 MCP 及命令列工具搜尋、讀取、建立和更新筆記，為 AI 智能體提供共享的持久上下文。
- [Cognee](https://github.com/topoteretes/cognee) - 知識圖譜記憶平台，將文件、程式碼、對話及從對話中學到的經驗互相關聯，供智能體持續檢索和重用。
- [Graphiti](https://github.com/getzep/graphiti) - 面向 AI 智能體的時序上下文圖框架，記錄事實變化及事件來源，並結合語義、關鍵字和圖檢索。
- [MemPalace](https://github.com/mempalace/mempalace) - 在本機保留原始對話文字的記憶儲存工具，提供層級整理、語義搜尋、時間關係及 MCP 存取。

## 程式開發智能體記憶整合

為後續開發保留程式開發對話上下文、工程經驗、用戶偏好或架構決策的記憶服務及外掛程式。

- [agentmemory](https://github.com/rohitg00/agentmemory) - 面向程式開發智能體的持久記憶服務，提供對話擷取、混合檢索、記憶整合，以及 MCP 和 REST 介面。
- [MemoraX Code](https://github.com/memorax-ai/memorax-code) - 面向程式開發智能體的共享記憶層，跨對話保留工程經驗、程式碼庫知識、用戶偏好及可重用流程。
- [claude-supermemory](https://github.com/supermemoryai/claude-supermemory) - Claude Code 外掛程式，透過 Supermemory 儲存持久的對話上下文、檢索相關記憶，並跨對話共享程式碼庫記憶。
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - 本機 MCP 伺服器，儲存程式碼知識圖譜及架構決策記錄，供 AI 程式開發智能體跨對話重用。
- [Claude-Mem](https://github.com/thedotmack/claude-mem) - 持久記憶系統，可擷取程式開發智能體的工具觀察結果、產生摘要，並為後續對話檢索項目上下文。
- [SoloPup Memory](https://github.com/OakcoderX/solopup-memory) - DeepSeek Harness 文字記憶外掛（公開測試版），以詞彙比對檢索重用原文來源、全域／專案範圍、條件及修訂歷史。


## 評測及學習資源

用於理解、實作及比較 AI 記憶機制的評測程式碼和可執行教學範例。

- [Agent Memory Leaderboard](https://github.com/AML-memory/agent-memory-leaderboard) - 公開的評測介面約定及評分實作，透過統一的新增和搜尋協定比較長期記憶系統。
- [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) - AI 工程課程，提供可執行的 Python 教學範例，涵蓋智能體上下文分頁、可編輯記憶區塊、記憶整合及混合記憶儲存。
