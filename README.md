# Awesome AI Agents

A curated collection of open-source frameworks, tools, research papers, and learning resources for building AI agents, including single and multi‑agent systems. Agents combine large language models (LLMs) with memory, planning, tool integration, and reasoning to solve complex tasks autonomously. This repository provides quick links to each resource so that you can jump directly to projects, papers, or tutorials.


## Frameworks & Libraries

### General Orchestration Frameworks
- **LangChain** – modular LLM application framework for chaining prompts, tools, and memory. [GitHub](https://github.com/langchain-ai/langchain)
- **Microsoft Semantic Kernel** – orchestration SDK supporting planners and tool skills for .NET and Python. [GitHub](https://github.com/microsoft/semantic-kernel)
- **LlamaIndex** – data-centric agent framework for retrieval‑augmented generation and knowledge integration. [GitHub](https://github.com/jerryjliu/llama_index)
- **Pydantic‑AI** – type-safe agent framework using Pydantic models to define tool interfaces. [GitHub](https://github.com/pydantic-ai/pydantic-ai)
- **OpenAI Agents SDK** – lightweight experimental framework for defining agents as Python functions that call tools when needed. [Docs](https://platform.openai.com/docs/assistants/overview)

### Multi‑Agent & Role‑Based Frameworks
- **Microsoft AutoGen** – orchestrates multiple LLM or tool agents via asynchronous conversation threads. [GitHub](https://github.com/microsoft/AutoGen)
- **CrewAI** – role‑based framework that treats an agent solution as a crew of specialized agents working together. [GitHub](https://github.com/crewAIInc/crewAI)
- **LangChain + LangGraph** – extension to LangChain that expresses agent workflows as directed graphs with branching and joining. [GitHub](https://github.com/langchain-ai/langgraph)
- **OpenAgents** – open platform for deploying language agents with tool integrations “in the wild.” [GitHub](https://github.com/OpenAgentsInc/openagents)
- **AgentVerse** – platform to run multiple LLM-based agents in simulated environments; useful for studying emergent behaviors. [GitHub](https://github.com/OpenBML/AgentVerse)

### Lightweight & Specialized Agents
- **SmolAgents** – minimalist library for agents that write and execute Python code to accomplish tasks. [GitHub](https://github.com/smol-ai/smolagents)  
  *See also the [Developer agent](https://github.com/smol-ai/developer) which scaffolds entire codebases from natural‑language specs.*
- **Auto‑GPT** – pioneering autonomous agent that uses an LLM loop to generate and execute tasks until a goal is reached. [GitHub](https://github.com/Significant-Gravitas/Auto-GPT)
- **BabyAGI** – simple task‑creation and execution loop illustrating autonomous agent concepts. [GitHub](https://github.com/yoheinakajima/babyagi)
- **GPT‑Engineer** – agent that generates full software projects based on a high‑level specification. [GitHub](https://github.com/AntonOsika/gpt-engineer)
- **BMTools** – registry of tools/APIs and helpers for equipping agents with capabilities such as web search and translation. [GitHub](https://github.com/OpenBMB/BMTools)
- **Langroid** – multi‑agent programming framework focusing on message‑passing between agents. [GitHub](https://github.com/langroid/langroid)
- **Phidata** – multi‑modal agent framework with built‑in tools and UI components. [GitHub](https://github.com/agno-agi/phidata)
-   * Hugging Face Transformers Agents – API for using pre‑defined tools and models via natural language. [Docs](htps://huggingface.co/docs/transformers/agent)
    * 
 
 ### Tracing & Observability Tools
  * Agenta – open‑source LLMOps platform for prototyping, evaluating and observing LLM apps; core licensed MIT and self‑hostable. [GitHub](https://github.com/agenta-ai/agenta)
  * Arize Phoenix – open‑source LLM tracing and evaluation system built on OpenTelemetry; self‑hostable. [GitHub](https://github.com/Arize-ai/phoenix)
  * Comet Opik – open‑source LLM evaluation and observability tool offering free full feature set. [GitHub](https://github.com/comet-ml/opik)
  * LangDB AI Gateway – Apache‑2.0 licensed gateway bridging LLM traffic with built‑in tracing capabilities; open source. [GitHub](https://github.com/langdb/ai-gateway)
  * Langfuse – open‑source LLM engineering platform for observability and evaluation; self‑hostable. [GitHub](https://github.com/langfuse/langfuse)
  * Langtrace – open‑source observability and evaluation platform for AI agents. [GitHub](https://github.com/accelerate-society/langtrace)
  * MLflow (self‑hosted) – open‑source platform for managing the ML lifecycle including experiments and LLM observability; Apache‑2.0 license. [GitHub](https://github.com/mlflow/mlflow)
  * Okahu Monocle – open‑source tracing framework for GenAI applications maintained by the Linux Foundation. [GitHub](https://github.com/OkahuAI/monocle)
  * Pydantic Logfire – MIT‑licensed open‑source Python SDK for logging and tracing LLM events built on OpenTelemetry. [GitHub](https://github.com/pydantic/logfire)

## Research & Papers

### Reasoning & Planning
- **ReAct: Synergizing Reasoning and Acting** (Yao et al., 2022) – introduced prompting pattern interleaving “thoughts” and “actions” to improve reasoning. [arXiv](https://arxiv.org/abs/2210.03629)
- **Chain‑of‑Thought Prompting** (Wei et al., 2022) – encourages the model to produce step‑by‑step reasoning. [arXiv](https://arxiv.org/abs/2201.11903)
- **Tree‑of‑Thoughts** (Yao et al., 2023) – explores multiple branches of reasoning to solve difficult problems. [arXiv](https://arxiv.org/abs/2305.10601)
- **Reflexion / Plan‑and‑Reflect** (Shinn et al., 2023) – adds a self‑critique loop for long‑horizon tasks. [arXiv](https://arxiv.org/abs/2309.00668)

### Tool Use & Integration
- **Toolformer** (Schick et al., 2023) – demonstrates self‑supervised fine‑tuning for API calling. [arXiv](https://arxiv.org/abs/2302.04761)
- **HuggingGPT** (Shen et al., 2023) – uses an LLM controller to orchestrate multiple expert models. [arXiv](https://arxiv.org/abs/2303.17580)
- **MRKL Systems** (Efroni et al., 2022) – blends large models with specialist modules. [arXiv](https://arxiv.org/abs/2205.12407)
- **API‑Bank** (Li et al., 2023) – benchmark and dataset for evaluating tool‑augmented LLMs. [arXiv](https://arxiv.org/abs/2308.07825)

### Memory & Long‑Term Autonomy
- **Generative Agents** (Park et al., 2023) – agents with long‑term memory that simulate humans in a virtual town. [arXiv](https://arxiv.org/abs/2304.03442)
- **Survey on Memory Mechanisms of LLM Agents** (Zhang et al., 2024) – overview of memory architectures and retrieval strategies. [arXiv](https://arxiv.org/abs/2402.13736)

### Multi‑Agent Communication & Collaboration
- **CAMEL: Communicative Agents for “Mind” Exploration** (Li et al., 2023) – agents collaborate through role‑playing dialogues. [arXiv](https://arxiv.org/abs/2303.17760)
- **MetaGPT** (Hong et al., 2023) – organizes agents into roles (PM, engineer, QA) to deliver complete software projects. [arXiv](https://arxiv.org/abs/2308.07370)

### Evaluation & Benchmarks
- **AgentBench** (Liu et al., 2023) – evaluates autonomous agents across diverse simulated environments. [arXiv](https://arxiv.org/abs/2308.07258)
- **Evaluating LLM Agents: A Survey** (Wang et al., 2023) – reviews metrics and benchmarks for agent evaluation. [arXiv](https://arxiv.org/abs/2312.04323)

## Tutorials & Guides
- **LLM Powered Autonomous Agents** (Lilian Weng, 2023) – blog post explaining core agent components such as planning, memory, and tool use. [Blog](https://lilianweng.github.io/posts/2023-06-15-agent/)
- **Prompt Engineering Guide: LLM Agents** (Dair.ai, 2023) – comprehensive guide on building agents, including ReAct, CoT, and reflection prompting. [Guide](https://github.com/dair-ai/Prompt-Engineering-Guide#llm-agents)
- **Building Autonomous Agents with LangChain** (PyCon 2023 talk) – video tutorial demonstrating LangChain agents with Wikipedia and calculator tools. [Video](https://www.youtube.com/watch?v=example)
- **OpenAI Cookbook Examples** – function‑calling tutorials showing how an LLM can call tools via structured JSON. [Docs](https://platform.openai.com/docs/guides/function-calling)

## Repository Structure

The repository groups resources into three main sections:

1. **Frameworks & Libraries:** open‑source codebases for building agents. Tools are grouped by their primary focus (orchestration, multi‑agent, lightweight).
2. **Research & Papers:** influential academic papers and technical reports grouped by topic (reasoning, tool use, memory, collaboration, evaluation).
3. **Tutorials & Guides:** educational materials including blog posts, notebooks, and videos that teach agent design and best practices.

Feel free to browse the sections above and click on the links to go directly to the source.

## Contribution Guidelines

We welcome contributions! To add a new tool, paper, or guide:

- Ensure that it is relevant to AI agents, multi‑agent systems, or LLM‑driven autonomy.
- Prefer resources that are well‑maintained, peer‑reviewed, or widely used.
- Add entries under the appropriate section with a brief description and a **link** to the original source.
- Keep descriptions factual and concise (1–3 sentences) and maintain alphabetical order where applicable.
- Submit a pull request or open an issue with details. Please adhere to our code of conduct and follow the existing Markdown style.

