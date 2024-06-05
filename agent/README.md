
## 什么是 agent

AI agent是对人类解决复杂问题时思维方式以及工具使用行为的完整模仿，让AI代理人类去完成思考和行动的过程，是极有可能实现AGI的方法。

AI agent就是用来描述任何利用人工智能技术，根据当前环境下的状态，选择策略，执行动作。

agent最重要的就是LLM，人类大脑控制我们的身体干各种事情，agent就是用LLM来控制各种工具的API，帮我们完成任务。

现在，借助LLM，以及视觉、语音等模型，离AGI就不远了。

主要组成部分有：记忆模块（长时&短时），工具模块（网络接口、数值计算、代码运行、文件读取、数据库访问），LLM，计划（思考推理、反思和自我批评、目标拆解），动作。

基本组成：大模型的能力调用，知识库的构建和检索，流程的编排，工具的使用

搭建agent就像组装一个人体，装上大脑（LLM），配上工具，将大脑和各个工具整合在一起。

结合了AI和机器人流程自动化(RPA)，能够自动完成人类的工作流程

通过大模型驱动的智能体平台，可以把更多的人、设备、物品连接起来，推动万物互联进阶到万物智联，进入人机交互的智能新时代，迎来人工智能的第二次涌现。

### agent 能做什么
知识密集型的决策任务（如服务厂老板考虑生产什么衣服），通过一次简单的问答，大语言模型只会给出看似有模有样，实则听君一席话如听一席话的内容，几乎不可能得到有价值的结果。
人类思考这类问题时，会考虑影响衣服销售的可能因素，并将大的目标拆分成小的目标，可能采取具体的动作去逐个实现这些小目标。并且还会根据动作产生的结果对小目标进行一些调整，然后继续实施，不断地重复这个过程。直到实现或收敛到目标问题的答案。

只需要一条指令，就能通过AGENT自动控制各种AI的工具，来生成文字、图像、视频、音乐、配音等各种不同形式的内容，并且做到合成以及自动发布小红书。

自动化抓取网页内容，自动动抓取学术文献，自动化抓取本地文件，
自动发送到邮箱、飞书、微信等平台。

自媒体运营与创意性内容生成
数据、文档查阅总结，本地知识库搭建
客服代理与数字人
个性化教案和培训
互联网产品与游戏开发

文本、图像、语音、视频、代码等多模态、跨平台的自动化流程。

数字分身：设计师、咨询顾问、销售代表，每个分身是一个agent
数字员工：
多智能体系统：由多个协作或竞争的自治智能体组成，旨在通过集体行为解决复杂问题。每个智能体都具有一定程度的主动性，并能够感知环境并作出决策，并与其他智能体交互，共同实现一个终极设定目标。
具身智能：机器人

### 有哪些优势和劣势

缺点：
作为基础的LLM推理能力不足，需要运行多次才能得到稍有洞察力的结果。

## 怎么使用agent

## 框架

