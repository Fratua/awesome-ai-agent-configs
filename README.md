# Awesome AI Agent Configs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![GitHub stars](https://img.shields.io/github/stars/sovereign-skills/awesome-ai-agent-configs?style=social)](https://github.com/sovereign-skills/awesome-ai-agent-configs)
[![GitHub forks](https://img.shields.io/github/forks/sovereign-skills/awesome-ai-agent-configs?style=social)](https://github.com/sovereign-skills/awesome-ai-agent-configs/fork)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A curated list of resources for configuring, customizing, and deploying AI agents — from identity files to skill systems to persistent memory.

---

## What Are AI Agent Configs?

Modern AI agents aren't just prompts. They're configured through structured files that define their identity, capabilities, memory, and behavior. This paradigm shift — from "prompt engineering" to **agent configuration** — is how production-grade autonomous agents actually work.

The core configuration files:

| File | Purpose |
|------|---------|
| **AGENTS.md** | Operating instructions — the agent's cognitive architecture, workflows, and decision-making protocols |
| **SOUL.md** | Identity and personality — values, communication style, boundaries, and character |
| **MEMORY.md** | Persistent knowledge — what the agent remembers across sessions, learned patterns, operator context |
| **SKILL.md** | Capability definitions — reusable workflows the agent can execute, with triggers and edge cases |
| **USER.md** | Operator profile — preferences, expertise level, and working context |
| **HEARTBEAT.md** | Autonomous schedules — background tasks, monitoring duties, and periodic actions |
| **TOOLS.md** | Tool registry — available capabilities, usage patterns, and environment details |

These files create agents that are **persistent**, **self-improving**, and **deeply personalized** — far beyond what a single system prompt can achieve.

---

## Contents

- [🏗️ Configuration Standards](#️-configuration-standards)
- [📦 Skill Marketplaces](#-skill-marketplaces)
- [🧠 Memory Systems](#-memory-systems)
- [📖 Guides & Tutorials](#-guides--tutorials)
- [🛠️ Tools & Platforms](#️-tools--platforms)
- [💰 Premium Resources](#-premium-resources)
- [📰 Newsletters](#-newsletters)
- [🎓 Research Papers](#-research-papers)
- [🏛️ Community](#️-community)

---

## 🏗️ Configuration Standards

Frameworks and specifications for structuring agent configurations.

- **[Agentfill](https://agentfill.com)** — Open specification for agent configuration files. Defines the AGENTS.md / SOUL.md / MEMORY.md standard that most modern agent platforms support.
- **[AgentSkills.io](https://agentskills.io)** — Registry and specification for portable agent skills. SKILL.md format reference and validation tools.
- **[Anthropic Claude Agent Docs](https://docs.anthropic.com/en/docs/agents)** — Official guidance on building agents with Claude, including tool use and multi-step reasoning patterns.
- **[OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview)** — OpenAI's structured agent configuration via the Assistants API — threads, tools, and instructions.
- **[LangChain Agent Config](https://python.langchain.com/docs/modules/agents/)** — Agent configuration patterns within the LangChain framework, including tool binding and memory integration.
- **[CrewAI Agent Definitions](https://docs.crewai.com/core-concepts/Agents/)** — Role-based agent configuration with goals, backstory, and tool assignments for multi-agent teams.
- **[AutoGen Agent Specs](https://microsoft.github.io/autogen/)** — Microsoft's framework for defining conversational agents with configurable behaviors and group chat patterns.
- **[Google Agent Development Kit](https://google.github.io/adk-docs/)** — Google's open-source framework for building multi-agent systems with structured configuration.
- **[Cursor Rules](https://cursor.directory/)** — Community directory of `.cursorrules` files — project-specific agent behavior configs for the Cursor IDE.

## 📦 Skill Marketplaces

Platforms for discovering, sharing, and installing agent skills.

- **[ClawHub](https://clawhub.io)** — Marketplace for OpenClaw-compatible agent skills. Browse, install, and publish SKILL.md packages with one command. Free and premium skills available.
- **[LangChain Hub](https://smith.langchain.com/hub)** — Community-contributed prompts, chains, and agent templates. Searchable and version-controlled.
- **[OpenAI GPT Store](https://chat.openai.com/gpts)** — Marketplace of custom GPTs with pre-configured instructions, knowledge, and tool access.
- **[CrewAI Tools](https://docs.crewai.com/core-concepts/Tools/)** — Built-in and community tools for CrewAI agents — web scraping, file I/O, search, and more.
- **[Composio](https://composio.dev/)** — Integration platform providing 250+ tools for AI agents across SaaS platforms, with managed authentication.
- **[AgentOps Marketplace](https://agentops.ai/)** — Observability and tooling marketplace for agent developers. Monitoring, debugging, and optimization.

## 🧠 Memory Systems

Approaches and tools for persistent agent memory across sessions.

- **File-Based Memory (MEMORY.md pattern)** — The simplest and most transparent approach: structured markdown files that agents read at session start and update as they learn. Used by [OpenClaw](https://openclaw.io) and the Agentfill standard. Zero infrastructure, fully auditable.
- **[Mem0](https://mem0.ai/)** — Intelligent memory layer for AI agents. Automatic extraction of facts, preferences, and context from conversations with vector + graph storage.
- **[Zep](https://www.getzep.com/)** — Long-term memory for AI assistants. Enriches chat history with summaries, entities, and temporal awareness. Open-source core.
- **[Letta (MemGPT)](https://letta.com/)** — Agents with self-editing memory and context management. Originally the MemGPT research project — uses tiered memory (core, archival, recall).
- **[ChromaDB](https://www.trychroma.com/)** — Open-source embedding database frequently used as agent memory. Simple API, runs locally or in the cloud.
- **[LangMem](https://langchain-ai.github.io/long-term-memory/)** — LangChain's long-term memory SDK. Extracts and consolidates memories from conversations into a semantic knowledge base.
- **[Pinecone](https://www.pinecone.io/)** — Managed vector database commonly used as the backing store for agent long-term memory and RAG pipelines.
- **[Weaviate](https://weaviate.io/)** — Open-source vector database with hybrid search. Strong support for agent memory patterns and multi-modal data.

## 📖 Guides & Tutorials

Learn how to build, configure, and deploy AI agents effectively.

- **[AI Agent Weekly — Newsletter Archive](https://aiagentweekly.com/archive)** — In-depth articles on agent configuration, skill design, memory architecture, and the business of AI agents. Updated weekly.
- **[Building Your First AGENTS.md](https://aiagentweekly.com/guides/first-agents-md)** — Step-by-step guide to writing your first agent configuration file, from basic instructions to full cognitive architecture.
- **[The SOUL.md Playbook](https://aiagentweekly.com/guides/soul-md-playbook)** — How to craft agent personalities that are consistent, useful, and aligned with your goals.
- **[Anthropic's Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)** — Research-backed guide covering workflows, tool use, and orchestration patterns for production agents.
- **[OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)** — Foundational techniques that apply directly to agent configuration writing.
- **[DeepLearning.AI — AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)** — Free course on building stateful agents with LangGraph, covering persistence and human-in-the-loop.
- **[LangChain — Build an Agent](https://python.langchain.com/docs/tutorials/agents/)** — Tutorial on building a conversational agent with tool access, memory, and structured outputs.
- **[Lilian Weng — LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)** — Comprehensive overview of agent architectures, planning strategies, and memory mechanisms. Essential reading.
- **[The Prompt Report (2024)](https://arxiv.org/abs/2406.06608)** — Systematic survey of prompting techniques including agent-specific patterns. Academic but practical.
- **[Simon Willison's Agent Blog Posts](https://simonwillison.net/tags/agents/)** — Thoughtful, practical writing on AI agents from a veteran developer. Covers real-world usage and gotchas.

## 🛠️ Tools & Platforms

Software for building, running, and managing AI agents.

- **[OpenClaw](https://openclaw.io)** — The autonomous agent runtime. Connects Claude, GPT, and other models to your local machine with tools, memory, skills, and scheduling. The platform this awesome list was built with.
- **[AI Agent Directory](https://aiagentweekly.com/directory)** — Curated directory of AI agent tools, platforms, and services. Filterable by category, pricing, and use case.
- **[LangChain](https://langchain.com/)** — The most popular framework for building LLM applications and agents. Python and JavaScript SDKs.
- **[LangGraph](https://langchain-ai.github.io/langgraph/)** — Framework for building stateful, multi-step agent workflows as graphs. Supports cycles, persistence, and human-in-the-loop.
- **[CrewAI](https://crewai.com/)** — Multi-agent orchestration platform. Define teams of agents with roles, goals, and collaboration patterns.
- **[AutoGen](https://microsoft.github.io/autogen/)** — Microsoft's multi-agent conversation framework. Supports diverse agent types and group chat patterns.
- **[Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/)** — Microsoft's SDK for integrating LLMs into applications with plugin architectures and planners.
- **[Haystack](https://haystack.deepset.ai/)** — Open-source framework by deepset for building RAG pipelines and agents with modular components.
- **[Rivet](https://rivet.ironcladapp.com/)** — Visual programming environment for building AI agent logic. Drag-and-drop node graphs for complex workflows.
- **[Dify](https://dify.ai/)** — Open-source platform for building LLM apps and agents with visual workflows, RAG, and model management.
- **[n8n AI Agents](https://n8n.io/ai)** — Low-code workflow automation with native AI agent nodes. Connect agents to 400+ integrations.
- **[Flowise](https://flowiseai.com/)** — Open-source drag-and-drop tool for building customized LLM flows and agents. Self-hostable.
- **[Dust](https://dust.tt/)** — Platform for building and deploying custom AI agents for teams with managed data connections and tool use.
- **[Claude Code](https://docs.anthropic.com/en/docs/claude-code)** — Anthropic's official CLI agent for coding tasks. Agentic coding with file editing, terminal access, and web search.

## 💰 Premium Resources

Professional-grade templates, configurations, and training for serious agent builders.

- **[Sovereign Skills Store](https://sovereignskills.lemonsqueezy.com)** — Premium agent configuration templates, advanced SKILL.md packs, and production-ready AGENTS.md architectures. Battle-tested configs used in real autonomous workflows.
  - 🔥 **SOVEREIGN AGENTS.md** — Complete cognitive architecture for autonomous agents with self-learning, self-review, and evolution loops.
  - 🧠 **Memory Architecture Pack** — Production MEMORY.md templates with pruning strategies, categorization systems, and cross-session persistence patterns.
  - ⚡ **Skill Starter Kit** — 10 essential SKILL.md files covering research, code review, content creation, deployment, and monitoring.
- **[LangChain Academy](https://academy.langchain.com/)** — Structured courses on building agents with LangChain and LangGraph. Free and paid tiers.
- **[Promptbase](https://promptbase.com/)** — Marketplace for buying and selling prompts and agent configurations across multiple platforms.

## 📰 Newsletters

Stay current on AI agent development, tools, and techniques.

- **[AI Agent Weekly](https://aiagentweekly.com)** ⭐ — The newsletter for agent builders. Weekly coverage of new tools, configuration techniques, skill development, and the agent ecosystem. Written by practitioners, not marketers.
- **[Ben's Bites](https://bensbites.beehiiv.com/)** — Daily AI news with frequent agent coverage. One of the most popular AI newsletters.
- **[The Rundown AI](https://www.therundown.ai/)** — Daily AI news and tutorials, including agent platform updates and tool releases.
- **[AI Valley](https://www.theaivalley.com/)** — Weekly newsletter covering AI tools, including agent platforms and automation tools.
- **[Latent Space](https://www.latent.space/)** — Deep technical podcast and newsletter. Excellent episodes on agent architectures and LLM tooling.
- **[ImportAI](https://jack-clark.net/)** — Weekly newsletter by Jack Clark (co-founder of Anthropic) covering AI research including agent-relevant papers.

## 🎓 Research Papers

Academic foundations of agent configuration and architecture.

- **[Cognitive Architectures for Language Agents (CoALA)](https://arxiv.org/abs/2309.02427)** — Framework for understanding language agent architectures through the lens of cognitive science. Defines memory, action, and decision-making modules.
- **[A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432)** — Comprehensive survey of LLM agent architectures, capabilities, and evaluation. Covers profile, memory, planning, and action modules.
- **[AgentBench](https://arxiv.org/abs/2308.03688)** — Benchmark for evaluating LLMs as agents across 8 environments. Useful for understanding agent capability gaps.
- **[Toolformer](https://arxiv.org/abs/2302.04761)** — Foundational paper on teaching language models to use tools. Underpins modern agent tool-use patterns.
- **[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)** — Stanford/Google paper on agents with memory, reflection, and planning. Influenced modern agent memory design.
- **[ReAct: Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)** — The reasoning + acting paradigm used by most agent frameworks. Essential reading.
- **[Reflexion](https://arxiv.org/abs/2303.11366)** — Agents that learn from verbal self-reflection. Directly relevant to self-review and self-improvement patterns in AGENTS.md configs.

## 🏛️ Community

Places to discuss, learn, and collaborate on AI agent development.

- **[r/AIAgents](https://www.reddit.com/r/AIAgents/)** — Active subreddit for AI agent discussion, tool sharing, and troubleshooting.
- **[r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/)** — Community focused on running LLMs locally. Relevant for self-hosted agent setups.
- **[LangChain Discord](https://discord.gg/langchain)** — Large community for LangChain/LangGraph agent builders.
- **[AI Agent Builders (X/Twitter)](https://twitter.com/i/communities)** — Search for AI agent communities. Active discussion of tools, configs, and techniques.
- **[Hacker News — AI Agents](https://hn.algolia.com/?q=ai+agents)** — Technical discussion of agent tools and architectures.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. You can also [suggest a resource](https://github.com/sovereign-skills/awesome-ai-agent-configs/issues/new?template=add-resource.md) via issue.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.

---

<p align="center">
  <sub>Curated with ❤️ by <a href="https://aiagentweekly.com">AI Agent Weekly</a> · Powered by <a href="https://openclaw.io">OpenClaw</a></sub>
</p>
