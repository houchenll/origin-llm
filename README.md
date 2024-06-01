# llm-origin
本文将 LLM 知识分为以下七个部分，并整理了相关资源：
* **LLM Overview**：汇总有关 LLM 的综述和系统课程。
* **LLM Fundamentals**：学习 LLM 之前需要掌握的基础知识，包括数学、Python、深度学习框架、机器学习、深度学习和NLP等。
* **Create LLM**：专注于创建和优化 LLM 所需的技术。
* **Use LLM**：专注于开发基于 LLM 的应用并进行部署。
* **LLM Applications**：基于 LLM 构建的应用。
* **面试准备**：整理与面试相关的八股文和面经。
* **其他**：如语音、视频等。


## LLM Overview
汇总LLM相关的综述、系统课程。

### Survey

### Course
* [llm-course](https://github.com/mlabonne/llm-course)(32.1k) by mlabonne: Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks. [mlabonne.github.io/blog](https://mlabonne.github.io/blog/).
* [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)(17.2k): Implementing a ChatGPT-like LLM in PyTorch from scratch, step by step.
* [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)(15.2k): a curated list of Large Language Model.
* [llm-cookbook](https://github.com/datawhalechina/llm-cookbook)(9.9k): 面向开发者的 LLM 入门教程，吴恩达大模型系列课程中文版.
* [LLMSurvey](https://github.com/RUCAIBox/LLMSurvey)(9.2k): The official GitHub page for the survey paper "A Survey of Large Language Models".
* [LLMsPracticalGuide](https://github.com/Mooler0410/LLMsPracticalGuide)(8.8k): A curated list of practical guide resources of LLMs (LLMs Tree, Examples, Papers)
* [llm-action](https://github.com/liguodongiot/llm-action)(6.9k): 本项目旨在分享大模型相关技术原理以及实战经验。


## LLM Fundamentals

### 数学

### Python

### 深度学习框架

### 机器学习

### 深度学习

### NLP


## Create LLM

### Transformer
Attention Is All You Need(2017), [paper](https://arxiv.org/pdf/1706.03762), [arxiv](https://arxiv.org/abs/1706.03762).

**Understand:**
* [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) by Jay Alammar: A visual and intuitive explanation of the Transformer model.
* [Visual intro to Transformers](https://www.youtube.com/watch?v=wjZofJX0v4M&t=187s) by 3Blue1Brown: Simple easy to understand visual intro to Transformers.
* [Attention? Attention!](https://lilianweng.github.io/posts/2018-06-24-attention/) by Lilian Weng: Introduce the need for attention in a more formal way.
* [annotated-transformer](https://github.com/harvardnlp/annotated-transformer)(5.2k) by harvardnlp: An annotated implementation of the Transformer paper. [The Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/) blog.
* [How-to-use-Transformers](https://github.com/jsksxs360/How-to-use-Transformers)(732): Transformers 库快速入门教程。[transformers快速入门](https://transformers.run/) blog。

**Use:**
* [huggingface/transformers 127k](https://github.com/huggingface/transformers), [huggingface.co/transformers](https://huggingface.co/docs/transformers/index), Transformers: State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX.


### LLM architecture
对于Transformer架构，需要对其输入（tokens）和输出（logits）有一个良好的理解。注意力机制是另一个需要掌握的关键组件，因为其改进版本会在后续介绍。

* **总览**：理解编码器-解码器Transformer架构，特别是decoder-only GPT架构，它在每个现代大语言模型中使用。
* **分词(Tokenization)**：了解如何将原始文本数据转换为模型能够理解的格式，这涉及将文本拆分为tokens（通常是单词或子词）。
* **注意力机制**：掌握注意力机制背后的理论，包括自注意力和缩放点积注意力，这些机制使模型在生成输出时能够关注输入的不同部分。
* **文本生成**：了解模型生成输出序列的不同方式。常见的策略包括贪婪解码、束搜索(beam search)、top-k采样和核采样(nucleus sampling)。

**References:**
* [The Illustrated GPT-2](https://jalammar.github.io/illustrated-gpt2/) by Jay Alammar: focused on the GPT architecture, which is very similar to Llama's.
* [LLM Visualization](https://bbycroft.net/llm) by Brendan Bycroft: Incredible 3D visualization of what happens inside of an LLM.
* [nanoGPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) by Andrej Karpathy: A 2h-long YouTube video to reimplement GPT from scratch (for programmers).
* [Decoding Strategies in LLMs](https://mlabonne.github.io/blog/posts/2023-06-07-Decoding_strategies.html): Provide code and a visual introduction to the different decoding strategies to generate text.


### 数据集(Dataset)
* [firecrawl](https://github.com/mendableai/firecrawl)(5.3k) by mendableai: Turn entire websites into LLM-ready markdown or structured data. Scrape, crawl and extract with a single API.
* [EasySpider](https://github.com/NaiboWang/EasySpider)(26.7k) by NaiboWang: A visual no-code/code-free web crawler/spider易采集：一个可视化浏览器自动化测试/数据采集/爬虫软件，可以无代码图形化的设计和执行爬虫任务。别名：ServiceWrapper面向Web应用的智能化服务封装系统。
* [LLMDataHub](https://github.com/Zjh-819/LLMDataHub)(2.1k) by Zjh-819: A quick guide (especially) for trending instruction finetuning datasets.


### 预训练
* [llm.c](https://github.com/karpathy/llm.c)(20k) by karpathy: LLM training in simple, raw C/CUDA. 用1000行C代码在笔记本电脑完成GPT2的训练，有助于初学者了解大模型底层的原理和知识点。


### LLM汇总
* [Awesome-Chinese-LLM](https://github.com/HqWu-HITCS/Awesome-Chinese-LLM)(12k) by HqWu-HITCS: 整理开源的中文大语言模型，以规模较小、可私有化部署、训练成本较低的模型为主，包括底座模型，垂直领域微调及应用，数据集与教程等。
* [open-llms](https://github.com/eugeneyan/open-llms)(10.4k) by eugeneyan: A list of open LLMs available for commercial use.

**Llama:**
* [llama.cpp github/59.3k](https://github.com/ggerganov/llama.cpp)(59.3k) by ggerganov: LLM inference in C/C++.
* [llama3-from-scratch](https://github.com/naklecha/llama3-from-scratch)(9.5k) by naklecha: llama3 implementation one matrix multiplication at a time.

**MultiModal:**
* [MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V)(4.4k) by OpenBMB: MiniCPM-Llama3-V 2.5: A GPT-4V Level Multimodal LLM on Your Phone.
* [InternVL](https://github.com/OpenGVLab/InternVL)(3k) by OpenGVLab: [CVPR 2024 Oral] InternVL Family: A Pioneering Open-Source Alternative to GPT-4V. 接近GPT-4V表现的可商用开源多模态对话模型.
* [CogVLM2](https://github.com/THUDM/CogVLM2)(1k) by THUDM: GPT4V-level open-source multi-modal model based on Llama3-8B.

### 微调(Finetune)
* [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory)(23.4k) by hiyouga: Unify Efficient Fine-Tuning of 100+ LLMs.

### peft


## Use LLM

### prompt
* [fabric github/13.3k](https://github.com/danielmiessler/fabric) - About
fabric is an open-source framework for augmenting humans using AI. It provides a modular framework for solving specific problems using a crowdsourced set of AI prompts that can be used anywhere. 可以选择并生成上百个场景的提示词。

### RAG
* [llama_index github/32.2k](https://github.com/run-llama/llama_index) - LlamaIndex is a data framework for your LLM applications. 连接私有数据库和LLM。
* [Verba github/4.4k](https://github.com/weaviate/Verba) - Retrieval Augmented Generation (RAG) chatbot powered by Weaviate.
* [WrenAI github/834](https://github.com/Canner/WrenAI) - WrenAI makes your database RAG-ready. Implement Text-to-SQL more accurately and securely. [getwren.ai](https://www.getwren.ai/).
* [llmware 4k](https://github.com/llmware-ai/llmware) - Unified framework for building enterprise RAG pipelines with small, specialized models.

### agent
* [dify github/31.8k](https://github.com/langgenius/dify) - Dify is an open-source LLM app development platform. Dify's intuitive interface combines AI workflow, RAG pipeline, agent capabilities, model management, observability features and more, letting you quickly go from prototype to production. [dify.ai](https://dify.ai/).
* [FinRobot github/673](https://github.com/AI4Finance-Foundation/FinRobot) - FinRobot: An Open-Source AI Agent Platform for Financial Applications using LLMs. [ai4finance.org](https://ai4finance.org/).
* [CopilotKit github/6983](https://github.com/CopilotKit/CopilotKit) - A framework for building custom AI Copilots 🤖 in-app AI chatbots, in-app AI Agents, & AI-powered Textareas. [copilotkit.ai](https://www.copilotkit.ai/).
* [bisheng github/7.4k](https://github.com/dataelement/bisheng) - Bisheng is an open LLM devops platform for next generation AI applications. [毕昇](https://bisheng.dataelem.com/).
* [SWE-agent github/11.3k](https://github.com/princeton-nlp/SWE-agent) - SWE-agent takes a GitHub issue and tries to automatically fix it, using GPT-4, or your LM of choice. It solves 12.47% of bugs in the SWE-bench evaluation set and takes just 1.5 minutes to run.
* [phidata github/9.4k](https://github.com/phidatahq/phidata) - Build AI Assistants with memory, knowledge and tools.
* [gpt-researcher github/12k](https://github.com/assafelovic/gpt-researcher) - GPT based autonomous agent that does online comprehensive research on any given topic.
* [MemGPT github/10.4k](https://github.com/cpacker/MemGPT) - Create LLM agents with long-term memory and custom tools.
* [maestro github/2k](https://github.com/Doriandarko/maestro) - A framework for Claude Opus to intelligently orchestrate subagents.
* [anything-llm 15.3k](https://github.com/Mintplex-Labs/anything-llm) - The all-in-one Desktop & Docker AI application with full RAG and AI Agent capabilities. [useanything.com](https://useanything.com/).
* [embedchain 8.7k](https://github.com/embedchain/embedchain) - Personalizing LLM Responses.

#### workflow
* [Flowise 25.9k](https://github.com/FlowiseAI/Flowise), [FlowiseAI](https://flowiseai.com/), Drag & drop UI to build your customized LLM flow.

### Inference optimization
* [ipex-llm 6.1k](https://github.com/intel-analytics/ipex-llm) - Accelerate local LLM inference and finetuning (LLaMA, Mistral, ChatGLM, Qwen, Baichuan, Mixtral, Gemma, Phi, etc.) on Intel CPU and GPU (e.g., local PC with iGPU, discrete GPU such as Arc, Flex and Max); seamlessly integrate with llama.cpp, Ollama, HuggingFace, LangChain, LlamaIndex, DeepSpeed, vLLM, FastChat, Axolotl, etc.
* [web-llm 10.9k](https://github.com/mlc-ai/web-llm) - High-performance In-browser LLM Inference Engine. [webllm.mlc.ai](https://webllm.mlc.ai/).

### Deploying LLMs
* [mergekit 3.8k](https://github.com/arcee-ai/mergekit), Tools for merging pretrained large language models.
* [llm github/3.2k](https://github.com/simonw/llm) - Access large language models from the command-line. [llm.datasette.io](https://llm.datasette.io/en/stable/).
* [OpenLLM 9k](https://github.com/bentoml/OpenLLM), [BentoML](https://bentoml.com/), Run any open-source LLMs, such as Llama 2, Mistral, as OpenAI compatible API endpoint in the cloud.
* [mlc-llm 17.4k](https://github.com/mlc-ai/mlc-llm) - Universal LLM Deployment Engine with ML Compilation. [llm.mlc.ai](https://llm.mlc.ai/).
* [self-llm 4.8k](https://github.com/datawhalechina/self-llm), 《开源大模型食用指南》基于Linux环境快速部署开源大模型，更适合中国宝宝的部署教程

### Securing LLMs


## Applications
* [llama-fs github/2.9k](https://github.com/iyaja/llama-fs) - A self-organizing file system with llama 3

### chat
* [jan github/19.4k](https://github.com/janhq/jan) - Jan is an open source alternative to ChatGPT that runs 100% offline on your computer. Multiple engine support (llama.cpp, TensorRT-LLM). [jan.ai](https://jan.ai/).
* [lencx/ChatGPT github/50.9k](https://github.com/lencx/ChatGPT) - ChatGPT Desktop Application (Mac, Windows and Linux). [nofwl.com](https://nofwl.com/)
* [open-webui github/24.8k](https://github.com/open-webui/open-webui) - User-friendly WebUI for LLMs (Formerly Ollama WebUI)
* [gpt4all 65.5k](https://github.com/nomic-ai/gpt4all) - gpt4all: run open-source LLMs anywhere. [gpt4all.io](https://gpt4all.io/index.html).
* [SillyTavern 6.4k](https://github.com/SillyTavern/SillyTavern), [SillyTavern](https://sillytavern.app/), LLM Frontend for Power Users.
* [llm-answer-engine](https://github.com/developersdigest/llm-answer-engine), [developersdigest.tech](https://www.developersdigest.tech/), Build a Perplexity-Inspired Answer Engine Using Next.js, Groq, Llama-3, Langchain, OpenAI, Upstash, Brave & Serper.

### search
* [khoj github/10.7k](https://github.com/khoj-ai/khoj) - Your AI second brain. Get answers to your questions, whether they be online or in your own notes. Use online AI models (e.g gpt4) or private, local LLMs (e.g llama3). Self-host locally or use our cloud instance. Access from Obsidian, Emacs, Desktop app, Web or Whatsapp. [khoj.dev](https://khoj.dev/).
* [Perplexica github/6.8k](https://github.com/ItzCrazyKns/Perplexica) - Perplexica is an AI-powered search engine. It is an Open source alternative to Perplexity AI.
* [farfalle github/1.6k](https://github.com/rashadphz/farfalle) - AI search engine - self-host with local or cloud LLMs. [www.farfalle.dev](https://www.farfalle.dev/).

### agent
* [ragapp github/2.1k](https://github.com/ragapp/ragapp) - The easiest way to use Agentic RAG in any enterprise.
* [GPTS](https://openai.com/index/introducing-gpts/) - You can now create custom versions of ChatGPT that combine instructions, extra knowledge, and any combination of skills.

### Virtual Human Generation
* [V-Express github/611](https://github.com/tencent-ailab/V-Express) - V-Express aims to generate a talking head video under the control of a reference image, an audio, and a sequence of V-Kps images. 音频控制肖像生成视频。
* [MusePose github/854](https://github.com/TMElyralab/MusePose) - MusePose: a Pose-Driven Image-to-Video Framework for Virtual Human Generation. 姿势驱动图片生成跳舞视频。

### code
* [openui github/15.6k](https://github.com/wandb/openui) - OpenUI let's you describe UI using your imagination, then see it rendered live.


## 面试


## Others

### tts

**ChatTTS**  
* [ChatTTS github/10.5k](https://github.com/2noise/ChatTTS) - ChatTTS is a generative speech model for daily dialogue

**GPT-SoVITS**  
* [GPT-SoVITS github/25k](https://github.com/RVC-Boss/GPT-SoVITS) - 1 min voice data can also be used to train a good TTS model! (few shot voice cloning)

**OpenVoice**
* [OpenVoice github/26.2k](https://github.com/myshell-ai/OpenVoice) - Instant voice cloning by MyShell.
* [open-voice](https://research.myshell.ai/open-voice)

### CV
* [yolov10 github/6.3k](https://github.com/THU-MIG/yolov10) - YOLOv10: Real-Time End-to-End Object Detection
