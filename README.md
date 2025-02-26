# Welcome to my list of interesting projects!

## Markdown
[Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
The Markdown elements outlined in the original design document.

## Agentic frameworks
[Microsoft.TinyTroupe](https://github.com/microsoft/TinyTroupe)
LLM-powered multiagent persona simulation for imagination enhancement and business insights.

[Dynamiq](https://dynamiq-ai.github.io/dynamiq/)
Dynamiq is your all-in-one Gen AI framework, designed to streamline the development of AI-powered applications. Dynamiq specialises in orchestrating retrieval-augmented generation (RAG) and large language model (LLM) agents.

[Agency Swarm](https://vrsen.github.io/agency-swarm/)
we aim to simplify the agent creation process and enable anyone to create collaborative swarm of agents (Agencies), each with distinct roles and capabilities

[Pydantic AI](https://ai.pydantic.dev/)
PydanticAI is a Python agent framework designed to make it less painful to build production grade applications with Generative AI.

[PhiData](https://www.phidata.com/)
Phidata is a framework for building multi-modal agents and workflows. Build agents with memory, knowledge, tools and reasoning. Build teams of agents that can work together to solve problems. Interact with your agents and workflows using a beautiful Agent UI.

[Smolagents](https://huggingface.co/docs/smolagents/index)
This library is the simplest framework out there to build powerful agents! By the way, wtf are “agents”? We provide our definition in this page, whe’re you’ll also find tips for when to use them or not (spoilers: you’ll often be better off without agents).

[AI Stuite](https://github.com/andrewyng/aisuite)
aisuite makes it easy for developers to use multiple LLM through a standardized interface. Using an interface similar to OpenAI's, aisuite makes it easy to interact with the most popular LLMs and compare the results. It is a thin wrapper around python client libraries, and allows creators to seamlessly swap out and test responses from different LLM providers without changing their code. Today, the library is primarily focussed on chat completions. We will expand it cover more use cases in near future.

[CrewAI-Studio](https://github.com/strnad/CrewAI-Studio)
Welcome to CrewAI Studio! This application provides a user-friendly interface written in Streamlit for interacting with CrewAI, suitable even for those who don't want to write any code. Follow the steps below to install and run the application on Windows or Linux (probably also MacOS) using either Conda or a virtual environment.

[AutoGen](https://microsoft.github.io/autogen/stable/)
A programming framework for building conversational single and multi-agent applications. Built on Core. Requires Python 3.10+.

[OctoTools](https://github.com/octotools/octotools)
A training-free, user-friendly, and easily extensible open-source agentic framework designed to tackle complex reasoning across diverse domains. OctoTools introduces standardized tool cards to encapsulate tool functionality, a planner for both high-level and low-level planning, and an executor to carry out tool usage.

## MLOps
[ZenML](https://github.com/zenml-io)
An open-source MLOps + LLMOps framework that seamlessly integrates existing infrastructure and tools

[unify](https://unify.ai/)
Build custom interfaces for: logging, evals, guardrails, labelling, tracing, agents, human-in-the-loop, hyperparam sweeps, and anything else you can think of ✨

## Ops
[Icecream](https://github.com/gruns/icecream)
Never use print() to debug again

[Pytest](https://docs.pytest.org/en/stable/)
The pytest framework makes it easy to write small, readable tests, and can scale to support complex functional testing for applications and libraries.

[ruff](https://docs.astral.sh/ruff/)
An extremely fast Python linter and code formatter, written in Rust.

[PyRight](https://microsoft.github.io/pyright/#/)
Pyright is a full-featured, standards-compliant static type checker for Python. It is designed for high performance and can be used with large Python source bases.

[UV](https://github.com/astral-sh/uv)
An extremely fast Python package and project manager, written in Rust.

## LLM Memory / caching
[Letta](https://github.com/letta-ai/letta?tab=readme-ov-file)
Letta (formerly MemGPT) is a framework for creating LLM services with memory.

[mem0](https://github.com/mem0ai/mem0)
enhances AI assistants and agents with an intelligent memory layer, enabling personalized AI interactions. Mem0 remembers user preferences, adapts to individual needs, and continuously improves over time, making it ideal for customer support chatbots, AI assistants, and autonomous systems.

[memary](https://github.com/kingjulio8238/Memary)
Agents promote human-type reasoning and are a great advancement towards building AGI and understanding ourselves as humans. Memory is a key component of how humans approach tasks and should be weighted the same when building AI agents. memary emulates human memory to advance these agents.

[MemoRAG](https://github.com/qhjqhj00/MemoRAG)
MemoRAG is an innovative RAG framework built on top of a highly efficient, super-long memory model. Unlike standard RAG, which primarily handles queries with explicit information needs, MemoRAG leverages its memory model to achieve a global understanding of the entire database. By recalling query-specific clues from memory, MemoRAG enhances evidence retrieval, resulting in more accurate and contextually rich response generation.​

[LMCache](https://github.com/LMCache/LMCache)
LMCache is a LLM serving engine extension to reduce TTFT and increase throughput, especially under long-context scenarios. By storing the KV caches of reusable texts across various locations including (GPU, CPU DRAM, Local Disk), LMCache reuse the KV caches of any reused text (not necessarily prefix) in any serving engine instance. Thus, LMCache saves precious GPU cycles and reduces response delay for users.

[LangMem](https://langchain-ai.github.io/langmem/)
LangMem helps agents learn and adapt from their interactions over time.

## State
[Burr](https://burr.dagworks.io/)
Burr makes it easy to develop applications that make decisions (chatbots, agents, simulations, etc...) from simple python building blocks.
Burr works well for any application that uses LLMs, and can integrate with any of your favorite frameworks. Burr includes a UI that can track/monitor/trace your system in real time, along with pluggable persisters (e.g. for memory) to save & load application state.

## LLM inference
[Guidance](https://github.com/guidance-ai/guidance)
Guidance is an efficient programming paradigm for steering language models. With Guidance, you can control how output is structured and get high-quality output for your use case—while reducing latency and cost vs. conventional prompting or fine-tuning. It allows users to constrain generation (e.g. with regex and CFGs) as well as to interleave control (conditionals, loops, tool use) and generation seamlessly.

[llama.cpp](https://github.com/ggerganov/llama.cpp)
The main goal of llama.cpp is to enable LLM inference with minimal setup and state-of-the-art performance on a wide range of hardware - locally and in the cloud.

## RAG frameworks
[llmware](https://github.com/llmware-ai/llmware)
provides a unified framework for building LLM-based applications (e.g., RAG, Agents), using small, specialized models that can be deployed privately, integrated with enterprise knowledge sources safely and securely, and cost-effectively tuned and adapted for any business process.

## LLM risk assessment
[Guardrails](https://github.com/guardrails-ai/guardrails?tab=readme-ov-file)
Guardrails runs Input/Output Guards in your application that detect, quantify and mitigate the presence of specific types of risks. To look at the full suite of risks, check out [Guardrails Hub](https://hub.guardrailsai.com/).
Guardrails help you generate structured data from LLMs.

[NeMo](https://github.com/NVIDIA/NeMo-Guardrails)
NeMo Guardrails is an open-source [toolkit](https://docs.nvidia.com/nemo/guardrails/) for easily adding programmable guardrails to LLM-based conversational systems.

[LlamaGuard Vision](https://huggingface.co/meta-llama/Llama-Guard-3-11B-Vision)
Llama Guard 3 Vision is a Llama-3.2-11B pretrained model, fine-tuned for content safety classification. Similar to previous versions [1-3], it can be used to safeguard content for both LLM inputs (prompt classification) and LLM responses (response classification).

[LlamaGuard 3](https://huggingface.co/meta-llama/Llama-Guard-3-8B)
Llama Guard 3 is a Llama-3.1-8B pretrained model, fine-tuned for content safety classification. Similar to previous versions, it can be used to classify content in both LLM inputs (prompt classification) and in LLM responses (response classification). It acts as an LLM – it generates text in its output that indicates whether a given prompt or response is safe or unsafe, and if unsafe, it also lists the content categories violated.

## LLM Routers
[Aurelio](https://github.com/aurelio-labs/semantic-router)
Semantic Router is a superfast decision-making layer for your LLMs and agents. Rather than waiting for slow LLM generations to make tool-use decisions, we use the magic of semantic vector space to make those decisions — routing our requests using semantic meaning.

[aisuite](https://github.com/andrewyng/aisuite)
makes it easy for developers to use multiple LLM through a standardized interface. Using an interface similar to OpenAI's, aisuite makes it easy to interact with the most popular LLMs and compare the results. It is a thin wrapper around python client libraries, and allows creators to seamlessly swap out and test responses from different LLM providers without changing their code. 

## rerankers
[rerankers](https://github.com/answerdotai/rerankers)
A lightweight unified API for various reranking models. 

[Voyage Ai](https://www.voyageai.com/)
Supercharging Search and Retrieval for Unstructured Data

[Cohere](https://cohere.com/)
The all-in-one platform for private and secure AI

## Documentation
[mkdocs](https://github.com/squidfunk/mkdocs-material)
Write your documentation in Markdown and create a professional static site for your Open Source or commercial project in minutes – searchable, customizable, more than 60 languages, for all devices.

## MCP
[Model Context Protocol](https://github.com/modelcontextprotocol/servers/tree/main)
A collection of reference implementations and community-contributed servers for the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP). This repository showcases the versatility and extensibility of MCP, demonstrating how it can be used to give Large Language Models (LLMs) secure, controlled access to tools and data sources.

## Search Engines
[Brave Search API](https://brave.com/search/api/)
Power your search and AI apps with the fastest growing independent search engine since Bing. Access an index of billions of pages with a single call.

[Tavily](https://tavily.com/)
Empowering your AI applications with real-time, accurate search results tailored for LLMs and RAG.

## Distributed LLMs
[Exo](https://github.com/exo-explore/exo)
Run your own AI cluster at home with everyday devices

## Knowledge Graphs
[itext2KG](https://github.com/AuvaLab/itext2kg)
iText2KG is a Python package designed to incrementally construct consistent knowledge graphs with resolved entities and relations by leveraging large language models for entity and relation extraction from text documents. It features zero-shot capability, allowing for knowledge extraction across various domains without specific training. The package includes modules for document distillation, entity extraction, and relation extraction, ensuring resolved and unique entities and relationships. It continuously updates the KG with new documents and integrates them into Neo4j for visual representation.

## Chunking
[Chonkie](https://github.com/chonkie-ai/chonkie)
The no-nonsense RAG chunking library that’s lightweight, lightning-fast, and ready to CHONK your texts.

[Semchunk](https://github.com/umarbutler/semchunk)
A fast and lightweight pure Python library for splitting text into semantically meaningful chunks.

## Data Validation & Structure Output
[Pydantic](https://docs.pydantic.dev/latest/)
Data validation using Python type hints.

[Instructor](https://python.useinstructor.com/)
Structured outputs powered by llms. Designed for simplicity, transparency, and control.

[Outlines](https://github.com/dottxt-ai/outlines)
Outlines provides ways to control the generation of language models to make their output more predictable.

## Fine-Tunning
[Unsloth](https://unsloth.ai/)
Makes finetuning large language models like Llama-3, Mistral, Phi-3 and Gemma 2x faster, use 70% less memory, and with no degradation in accuracy!

[MLX](https://opensource.apple.com/projects/mlx/)
MLX is an array framework designed for efficient and flexible machine learning research on Apple silicon.

[Axoloti](https://axoloti.ai/)
MLX is an array framework designed for efficient and flexible machine learning research on Apple silicon.

[Covalent](https://www.covalent.xyz/)
Effortless AI Compute for Any Environment.

[Encord](https://encord.com/)
Manage, curate, and label multimodal data such as image, video, audio, document, text and DICOM files – all on one platform. Transform petabytes of unstructured data into high quality data for training, fine-tuning, and aligning AI models, fast.

[Transformer Labs](https://transformerlab.ai/)
100% Open Source Toolkit for Large Language Models: Train, Tune, Chat on your own Machine

## Inference
[Groq](https://groq.com/)
We provide fast AI inference in the cloud and in on-prem AI compute centers. We power the speed of iteration, fueling a new wave of innovation, productivity, and discovery. Groq was founded in 2016 to build technology to advance AI because we saw this moment coming. 

[Cerebras](https://cerebras.ai/)
Cerebras Inference Llama 3.3 70B runs at 2,200 tokens/s and Llama 3.1 405B at 969 tokens/s – over 70x faster than GPU clouds. Get instant responses to code-gen, summarization, and agentic tasks.

[Sambanova](https://sambanova.ai/)
We’ve built an enterprise-ready AI platform from the ground up – intentionally designed for the most valuable and complex AI workloads of today and tomorrow. Using our platform to build a technology backbone for the next decade of AI innovation, organizations get pre-trained foundation models that truly transform the way they gain value from AI and deep learning. And, with our flagship offering, SambaNova Suite, we help them realize value 22x faster.

[Together AI](https://www.together.ai/)
Train, fine-tune-and run inference on AI models blazing fast, at low cost, and at production scale.

[Predibase](https://predibase.com/)
Highest quality, fastest throughput small language models in your cloud

## Web Assistants
[Bolt](https://bolt.new/)
What do you want to build?

[Lovable](https://lovable.dev/)
Idea to app in seconds

[V0](https://v0.dev/)
What can I help you ship?

[Cerebras Code](https://cerebrascoder.com/)
Dream it. Code it. Instantly.

[HeyBoss](https://www.heyboss.xyz/)
World's 1st AI engineer for non-coders. Type your idea and AI will code your app, sites, and games in minutes, no coding required.

[Sitebrew](https://www.sitebrew.ai/create)
Generate a site and share it with the world, in seconds

## Model Assistants
[Deepseek](https://chat.deepseek.com/sign_in)
Deepseek chat

[Groq Labs](https://appgen.groqlabs.com/)
Build a micro-app

[Kimi](https://kimi.moonshot.cn/)

[Scira](https://scira.app/)
What do you want to explore?

[Gemini Coding Partner](https://gemini.google.com/gem/coding-partner)
Level up your coding skills. Get the help you need to build your projects and learn as you go.

[Gemini Coder](https://huggingface.co/spaces/osanseviero/gemini-coder)
Turn your idea into an app

[Google AI Studio](https://aistudio.google.com/prompts/new_chat)
Push Gemini to the limits of what Al can do using the Gemini API

[Val Town](https://www.val.town/townie/8011cb54-26e0-40b2-b514-64864f3d5dfb)
Create a val using Townie, the Val Town bot

[Grok](https://grok.com/)

[Convergance](https://convergence.ai/)
Your AI assistant for your daily tasks

## Code Assistants
[Replit](https://replit.com/)
Turn your ideas into apps with AI.

[Bolt.diy](https://stackblitz-labs.github.io/bolt.diy/)
This fork of Bolt.new (oTToDev) allows you to choose the LLM that you use for each prompt! Currently, you can use OpenAI, Anthropic, Ollama, OpenRouter, Gemini, LMStudio, Mistral, xAI, HuggingFace, DeepSeek, or Groq models - and it is easily extended to use any other model supported by the Vercel AI SDK! See the instructions below for running this locally and extending it to include more models.

[Codestral](https://mistral.ai/news/codestral/)
Empowering developers and democratising coding with Mistral AI.

[CoPilot](https://github.com/features/copilot)
The AI editor for everyone

[Continue](https://www.continue.dev/)
The leading open-source AI code assistant. You can connect any models and any context to create custom autocomplete and chat experiences inside the IDE

[LlamaCode](https://llamacoder.together.ai/)
Together AI code assinstant using Llama and Deekpseek

[Screenshot To Code](https://screenshottocode.com/)
Convert any screenshot or design to clean code (with support for most frameworks)

[Copy Coder](https://copycoder.ai/)
Built for the next generation of AI coders. Upload images of full applications, UI mockups, or custom designs and use our generated prompts to build your apps faster.

[Goose](https://goose.ai/)
GooseAI makes deploying NLP services easier and more accessible for creative technologists building products on top of large language models. In short, GooseAI is a fully managed inference service delivered via API. With feature parity to other well known APIs, GooseAI delivers a plug-and-play solution for serving open source language models at the industry's best economics by simply changing 2 lines in your code.

[Aider](https://aider.chat/)
Aider lets you pair program with LLMs, to edit code in your local git repository. Start a new project or work with an existing code base. Aider works best with Claude 

[Roo Code](https://github.com/RooVetGit/Roo-Code)
Roo Code is an AI-powered autonomous coding agent that lives in your editor.

[Cline](https://github.com/cline/cline)
Meet Cline, an AI assistant that can use your CLI aNd Editor.

[DeepClaude](https://deepclaude.com/)
Harness the power of DeepSeek R1's reasoning and Claude's creativity and code generation capabilities with a unified API and chat interface.

[Augment Code](https://www.augmentcode.com/)
The first AI coding assistant built for professional software engineers and large codebases.

[CodeLLM](https://codellm.abacus.ai/)
A revolutionary new AI Code Editor that helps you 10x your developer productivity! Bundled with AI super assistant ChatLLM

## AI Automation / No Code
[n8n](https://n8n.io/)
Secure, AI-native workflow automation. The world's most popular workflow automation platform for technical teams

[Dify](https://dify.ai/)
The Innovation Engine for GenAI Applications

[TriggerDev](https://trigger.dev/)
The open source background jobs platform. Write workflows in normal async code and we’ll handle the rest, from queues to elastic scaling. No timeouts, retries, observability, and zero infrastructure to manage.

[Kestra](https://kestra.io/)
Unified Orchestration Platform to Simplify Business-Critical Workflows and Govern them as Code and from the UI.

[NocoCode](https://www.nocobase.com/)
Extensibility-first open-source no-code platform.
Total control, infinite extensibility, empower your team to swiftly adapt to changes and significantly reduce costs. Skip years of development and millions in investment - just deploy NocoBase in minutes.

[Gumloop](https://www.gumloop.com/)
Gumloop is a platform for automating complex work using AI via a no-code drag and drop interface. We want any person or business to be able to automate their work without needing to be AI experts or engineers.

[Active Pieces](https://www.activepieces.com/)
Automation software that's AI-first, no-code & open-source

[MindStudio](https://www.mindstudio.ai/)
Create AI solutions–simple, fast, hassle-free

## IDE
[Trae](https://www.trae.ai/)
Trae is an adaptive AI IDE that transforms how you work, collaborating with you to run faster.

[Cursor](https://www.cursor.com/)
Built to make you extraordinarily productive, Cursor is the best way to code with AI.

[Project IDX](https://idx.dev/)
Project IDX is an AI-assisted workspace for full-stack, multiplatform app development in the cloud. With support for a broad range of frameworks, languages, and services, alongside integrations with your favorite Google products, IDX streamlines your development workflow so you can build and ship apps across platforms with speed, ease, and quality.

[Windsurf](https://codeium.com/windsurf)
The first agentic IDE, and then some. The Windsurf Editor is where the work of developers and AI truly flow together, allowing for a coding experience that feels like literal magic.

[Pydantic Run](https://pydantic.run/)
A pydantic playgroud

## UI
[Gradio Playground](https://www.gradio.app/playground)

[21st](https://21st.dev/)
Discover, share, and craft perfect UI components with top design engineers

[Penpot](https://github.com/penpot/penpot)
Penpot is the first open-source design tool for design and code collaboration. Designers can create stunning designs, interactive prototypes, design systems at scale, while developers enjoy ready-to-use code and make their workflow easy and fast. And all of this with no handoff drama.

[CustomTkinter](https://customtkinter.tomschimansky.com/)
A modern and customizable python UI-library based on Tkinter

[Shadcn](https://ui.shadcn.com/)
A set of beautifully-designed, accessible components and a code distribution platform. Works with your favorite frameworks. Open Source. Open Code.

[Storyook](https://storybook.js.org/)
Storybook is a frontend workshop for building UI components and pages in isolation. Thousands of teams use it for UI development, testing, and documentation. It's open source and free.

[ant.desgin](https://ant.design/)
Help designers/developers building beautiful products more flexible and working with happiness

[Mui](https://mui.com/)
MUI offers a comprehensive suite of free UI tools to help you ship new features faster. Start with Material UI, our fully-loaded component library, or bring your own design system to our production-ready components.

[Radix](https://www.radix-ui.com/)
An open source component library optimized for fast development, easy maintenance, and accessibility. Just import and go—no configuration required.

[Codia](https://codia.ai/)
Specializing in AI-driven design and development, we harness cutting-edge technology to innovate and transform ideas into reality.

## Recognition
[Gliner](https://github.com/urchade/GLiNER)
Generalist and Lightweight Model for Named Entity Recognition (Extract any entity types from texts)

## Multimodal libraries/models
[FastRTC](https://huggingface.co/blog/fastrtc)
FastRTC: The Real-Time Communication Library for Python

[SmolVLM2](https://huggingface.co/blog/smolvlm2)
SmolVLM2 represents a fundamental shift in how we think about video understanding - moving from massive models that require substantial computing resources to efficient models that can run anywhere. Our goal is simple: make video understanding accessible across all devices and use cases, from phones to servers.

[SigLIP2](https://huggingface.co/docs/transformers/main/en/model_doc/siglip2)
Multilingual Vision-Language Encoders with Improved Semantic Understanding, Localization, and Dense Features

[GOT-OCR](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)
AI models for OCR

## Agents
[TEN-Agent](https://github.com/TEN-framework/TEN-Agent)
A conversational AI powered by the TEN, integrating Gemini 2.0 Live, OpenAI Realtime, RTC, and more. It delivers real-time capabilities to see, hear, and speak, while being fully compatible with popular workflow platforms like Dify and Coze.

## Edge AI
[SmallThinker](https://huggingface.co/PowerInfer/SmallThinker-3B-Preview)

## UI Testing
[Browser-use](https://browser-use.com/)
We make websites accessible for AI agents by extracting all interactive elements, so agents can focus on what makes their beer taste better.

## Image generation
[Recraft](https://www.recraft.ai/)
Vector Premium image generation and editing tool

[Diagramming AI](https://diagrammingai.com/)
Instantly Shape Your Ideas into Clear, Powerful Diagrams
