# Awesome Self-Hosted Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source tools, frameworks, and resources for running AI agents fully self-hosted - no vendor lock-in, no usage fees, full control.

## Contents

- [Agent Frameworks](#agent-frameworks)
- [LLM Backends](#llm-backends)
- [Memory and Vector Stores](#memory-and-vector-stores)
- [Orchestration and Monitoring](#orchestration-and-monitoring)
- [Cost and Budget Tools](#cost-and-budget-tools)
- [Deployment](#deployment)
- [Learning Resources](#learning-resources)

## Agent Frameworks

- [AutoGen](https://github.com/microsoft/autogen) - Multi-agent conversation framework from Microsoft Research supporting customizable and conversable agents.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing autonomous AI agents that collaborate on complex tasks.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor agent applications with cycles and controllability.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - Dev-first framework for building, managing, and running autonomous agents with tool integrations.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Browser-based autonomous agent platform, fully self-hostable with Docker.
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - Open-source autonomous software engineer agent that plans, writes code, and uses a sandboxed terminal.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end LLM framework for building pipelines with retrieval, generation, and agent components.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework that takes a one-line requirement and outputs PRDs, design docs, and code.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - Minimal task-driven autonomous agent that creates, prioritizes, and executes tasks using LLMs.

## LLM Backends

- [Ollama](https://github.com/ollama/ollama) - Run open-weight LLMs locally with a simple CLI and REST API. Supports GGUF models out of the box.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - C/C++ inference engine for LLMs with broad hardware support including CPU, CUDA, Metal, and Vulkan.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving engine with PagedAttention for efficient memory management.
- [LocalAI](https://github.com/mudler/LocalAI) - Drop-in OpenAI-compatible REST API that runs LLMs, image generators, and audio models locally.
- [LM Studio](https://lmstudio.ai/) - Desktop app for discovering, downloading, and running local LLMs with an OpenAI-compatible server.
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) - Gradio-based web UI for running large language models with multiple backend support.
- [Jan](https://github.com/janhq/jan) - Open-source desktop client for running LLMs offline with a ChatGPT-style interface.

## Memory and Vector Stores

- [Chroma](https://github.com/chroma-core/chroma) - Embeddable open-source vector database designed for AI applications with simple APIs.
- [Weaviate](https://github.com/weaviate/weaviate) - Cloud-native vector database with built-in vectorization modules and hybrid search.
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector similarity search engine written in Rust with filtering support.
- [Milvus](https://github.com/milvus-io/milvus) - Distributed vector database built for scalable similarity search across billions of vectors.
- [pgvector](https://github.com/pgvector/pgvector) - PostgreSQL extension for vector similarity search, integrates with existing Postgres workflows.
- [Redis VSS](https://github.com/RediSearch/RediSearch) - Vector similarity search module for Redis, useful for low-latency retrieval in agent memory.

## Orchestration and Monitoring

- [Prefect](https://github.com/PrefectHQ/prefect) - Workflow orchestration tool for building, scheduling, and monitoring data and ML pipelines.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution platform for running reliable distributed workflows and long-running agent tasks.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform for tracing, evaluating, and debugging agent runs. Self-hostable.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability platform with request logging, caching, and rate limiting.
- [agent-probe](https://github.com/arcane-bear/agent-probe) - Lightweight CI/CD health-check workflow for AI agent repos.
- [Phoenix](https://github.com/Arize-ai/phoenix) - Open-source observability for LLM applications with tracing, evaluation, and dataset management.
- [Command OS](https://github.com/faraz-jb/ai-invention-command-os) - Multi-tenant control plane for AI agencies: one dashboard + one MCP endpoint to run every client's agents, projects, sites, and revenue. Remote-exec without SSH (pull-based connect-back), 19-tool MCP server, SQLite, self-hosted with Docker.

## Cost and Budget Tools

- [agent-cost-cli](https://github.com/arcane-bear/agent-cost-cli) - CLI tool for estimating LLM API costs across providers.
- [LiteLLM](https://github.com/BerriAI/litelllm) - Proxy server that provides a unified interface to 100+ LLMs with spend tracking and budget controls.
- [OpenRouter](https://github.com/OpenRouterTeam/openrouter-runner) - Self-hostable model runner with cost comparison across providers.

## Deployment

- [Coolify](https://github.com/coollabsio/coolify) - Self-hostable Heroku/Netlify alternative for deploying apps, databases, and services with Docker.
- [Dokku](https://github.com/dokku/dokku) - Minimal PaaS implementation powered by Docker that runs on a single server.
- [CapRover](https://github.com/caprover/caprover) - Free and open-source PaaS with automated HTTPS, Docker Swarm, and one-click app deploys.
- [Portainer](https://github.com/portainer/portainer) - Lightweight container management UI for Docker, Swarm, Kubernetes, and Nomad environments.
- [Kamal](https://github.com/basecamp/kamal) - Deploy web apps anywhere with zero downtime using Docker and simple YAML configuration.
- [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container agent stacks with a single YAML file. The standard for local-first deployment.

## Learning Resources

- [Self-Hosting Guide](https://github.com/awesome-selfhosted/awesome-selfhosted) - Comprehensive directory of self-hostable software across all categories.
- [Practical Guide to Building Agents](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic's guide to patterns and best practices for agent design.
- [LangChain AI Handbook](https://www.pinecone.io/learn/series/langchain/) - Tutorial series covering LLM apps, agents, and retrieval-augmented generation.
- [r/selfhosted](https://www.reddit.com/r/selfhosted/) - Active Reddit community for self-hosting discussions, including AI and LLM setups.
- [LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Community focused on running LLMs locally with hardware guides, benchmarks, and tutorials.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](.github/CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

---

*Maintained by [Tijo Gaucher](https://github.com/arcane-bear) - Built with [RapidClaw](https://rapidclaw.dev), AI agent infrastructure for teams*
