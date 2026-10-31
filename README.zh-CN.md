# AI 记忆精选

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

[English](README.en.md) | **简体中文** | [繁體中文](README.zh-HK.md)

精选 AI 记忆引擎、智能体、集成工具、知识存储与学习资源，帮助保留、组织、检索并复用跨会话和跨任务的上下文。

## 记忆引擎与服务

为 AI 应用捕获、维护和检索长期用户或智能体上下文的引擎、库与服务。

- [EverOS](https://github.com/EverMind-AI/EverOS) - 本地记忆运行时，将对话、文件和智能体经验保存为 Markdown，并提供索引检索与跨会话记忆整合。
- [memU](https://github.com/NevaMind-AI/memU) - 共享记忆系统，将智能体会话历史提炼为可检索的个人知识和可复用的 Markdown 技能。
- [Memobase](https://github.com/memodb-io/memobase) - 用户记忆服务，将对话转化为可配置的用户画像和事件时间线，为大语言模型应用提供个性化上下文。
- [MemOS](https://github.com/MemTensor/MemOS) - 面向大语言模型与智能体的记忆系统，以图结构组织多模态长期记忆，支持检索、编辑、共享与反馈修正。
- [Supermemory](https://github.com/supermemoryai/supermemory) - AI 记忆引擎，可提取对话事实、维护用户画像、跟踪信息变化，并结合文档上下文检索记忆。
- [TencentDB Agent Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) - 共享智能体记忆平台，保留对话知识与可复用技能，组织文档和代码资产，并管理跨会话、跨智能体的访问权限。
- [MindMemOS](https://github.com/mindscale-noah/MindMemOS) - 可迁移的智能体记忆服务，保存用户与任务上下文，支持检索、基于反馈的记忆整合和经验到技能的提炼。
- [Mem0](https://github.com/mem0ai/mem0) - 提取和检索用户、会话及智能体信息的记忆层，为 AI 助手在多次交互中提供个性化上下文。

## 具备持久记忆的智能体与应用

保留个人上下文、项目知识或学习经验，并在后续交互与任务中复用的智能体和应用。

- [Letta (MemGPT)](https://github.com/letta-ai/letta) - 面向具备持久记忆的有状态 AI 智能体的历史代码仓库，已退役的 Letta V1 服务端保留在 archive 分支。
- [Second Me](https://github.com/Mindverse/Second-Me) - 个人 AI 原型，通过分层记忆建模与本地训练，基于用户记忆和上下文构建个人 AI 分身。
- [Codewhale（原 DeepSeek TUI）](https://github.com/Hmbown/DeepSeek-TUI) - 编程智能体，可选启用本地记忆，以 Markdown 保存用户偏好和代码仓库约定，并通过 SQLite 全文检索跨会话调用。
- [OpenLoopX (LLM4AD Next)](https://github.com/Optima-CityU/LLM4AD_Next) - 由大语言模型驱动的算法设计平台，可选接入 MindMemOS 长期记忆，在不同任务与项目间检索和复用经验、约束及教训。
- [OpenHuman](https://github.com/tinyhumansai/openhuman) - 基于 Rust 的智能体运行框架与桌面助手，提供持久化对话和学习内容存储、上下文检索，以及记忆查看与删除功能。
- [Oh My Pi](https://github.com/can1357/oh-my-pi) - 编程智能体，可选启用按项目隔离的记忆，用于保留事实、检索经验、编辑已存知识，并将会话上下文带入后续工作。

## 记忆存储与知识图谱

以层级结构、本地笔记或知识图谱组织智能体记忆的存储工具，使持久上下文可被检索与复用。

- [Lithium](https://github.com/0xJaksun/lithium-core) - 基于 PostgreSQL 的智能体上下文存储，提供层级检索、条目版本管理及 MCP 工具，用于保留决策与项目知识。
- [Flowix](https://github.com/text2future/flowix) - 本地 Markdown 笔记本，通过 MCP 与命令行工具搜索、读取、创建和更新笔记，为 AI 智能体提供共享的持久上下文。
- [Cognee](https://github.com/topoteretes/cognee) - 知识图谱记忆平台，将文档、代码、对话和会话中学到的经验关联起来，供智能体持久检索与复用。
- [Graphiti](https://github.com/getzep/graphiti) - 面向 AI 智能体的时序上下文图框架，记录事实变化与事件来源，并结合语义、关键词和图检索。
- [MemPalace](https://github.com/mempalace/mempalace) - 在本地保留原始对话文本的记忆存储，提供层级组织、语义搜索、时间关系与 MCP 访问。

## 编程智能体记忆集成

为后续开发保留编程会话上下文、工程经验、用户偏好或架构决策的记忆服务与插件。

- [agentmemory](https://github.com/rohitg00/agentmemory) - 面向编程智能体的持久记忆服务，提供会话捕获、混合检索、记忆整合以及 MCP 和 REST 接口。
- [MemoraX Code](https://github.com/memorax-ai/memorax-code) - 面向编程智能体的共享记忆层，跨会话保留工程经验、代码仓库知识、用户偏好与可复用流程。
- [claude-supermemory](https://github.com/supermemoryai/claude-supermemory) - Claude Code 插件，借助 Supermemory 保存持久的对话上下文、检索相关记忆，并跨会话共享代码仓库记忆。
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - 本地 MCP 服务，保存代码知识图谱与架构决策记录，供 AI 编程智能体跨会话复用。
- [Claude-Mem](https://github.com/thedotmack/claude-mem) - 持久记忆系统，可捕获编程智能体的工具观察结果、生成摘要，并为后续会话检索项目上下文。
- [SoloPup Memory](https://github.com/OakcoderX/solopup-memory) - DeepSeek Harness 文字记忆插件（公开测试版），以词面检索复用原话来源、全局/项目范围、条件与修订历史。


## 评测与学习资源

用于理解、实现和比较 AI 记忆机制的评测代码与可运行教学示例。

- [Agent Memory Leaderboard](https://github.com/AML-memory/agent-memory-leaderboard) - 公开的评测接口约定与评分实现，通过统一的添加和搜索协议比较长期记忆系统。
- [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) - AI 工程课程，提供可运行的 Python 教学示例，涵盖智能体上下文分页、可编辑记忆块、记忆整合与混合记忆存储。