| Name | github | Doc | Description | Other |
|------|--------|-----|-------------|-------|
| [AutoGPT](https://news.agpt.co/) | [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)(163k) | [Docs](https://docs.agpt.co/) | AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so that you can focus on what matters. Explore the new frontier of autonomous AI and try the fastest growing open source project in the history of GitHub for yourself. ||
| [LangChain](https://www.langchain.com/) | [langchain](https://github.com/langchain-ai/langchain)(86.5k) | [Docs](https://python.langchain.com/v0.2/docs/introduction/) | Build context-aware reasoning applications. | [youtube LangChain by Greg Kamradt](https://www.youtube.com/playlist?list=PLqZXAkvF1bPNQER9mLmDbntNfSpzdDIU5) |
| [MetaGPT](https://www.deepwisdom.ai/) | [MetaGPT](https://github.com/geekan/MetaGPT)(40.6k) | [Docs](https://docs.deepwisdom.ai/main/en/) | The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming. 使 GPTs 组成软件公司，协作处理更复杂的任务。 | [paper](https://arxiv.org/pdf/2308.00352), [arxiv](https://arxiv.org/abs/2308.00352) |
| [dify](https://dify.ai/) | [dify](https://github.com/langgenius/dify)(32.6k) | [Docs](https://docs.dify.ai/) | Dify is an open-source LLM app development platform. Dify's intuitive interface combines AI workflow, RAG pipeline, agent capabilities, model management, observability features and more, letting you quickly go from prototype to production. 部署可嵌入网站，或者通过API调用 | [youtube channel](https://www.youtube.com/@dify_ai) |
| [LlamaIndex](https://www.llamaindex.ai/) | [llama_index](https://github.com/run-llama/llama_index)(32.4k) | [Docs](https://docs.llamaindex.ai/en/stable/) | LlamaIndex is a data framework for your LLM applications. | [youtube channel](https://www.youtube.com/@LlamaIndex) |
| [AutoGen](https://microsoft.github.io/autogen/) | [autogen](https://github.com/microsoft/autogen)(26.8k) | [docs/Getting-Started](https://microsoft.github.io/autogen/docs/Getting-Started) | A programming framework for agentic AI. 可以本地化私有部署，可以和更多的系统环境进行交互，来完成多样化的更复杂的任务，有可视化的UI界面。 ||
| [ChatDev](https://chatdev.ai/) | [ChatDev](https://github.com/OpenBMB/ChatDev)(23.9k) || Create Customized Software using Natural Language Idea (through LLM-powered Multi-Agent Collaboration). | [arxiv](https://arxiv.org/abs/2307.07924) |
| [FastGPT](https://fastgpt.in/) | [FastGPT](https://github.com/labring/FastGPT)(14.2k) || FastGPT is a knowledge-based platform built on the LLMs, offers a comprehensive suite of out-of-the-box capabilities such as data processing, RAG retrieval, and visual AI workflow orchestration, letting you easily develop and deploy complex question-answering systems without the need for extensive setup or configuration. 特定领域的人工智能助手，支持RAG ||
| [XAgent](https://www.xagent.com/) | [XAgent](https://github.com/OpenBMB/XAgent)(7.7k) || An Autonomous LLM Agent for Complex Task Solving. 自主智能体应用框架 ||
| [AgentVerse](https://agentverse.ai/) | [AgentVerse](https://github.com/OpenBMB/AgentVerse)(3.8k) || AgentVerse 🪐 is designed to facilitate the deployment of multiple LLM-based agents in various applications, which primarily provides two frameworks: task-solving and simulation. | [arxiv](https://arxiv.org/abs/2308.10848) |


## 有哪些典型应用

| Name | Description | Other |
|------|-------------|-------|
| [GPTs](https://chatgpt.com/gpts) || [Introduction](https://openai.com/index/introducing-gpts/) |
| [coze](https://www.coze.com/home) |||
| [扣子](https://www.coze.cn/home) |||


## 相关资源

## assistant API
Open AI assistant API 是通往agent的关键一步。

主要构成：Assistant, Retrieval(本地知识检索), Code Interpreter, Function call, Image Generation, Web Browsing(Bing API).

主要概念有：Assistant, Thread, Run, Message. Thread是一次会话，其中包含多个Message。
步骤：
1. 创建Assistant，关键参数有：name, instructions, model, tools, field_ids。
2. 创建Thread
3. 创建Message，关键参数：thread_id, role, content, field_ids
4. 创建Run，并执行Run，最后取出Message

## 相关公司
实在智能：看见屏幕、操作软件
面壁智能：agent


## 应聘企业要求

职位数量：300

### 工作内容/职位描述
* 参与大模型在RAG/Agent方面的能力构建，包括数据体系、算法调优、评估迭代
* 基于大模型探索下一代聊天机器人能力边界。包括但不限于：记忆、联想、反思、环境感知、使用工具、子目标拆解、主动探索等。
* 推动相关能力工具化建设，支持公司各业务线应用落地。
* 能够深入理解业务，进行重点难点技术攻关工作，将技术实现与业务场景联系起来，快速解决业务需求问题。
* 不断探索技术新领域，推动技术能力的沉淀和技术氛围的建设。
* 跟踪业界前沿技术的发展，探索深度学习等前沿技术在企业智能场景下的应用前景。
* 负责公司销售智能外呼与智能CRM产品中用户意图理解与对话策略算法，通过对话系统与对话大模型优化提升产品的用户体验和业务效果；
* 负责公司商家经营大模型RAG与Agent技术建设，提升大模型在人机交互的对话质量、API指令对齐以及电商经营任务规划与分析上能力
* 负责商家智能经营AIGC算法能力建设，包括商品发布、营销与优化能力，买家理解与营销能力等
* 负责AI Agent的核心逻辑实现，算法及模型的设计、实验、调优等研发工作；
* 负责为特定业务设计和实现高质量的基础特征（实体、类别、画像标签等）； 
* 负责自然语言处理基础能力建设，针对特定场景搭建自然语言处理基础组件； 
* 在客服场景中构建Agent，实现一定程度的RPA功能，提升服务效率。

### 要求
* 熟悉大模型的原理，拥有精调、预训练、数据处理等方面的经验优先；
* 熟悉自然语言处理常见算法与模型，具备深度学习技术在NLP领域的应用实践；
* 熟悉自然语言处理的实体提取、意图识别、事件摘要、语义分析、新词发现、图文数据分类、对话系统等相关任务，并在特定领域有深入的实践经验；
* 熟悉常用的机器学习算法（LR/GBDT/SVM等），有相关的实现项目经验；熟悉深度学习的原理和实现，了解DNN、LSTM、CNN等基本网络模型，熟练掌握Tensorflow/pytorch/Keras等至少一种深度学框架； 
* 具备良好的工程实现能力，熟悉Python、Java等常用编程语言中至少一种；
* 有文本数据处理、特征工程以及画像体系建设等方面经验。 
* 参与过推荐系统、问答、搜索等实际项目的开发，有丰富的架构设计、特征工程、画像体系建设等方面经验，熟练掌握基本的召回和排序算法，并对领域前沿算法有研究； 
* 具备探索精神、较强的分析问题和解决问题的能力，能够独立开展工作并落地。
* 具备强烈的进取心、求知欲及团队合作精神，热衷于追求技术创新。
* 拥有深度学习领域论文发表者优先。
* 熟悉大模型开发框架langchain或llamaIndex优先；


### 业务方向

