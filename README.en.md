# Awesome AI Memory

<a href="https://awesome.re"><img src="assets/badges/awesome-badge-official-flat2.svg" alt="Awesome" height="24" align="middle"></a>&ensp;<a href="https://awesome.re"><img src="assets/badges/awesome-badge-flat.svg" alt="Awesome (flat)" height="24" align="middle"></a>

**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-HK.md)

A curated collection of AI memory engines, agents, integrations, knowledge stores, and learning resources for retaining, organizing, retrieving, and reusing context across interactions and tasks.

## Memory Engines and Services

Engines, libraries, and services that capture, maintain, and retrieve lasting user or agent context for AI applications.

- [EverOS](https://github.com/EverMind-AI/EverOS) - Local memory runtime that stores conversations, files, and agent experience as Markdown, with indexed retrieval and consolidation across sessions.
- [memU](https://github.com/NevaMind-AI/memU) - Shared memory system that distills agent session history into retrievable personal knowledge and reusable Markdown skills.
- [Memobase](https://github.com/memodb-io/memobase) - User memory service that turns conversations into configurable profiles and event timelines for personalized LLM applications.
- [MemOS](https://github.com/MemTensor/MemOS) - Memory system for LLMs and agents that manages graph-organized, multimodal long-term memory with retrieval, editing, sharing, and feedback correction.
- [Supermemory](https://github.com/supermemoryai/supermemory) - AI memory engine that extracts conversational facts, maintains user profiles, tracks changing information, and retrieves memories alongside document context.
- [TencentDB Agent Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) - Shared agent memory platform that preserves conversation knowledge and reusable skills, organizes document and code assets, and manages access across sessions and agents.
- [MindMemOS](https://github.com/mindscale-noah/MindMemOS) - Portable agent memory service for user and task context, with retrieval, feedback-driven consolidation, and experience-to-skill distillation.
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer that extracts and retrieves user, session, and agent information to support personalized AI assistants across interactions.

## Agents and Applications with Persistent Memory

Agents and applications that preserve personal context, project knowledge, or learned experience for reuse in later interactions and tasks.

- [Letta (MemGPT)](https://github.com/letta-ai/letta) - Legacy repository for stateful AI agents with persistent memory, with the retired Letta V1 server preserved on the archive branch.
- [Second Me](https://github.com/Mindverse/Second-Me) - Personal AI prototype that uses hierarchical memory modeling and local training to build an AI representation from a user's memories and context.
- [Codewhale (formerly DeepSeek TUI)](https://github.com/Hmbown/DeepSeek-TUI) - Coding agent with opt-in local memory for user preferences and repository conventions, stored as Markdown with SQLite full-text retrieval across sessions.
- [OpenLoopX (LLM4AD Next)](https://github.com/Optima-CityU/LLM4AD_Next) - LLM-driven algorithm-design platform with optional MindMemOS-backed long-term memory for recalling experience, constraints, and lessons across tasks and projects.
- [OpenHuman](https://github.com/tinyhumansai/openhuman) - Rust agent harness and desktop assistant with persistent conversation and learning storage, contextual recall, and memory inspection and deletion.
- [Oh My Pi](https://github.com/can1357/oh-my-pi) - Coding agent with optional project-scoped memory for retaining facts, recalling experience, editing stored knowledge, and carrying session context into later work.

## Memory Stores and Knowledge Graphs

Stores that organize agent memory as hierarchies, local notes, or knowledge graphs so that durable context can be searched and reused.

- [Lithium](https://github.com/0xJaksun/lithium-core) - PostgreSQL-backed context store for AI agents, with hierarchical retrieval, versioned entries, and MCP tools for preserving decisions and project knowledge.
- [Flowix](https://github.com/text2future/flowix) - Local Markdown notebook that provides shared, durable context for AI agents through MCP and CLI tools for searching, reading, creating, and updating notes.
- [Cognee](https://github.com/topoteretes/cognee) - Knowledge graph memory platform that connects documents, code, conversations, and learned session lessons for persistent agent recall.
- [Graphiti](https://github.com/getzep/graphiti) - Framework for building temporal context graphs for AI agents, with evolving facts, episode provenance, and hybrid semantic, keyword, and graph retrieval.
- [MemPalace](https://github.com/mempalace/mempalace) - Conversation memory store that preserves original text locally, with hierarchical organization, semantic search, temporal relationships, and MCP access.

## Coding Agent Memory Integrations

Memory servers and plugins that preserve coding-session context, engineering lessons, preferences, or architectural decisions for later work.

- [agentmemory](https://github.com/rohitg00/agentmemory) - Persistent memory server for coding agents, with session capture, hybrid recall, memory consolidation, and MCP and REST interfaces.
- [MemoraX Code](https://github.com/memorax-ai/memorax-code) - Shared memory layer for coding agents that retains engineering lessons, repository knowledge, user preferences, and reusable procedures across sessions.
- [claude-supermemory](https://github.com/supermemoryai/claude-supermemory) - Claude Code plugin that uses Supermemory to capture durable conversation context, recall relevant memories, and share repository memory across sessions.
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - Local MCP server that preserves code knowledge graphs and architectural decision records for reuse across AI coding sessions.
- [Claude-Mem](https://github.com/thedotmack/claude-mem) - Persistent memory system that captures coding-agent tool observations, generates summaries, and retrieves project context for later sessions.
- [SoloPup Memory](https://github.com/OakcoderX/solopup-memory) - Public-beta DeepSeek Harness text-memory plugin preserving original-source references, global/project scope, conditions and correction history through lexical retrieval.


## Evaluation and Learning Resources

Evaluation code and runnable teaching examples for understanding, implementing, and comparing AI memory mechanisms.

- [Agent Memory Leaderboard](https://github.com/AML-memory/agent-memory-leaderboard) - Public evaluation contracts and scoring implementations for comparing long-term memory systems through a shared add-and-search protocol.
- [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) - AI engineering curriculum with runnable educational Python examples of agent context paging, editable memory blocks, consolidation, and hybrid memory stores.
