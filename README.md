# AI 开源项目全景导航

## 目录

- [热门 AI 创作工具（视频、音频与剪辑）](#热门-ai-创作工具视频音频与剪辑)
- [基础模型与推理](#基础模型与推理)
- [大语言模型应用与 Agent](#大语言模型应用与-agent)
- [RAG、检索与向量数据库](#rag检索与向量数据库)
- [训练、微调与对齐](#训练微调与对齐)
- [评测、可观测性与安全](#评测可观测性与安全)
- [机器学习框架与 MLOps](#机器学习框架与-mlops)
- [计算机视觉](#计算机视觉)
- [生成式图像与视频](#生成式图像与视频)
- [语音、音频与音乐](#语音音频与音乐)
- [自然语言处理](#自然语言处理)
- [多模态与文档智能](#多模态与文档智能)
- [机器人、自动驾驶与具身智能](#机器人自动驾驶与具身智能)
- [科学计算与生物 AI](#科学计算与生物-ai)
- [开发者工具与本地 AI](#开发者工具与本地-ai)
- [数据集、社区与学习资源](#数据集社区与学习资源)

> 面向开发者、研究者和产品团队的 AI 开源项目精选索引。按能力、模型、工程与应用场景分类，优先收录活跃、可复用、社区影响力较大的 GitHub 项目。

> **说明**：GitHub 上的 AI 项目持续增长，无法以静态文档“穷尽所有”。本仓库提供一个结构化、可持续更新的高质量入口；欢迎通过 Issue / PR 补充遗漏项目或修正状态。

## 热门 AI 创作工具（视频、音频与剪辑）

面向视频生成、影视剪辑、配音、音频转换与制作流程自动化的开源工具。

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | Agent 驱动的视频制作系统，提供制作管线、工具与技能库。 | 44.0k |
| [OpenCut](https://github.com/OpenCut-app/OpenCut) | 开源 CapCut 替代品，适合影视短片剪辑。 | 79.8k |
| [video-use](https://github.com/browser-use/video-use) | 让编码 Agent 自动完成视频编辑任务。 | 18.1k |
| [AICON](https://github.com/869413421/ai-moive-studio) | 自然语言驱动的无限画布工作流，覆盖剧本、分镜、素材生成与视频合成。 | 1.5k |
| [Rongguang](https://github.com/Stonewuu/ai-fusion-video) | 基于 Agent 的短剧、漫剧与视频全流程 AI 创作平台。 | 1.5k |
| [Claude Code Video Toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | 面向 Claude Code 的 AI 原生视频制作工具包。 | 2.1k |
| [Hyperframes](https://github.com/heygen-com/hyperframes) | 面向 Agent 的 HTML 视频渲染工具，可将网页内容渲染为视频。 | 43.6k |
| [YouDub-webui](https://github.com/liuzhao1225/YouDub-webui) | 面向 YouTube、Bilibili 的视频本地化、字幕翻译与 AI 配音工具。 | 5.4k |
| [VideoCaptioner](https://github.com/WEIFENG2333/VideoCaptioner) | 基于 LLM 的视频字幕生成、断句校正与字幕翻译工具。 | 16.0k |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 节点式生成视频、图像与创意工作流。 | 122.8k |
| [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) | 静态人像驱动与口播视频生成。 | 18.8k |
| [voicebox](https://github.com/jamiepine/voicebox) | 开源 AI 语音工作室：克隆、口述与生成语音。 | 47.4k |
| [Whisper](https://github.com/openai/whisper) | 多语种语音识别、字幕与音频转文字。 | 106.1k |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | 更高效的 Whisper 推理，适合转写流水线。 | 24.6k |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | 文本转语音训练、克隆与生成工具。 | 45.8k |
| [VoxCPM](https://github.com/OpenBMB/VoxCPM) | 多语种语音生成、创意音色设计与高保真声音克隆。 | 34.5k |
| [MockingBird](https://github.com/babysor/MockingBird) | 数秒完成声音克隆并实时生成语音。 | 36.9k |
| [Duix-Avatar](https://github.com/duixcom/Duix-Avatar) | 本地数字人视频生成与形象克隆工具包。 | 14.2k |
| [Toonflow](https://github.com/HBAI-Ltd/Toonflow-app) | 将小说或剧本转为动画短剧，集成编剧、分镜与视频生成。 | 13.1k |
| [palmier-pro](https://github.com/palmier-io/palmier-pro) | 专为 AI 创作设计的 macOS 视频编辑器。 | 12.8k |
| [voice-pro](https://github.com/abus-aikorea/voice-pro) | 集成 TTS、声音克隆、转写、分离与翻译的创作者 WebUI。 | 11.4k |
| [KrillinAI](https://github.com/krillinai/KrillinAI) | 视频下载、转写、翻译、配音与封装的一体化工具。 | 10.6k |
| [AutoClip](https://github.com/zhouxiaoka/autoclip) | AI 高光提取与短视频自动剪辑。 | 6.2k |
| [short-video-factory](https://github.com/YILS-LIN/short-video-factory) | 批量生成营销及内容短视频的跨平台工具。 | 5.0k |
| [SmartSub](https://github.com/buxuku/SmartSub) | 本地字幕生成、翻译、AI 配音与声音克隆。 | 4.4k |
| [auto-subs](https://github.com/tmoroney/auto-subs) | 面向 DaVinci Resolve、Premiere 与 After Effects 的本地字幕生成。 | 3.9k |
| [VideoLingo](https://github.com/Huanshere/VideoLingo) | 一键完成字幕切分、翻译、对齐与配音的开源视频本地化工具。 | 18.3k |
| [OmniVoice-Studio](https://github.com/debpalash/OmniVoice-Studio) | 本地声音克隆、视频配音、口述与有声书制作工具。 | 9.5k |
| [html-video](https://github.com/nexu-io/html-video) | 面向编程 Agent 的本地 HTML/CSS/数据到 MP4 视频生成工具。 | 4.3k |
| [MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano) | 可在 CPU 实时运行的轻量多语种语音生成模型。 | 4.0k |
| [video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 面向 Claude Code 与 Codex 的 AI 电影感产品视频制作技能库。 | 3.5k |
| [qwen-audio-agent](https://github.com/QwenAudio/qwen-audio-agent) | 支持 AI Agent 实时语音交互的运行时。 | 1.9k |
| [VoiceStudio](https://github.com/debpalash/VoiceStudio) | 全本地语音克隆、音色设计、视频配音、转写与有声书制作工具。 | 10.1k |
| [FluidVoice](https://github.com/altic-dev/FluidVoice) | 支持端侧语音转写与文本增强的 macOS 听写应用。 | 10.7k |
| [AI-Video-Transcriber](https://github.com/wendy7756/AI-Video-Transcriber) | 跨平台转写和总结视频、播客的开源工具。 | 3.2k |
| [Scriberr](https://github.com/rishikanthc/Scriberr) | 自托管的 AI 音频转写工具。 | 3.1k |

## 基础模型与推理

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [meta-llama/llama](https://github.com/meta-llama/llama) | Llama 系列模型与推理代码。 | 59.5k |
| [QwenLM/Qwen](https://github.com/QwenLM/Qwen) | 通义千问模型、微调与部署资源。 | 21.5k |
| [mistralai/mistral-inference](https://github.com/mistralai/mistral-inference) | Mistral 模型参考推理实现。 | 10.8k |
| [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) | DeepSeek-V3 模型与技术资料。 | 104.1k |
| [deepseek-ai/DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) | 推理模型与蒸馏模型资源。 | 92.0k |
| [google-deepmind/gemma](https://github.com/google-deepmind/gemma) | Gemma 模型的官方开源实现。 | 5.6k |
| [google-research/bert](https://github.com/google-research/bert) | BERT 原始实现与预训练模型。 | 40.1k |
| [facebookresearch/llama](https://github.com/facebookresearch/llama) | LLaMA 研究代码。 | 59.5k |
| [EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox) | 大规模语言模型训练与推理。 | 7.4k |
| [bigscience-workshop/Megatron-DeepSpeed](https://github.com/bigscience-workshop/Megatron-DeepSpeed) | BLOOM 训练技术栈。 | 1.4k |
| [01-ai/Yi](https://github.com/01-ai/Yi) | Yi 系列模型资源。 | 7.8k |
| [THUDM/GLM-4](https://github.com/THUDM/GLM-4) | GLM-4 模型与部署示例。 | 7.1k |
| [InternLM/InternLM](https://github.com/InternLM/InternLM) | 书生大模型生态。 | 7.3k |
| [BAAI/bge-m3](https://github.com/FlagOpen/FlagEmbedding) | BGE 嵌入、重排与检索模型。 | 12.0k |
| [togethercomputer/RedPajama-Data](https://github.com/togethercomputer/RedPajama-Data) | 开放训练数据配方。 | 5.0k |

### 推理与服务

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 高吞吐 LLM 推理与 OpenAI 兼容服务。 | 87.6k |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | 面向复杂 LLM 程序的高性能运行时。 | 31.0k |
| [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) | Hugging Face 生产级推理服务。 | 10.9k |
| [NVIDIA/TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) | NVIDIA GPU 高性能推理。 | 14.3k |
| [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) | 训练与推理优化。 | 42.8k |
| [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) | 跨端模型编译与部署。 | 23.0k |
| [ollama/ollama](https://github.com/ollama/ollama) | 本地运行与管理 LLM。 | 177.3k |
| [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | CPU/边缘设备 LLM 推理。 | 122.1k |
| [exllamav2/exllamav2](https://github.com/turboderp-org/exllamav2) | 量化模型 GPU 推理。 | 4.6k |
| [OpenBMB/MiniCPM](https://github.com/OpenBMB/MiniCPM) | 轻量模型与端侧部署。 | 10.1k |

## 大语言模型应用与 Agent

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | LLM 应用编排框架。 | 143.0k |
| [LangGraph](https://github.com/langchain-ai/langgraph) | 用于构建可控、可恢复 Agent 工作流的状态图框架。 | 42.2k |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | 数据连接与 RAG 应用框架。 | 51.2k |
| [microsoft/autogen](https://github.com/microsoft/autogen) | 多智能体应用框架。 | 60.1k |
| [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | AI 编排 SDK。 | 28.4k |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 角色化多智能体协作。 | 56.4k |
| [langgenius/dify](https://github.com/langgenius/dify) | LLM 应用开发与运营平台。 | 150.8k |
| [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) | 可视化 LLM 工作流。 | 55.0k |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | 可视化 AI 应用构建器。 | 152.6k |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | 统一 LLM API、代理与网关。 | 55.1k |
| [Vercel AI SDK](https://github.com/vercel/ai) | TypeScript 的 AI 应用与 Agent 开发工具包。 | 26.5k |
| [open-webui/open-webui](https://github.com/open-webui/open-webui) | 可扩展自托管 AI Web UI。 | 147.3k |
| [lobehub/lobe-chat](https://github.com/lobehub/lobehub) | 个人 AI 助手工作空间。 | 81.0k |
| [MudBlazor/PromptFlow](https://github.com/microsoft/promptflow) | LLM 应用流编排与评测。 | 11.2k |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 自主 Agent 实验平台。 | 185.7k |
| [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | 多角色软件开发 Agent。 | 33.9k |
| [geekan/MetaGPT](https://github.com/geekan/MetaGPT) | 软件公司式多智能体框架。 | 69.6k |
| [OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin) | 软件工程 Agent 平台。 | 82.6k |
| [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) | 代码任务智能体。 | 82.6k |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | 浏览器自动化 Agent。 | 107.3k |
| [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver) | 代码优先的任务规划 Agent。 | 6.2k |
| [composiohq/composio](https://github.com/ComposioHQ/composio) | Agent 工具与集成层。 | 29.5k |
| [TEN Framework](https://github.com/TEN-framework/ten-framework) | 开源对话式语音 AI Agent 框架。 | 11.1k |
| [LiveKit Agents](https://github.com/livekit/agents) | 构建实时语音与多模态 AI Agent 的框架。 | 13.1k |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | 用于语音 Agent、多模态应用和实时 AI 的开源框架。 | 14.3k |
| [mem0](https://github.com/mem0ai/mem0) | 可跨模型与框架复用的 AI Agent 记忆层。 | 63.5k |
| [pi](https://github.com/earendil-works/pi) | 提供统一模型 API、Agent 循环、终端界面与编码 Agent CLI 的工具包。 | 100.5k |
| [Hermes Agent](https://github.com/NousResearch/hermes-agent) | 可持续成长、支持工具调用与长期任务的开源 Agent。 | 243.4k |

## RAG、检索与向量数据库

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 生产级 NLP 与 RAG 管线。 | 26.1k |
| [ragflow/ragflow](https://github.com/infiniflow/ragflow) | 深度文档理解 RAG 引擎。 | 86.4k |
| [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) | 全栈私有 RAG 应用。 | 64.1k |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | AI 原生向量数据库。 | 28.9k |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | 高性能向量搜索引擎。 | 33.7k |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | 分布式向量数据库。 | 45.4k |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | 向量数据库与语义搜索。 | 16.7k |
| [facebookresearch/faiss](https://github.com/facebookresearch/faiss) | 稠密向量相似度搜索。 | 40.6k |
| [pgvector/pgvector](https://github.com/pgvector/pgvector) | PostgreSQL 向量扩展。 | 22.4k |
| [vespa-engine/vespa](https://github.com/vespa-engine/vespa) | 大规模搜索与推荐服务。 | 7.0k |
| [opensearch-project/OpenSearch](https://github.com/opensearch-project/OpenSearch) | 开源搜索与分析引擎。 | 13.4k |
| [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 搜索、分析与向量检索。 | 77.6k |
| [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) | 非结构化文档解析。 | 15.2k |
| [jina-ai/reader](https://github.com/jina-ai/reader) | 网页转 LLM 友好文本。 | 11.8k |
| [FlagOpen/FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding) | 中文/多语种嵌入与重排。 | 12.0k |
| [LLM Wiki](https://github.com/nashsu/llm_wiki) | 将文档自动构建为可关联、可持续维护的知识库桌面应用。 | 15.9k |
| [PixelRAG](https://github.com/StarTrail-org/PixelRAG) | 面向可扩展像素原生检索的 RAG 工具。 | 9.1k |
| [OpenKB](https://github.com/VectifyAI/OpenKB) | 开源 LLM 知识库。 | 3.3k |
| [LightRAG](https://github.com/HKUDS/LightRAG) | 简洁快速的图谱增强 RAG 框架。 | 38.9k |
| [GraphRAG](https://github.com/microsoft/graphrag) | Microsoft 开源的模块化图谱检索增强生成系统。 | 35.6k |
| [Graphiti](https://github.com/getzep/graphiti) | 为 AI Agent 构建实时知识图谱与时间感知记忆。 | 30.5k |
| [OpenViking](https://github.com/volcengine/OpenViking) | 统一 Agent 记忆、知识 RAG 与技能的自演进上下文数据库。 | 34.9k |
| [ragent](https://github.com/nageoffer/ragent) | 覆盖文档解析、多路检索、记忆与 MCP 的企业级 Agentic RAG 平台。 | 4.1k |

## 训练、微调与对齐

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [huggingface/transformers](https://github.com/huggingface/transformers) | 预训练模型库与训练工具。 | 163.1k |
| [huggingface/peft](https://github.com/huggingface/peft) | LoRA 等参数高效微调。 | 21.5k |
| [huggingface/trl](https://github.com/huggingface/trl) | SFT、DPO、RLHF 训练。 | 19.0k |
| [huggingface/accelerate](https://github.com/huggingface/accelerate) | 统一分布式训练接口。 | 9.8k |
| [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) | 开箱即用 LLM 微调。 | 73.6k |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | 高效微调与量化训练。 | 69.2k |
| [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) | LLM 后训练工具。 | 12.3k |
| [OpenRLHF/OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) | 高性能 RLHF 框架。 | 9.9k |
| [volcengine/verl](https://github.com/volcengine/verl) | 大模型强化学习训练。 | 22.7k |
| [NVIDIA/Megatron-LM](https://github.com/NVIDIA/Megatron-LM) | 超大 Transformer 分布式训练。 | 17.3k |
| [microsoft/LoRA](https://github.com/microsoft/LoRA) | LoRA 原始实现。 | 13.7k |
| [artidoro/qlora](https://github.com/artidoro/qlora) | 量化 LoRA 微调。 | 11.0k |
| [Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) | PyTorch 训练工程化。 | 31.3k |
| [NVIDIA/NeMo](https://github.com/NVIDIA/NeMo) | 对话、语音与多模态训练框架。 | 17.8k |

## 评测、可观测性与安全

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | 标准化语言模型评测。 | 13.5k |
| [open-compass/opencompass](https://github.com/open-compass/opencompass) | 大模型中文综合评测。 | 7.2k |
| [openai/evals](https://github.com/openai/evals) | LLM 评测框架。 | 19.1k |
| [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | 单元测试式 LLM 评测。 | 17.3k |
| [langfuse/langfuse](https://github.com/langfuse/langfuse) | LLM 可观测性与评测。 | 32.1k |
| [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) | AI 可观测性与漂移分析。 | 10.8k |
| [traceloop/openllmetry](https://github.com/traceloop/openllmetry) | 基于 OpenTelemetry 的 LLM 追踪。 | 7.3k |
| [microsoft/presidio](https://github.com/microsoft/presidio) | PII 识别与脱敏。 | 10.3k |
| [NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | 可编程安全护栏。 | 6.8k |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | LLM 输入输出安全。 | 3.2k |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | 结构化输出与验证。 | 7.2k |
| [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) | 常用提示词集合。 | 166.5k |

## 机器学习框架与 MLOps

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [pytorch/pytorch](https://github.com/pytorch/pytorch) | 主流深度学习框架。 | 102.1k |
| [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) | 端到端机器学习平台。 | 196.6k |
| [jax-ml/jax](https://github.com/jax-ml/jax) | 高性能数值计算与自动微分。 | 36.1k |
| [keras-team/keras](https://github.com/keras-team/keras) | 多后端深度学习 API。 | 64.2k |
| [scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn) | 经典机器学习库。 | 66.8k |
| [dmlc/xgboost](https://github.com/dmlc/xgboost) | 梯度提升框架。 | 28.6k |
| [ray-project/ray](https://github.com/ray-project/ray) | 分布式 AI 计算平台。 | 43.4k |
| [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow) | Kubernetes 上的机器学习工作流。 | 15.8k |
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | 实验跟踪与模型生命周期管理。 | 27.3k |
| [dvc/dvc](https://github.com/iterative/dvc) | 数据与模型版本管理。 | 15.8k |
| [wandb/wandb](https://github.com/wandb/wandb) | 实验追踪客户端。 | 11.2k |
| [prefecthq/prefect](https://github.com/PrefectHQ/prefect) | 数据/ML 工作流编排。 | 23.5k |
| [feast-dev/feast](https://github.com/feast-dev/feast) | 特征库。 | 7.2k |
| [bentoml/BentoML](https://github.com/bentoml/BentoML) | 模型服务与部署。 | 8.7k |
| [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core) | Kubernetes 模型推理。 | 4.8k |

## 计算机视觉

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) | YOLO 检测、分割与追踪。 | 60.0k |
| [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) | 目标检测工具箱。 | 32.9k |
| [open-mmlab/mmsegmentation](https://github.com/open-mmlab/mmsegmentation) | 语义分割工具箱。 | 9.9k |
| [open-mmlab/mmpose](https://github.com/open-mmlab/mmpose) | 姿态估计工具箱。 | 7.8k |
| [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) | 目标检测与分割。 | 34.6k |
| [opencv/opencv](https://github.com/opencv/opencv) | 通用计算机视觉库。 | 90.2k |
| [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) | OCR 与文档解析。 | 86.5k |
| [JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR) | 多语种 OCR。 | 29.8k |
| [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) | 开放词汇目标检测。 | 10.5k |
| [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything) | SAM 图像分割。 | 54.6k |
| [IDEA-Research/Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything) | 检测结合分割。 | 17.7k |
| [openai/CLIP](https://github.com/openai/CLIP) | 图文对比学习模型。 | 34.1k |
| [TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN) | 人脸修复。 | 37.6k |
| [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) | 图像超分辨率。 | 36.3k |

## 生成式图像与视频

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion) | Stable Diffusion 原始代码。 | 73.2k |
| [Stability-AI/generative-models](https://github.com/Stability-AI/generative-models) | SDXL 等生成模型。 | 27.2k |
| [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Stable Diffusion Web 界面。 | 164.3k |
| [comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI) | 节点式图像生成工作流。 | 122.8k |
| [invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI) | 专业级生成图像工具。 | 27.7k |
| [Fooocus-Project/Fooocus](https://github.com/lllyasviel/Fooocus) | 易用的图像生成 UI。 | 51.6k |
| [huggingface/diffusers](https://github.com/huggingface/diffusers) | 扩散模型工具库。 | 34.2k |
| [TencentARC/InstantMesh](https://github.com/TencentARC/InstantMesh) | 单图 3D 网格生成。 | 4.5k |
| [facebookresearch/pytorch3d](https://github.com/facebookresearch/pytorch3d) | 3D 深度学习库。 | 9.9k |
| [THUDM/CogVideo](https://github.com/THUDM/CogVideo) | 文本到视频模型。 | 12.9k |
| [OpenTalker/SadTalker](https://github.com/OpenTalker/SadTalker) | 音频驱动人像视频。 | 14.0k |
| [TencentARC/PhotoMaker](https://github.com/TencentARC/PhotoMaker) | 个性化图像生成。 | 10.1k |
| [haofanwang/ControlNet](https://github.com/lllyasviel/ControlNet) | 可控图像生成。 | 34.0k |
| [guoyww/AnimateDiff](https://github.com/guoyww/AnimateDiff) | 动画扩散模型。 | 12.2k |

## 语音、音频与音乐

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [openai/whisper](https://github.com/openai/whisper) | 多语种自动语音识别。 | 106.1k |
| [whisper.cpp](https://github.com/ggml-org/whisper.cpp) | 适合 Mac/Apple Silicon 的完全本地高速 Whisper 推理；支持 CPU/GPU 与字幕文件导出，需少量命令行操作。 | 52.6k |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | 适合批量处理或 NVIDIA GPU 的高效 Whisper 实现；可通过脚本导出字幕。 | 24.7k |
| [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit) | 适合普通用户：导入视频后用 Whisper 转写、导出 SRT/VTT，并可逐句校对和压制字幕。 | 13.7k |
| [Whisper-WebUI](https://github.com/jhj0517/Whisper-WebUI) | 本地网页工具：上传视频或 YouTube 链接生成 SRT/VTT/TXT，支持翻译与说话人分离。 | 2.8k |
| [auto-subtitle](https://github.com/m1guelpf/auto-subtitle) | 一条命令生成字幕并直接烧录进视频，适合会基础命令行的短视频创作者。 | 2.3k |
| [VideoSubFinder](https://github.com/SWHL/VideoSubFinder) | 从已有硬字幕的视频画面中 OCR 提取文字，而非语音识别。 | 0.1k |
| [coqui-ai/TTS](https://github.com/coqui-ai/TTS) | 文本转语音训练与推理。 | 45.8k |
| [myshell-ai/MeloTTS](https://github.com/myshell-ai/MeloTTS) | 多语种 TTS。 | 7.6k |
| [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) | 开源语音生成模型。 | 31.7k |
| [FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice) | 多语种语音生成。 | 22.5k |
| [2Noise/ChatTTS](https://github.com/2Noise/ChatTTS) | 对话式语音生成。 | 39.7k |
| [facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft) | 音乐与音频生成。 | 23.5k |
| [suno-ai/bark](https://github.com/suno-ai/bark) | 文本到音频生成。 | 39.2k |
| [RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) | 检索式音色转换。 | 36.8k |
| [m-bain/whisperX](https://github.com/m-bain/whisperX) | 带说话人分离的转写。 | 23.3k |

## 自然语言处理

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [explosion/spaCy](https://github.com/explosion/spaCy) | 工业级 NLP 库。 | 33.8k |
| [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza) | Stanford NLP 工具包。 | 7.9k |
| [hanlp-dev/hanlp](https://github.com/hankcs/HanLP) | 中文 NLP 工具包。 | 36.5k |
| [PaddlePaddle/PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP) | NLP 预训练与应用工具。 | 13.0k |
| [fastnlp/fastNLP](https://github.com/fastnlp/fastNLP) | NLP 训练框架。 | 3.1k |
| [google/sentencepiece](https://github.com/google/sentencepiece) | 子词分词器。 | 12.0k |
| [UKPLab/sentence-transformers](https://github.com/UKPLab/sentence-transformers) | 句向量与语义检索。 | 19.0k |
| [RasaHQ/rasa](https://github.com/RasaHQ/rasa) | 对话式 AI 框架。 | 21.3k |
| [microsoft/recognizers-text](https://github.com/microsoft/recognizers-text) | 文本实体识别器。 | 1.8k |

## 多模态与文档智能

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA) | 视觉语言助手。 | 25.0k |
| [OpenGVLab/InternVL](https://github.com/OpenGVLab/InternVL) | 多模态大模型。 | 10.1k |
| [QwenLM/Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) | 视觉语言模型。 | 19.7k |
| [THUDM/GLM-4-Voice](https://github.com/THUDM/GLM-4-Voice) | 端到端语音语言模型。 | 3.2k |
| [OpenBMB/MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V) | 轻量视觉语言模型。 | 26.1k |
| [VikParuchuri/marker](https://github.com/VikParuchuri/marker) | PDF 转 Markdown/JSON。 | 38.0k |
| [opendatalab/MinerU](https://github.com/opendatalab/MinerU) | 复杂 PDF 内容抽取。 | 76.2k |
| [allenai/olmOCR](https://github.com/allenai/olmocr) | 文档 OCR 与结构恢复。 | 19.2k |
| [facebookresearch/nougat](https://github.com/facebookresearch/nougat) | 学术文档转 Markdown。 | 10.1k |
| [ModelTC/lightllm](https://github.com/ModelTC/lightllm) | LLM 推理服务。 | 4.2k |

## 机器人、自动驾驶与具身智能

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [openai/gym](https://github.com/Farama-Foundation/Gymnasium) | 强化学习环境接口。 | 37.2k |
| [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium) | 维护中的 Gym API。 | 12.3k |
| [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3) | 强化学习算法实现。 | 13.6k |
| [ray-project/ray](https://github.com/ray-project/ray) | Ray RLlib 分布式强化学习。 | 43.4k |
| [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) | 物理仿真引擎。 | 14.4k |
| [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) | GPU 加速机器人学习。 | 7.8k |
| [openai/robosuite](https://github.com/ARISE-Initiative/robosuite) | 机器人操作仿真。 | 2.5k |
| [facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab) | 具身 AI 仿真平台。 | 3.1k |
| [openai/CLIP](https://github.com/openai/CLIP) | 视觉语义表征，常用于机器人感知。 | 34.1k |
| [autowarefoundation/autoware](https://github.com/autowarefoundation/autoware) | 开源自动驾驶软件栈。 | 11.9k |
| [commaai/openpilot](https://github.com/commaai/openpilot) | 高级驾驶辅助系统。 | 63.3k |
| [NVIDIA-Omniverse/IsaacLab](https://github.com/isaac-sim/IsaacLab) | 机器人训练框架。 | 7.8k |

## 科学计算与生物 AI

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [microsoft/AI4Science](https://github.com/microsoft/AI4Science) | AI for Science 资源集合（链接当前不可用）。 | 不可用 |
| [deepmind/alphafold](https://github.com/google-deepmind/alphafold) | 蛋白质结构预测。 | 14.8k |
| [sokrypton/ColabFold](https://github.com/sokrypton/ColabFold) | 高效 AlphaFold 工作流。 | 2.9k |
| [facebookresearch/esm](https://github.com/facebookresearch/esm) | 蛋白质语言模型。 | 4.2k |
| [aqlaboratory/openfold](https://github.com/aqlaboratory/openfold) | AlphaFold 复现。 | 3.4k |
| [microsoft/AI2BMD](https://github.com/microsoft/AI2BMD) | AI 分子动力学模拟。 | 0.6k |
| [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) | 科学大模型训练基础设施。 | 42.8k |
| [NVIDIA/modulus](https://github.com/NVIDIA/modulus) | 物理机器学习框架。 | 3.1k |
| [google-deepmind/alphamissense](https://github.com/google-deepmind/alphamissense) | 变异致病性预测。 | 0.6k |

## 开发者工具与本地 AI

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [Aider-AI/aider](https://github.com/Aider-AI/aider) | 终端里的 AI 结对编程。 | 47.8k |
| [continuedev/continue](https://github.com/continuedev/continue) | IDE 开源 AI 编程助手。 | 35.2k |
| [TabbyML/tabby](https://github.com/TabbyML/tabby) | 自托管代码补全。 | 33.8k |
| [microsoft/vscode](https://github.com/microsoft/vscode) | 编辑器生态，众多 AI 扩展的运行平台。 | 188.0k |
| [e2b-dev/E2B](https://github.com/e2b-dev/E2B) | AI Agent 安全代码沙箱。 | 13.2k |
| [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) | 自主软件工程 Agent。 | 82.6k |
| [getcursor/cursor](https://github.com/getcursor/cursor) | AI 代码编辑器相关开源资源。 | 33.1k |
| [NixOS/nix](https://github.com/NixOS/nix) | 可复现 AI 开发环境管理。 | 17.4k |
| [lmstudio-ai/lmstudio-js](https://github.com/lmstudio-ai/lmstudio-js) | LM Studio JavaScript SDK。 | 1.7k |
| [janhq/jan](https://github.com/janhq/jan) | 本地运行模型的桌面应用。 | 43.8k |
| [lobehub/lobe-chat](https://github.com/lobehub/lobehub) | 多模型个人工作台。 | 81.0k |
| [agent-browser](https://github.com/vercel-labs/agent-browser) | 面向 AI Agent 的浏览器自动化命令行工具。 | 40.9k |
| [agent-skills](https://github.com/addyosmani/agent-skills) | 面向 AI 编码 Agent 的生产级工程技能库。 | 93.0k |

## 数据集、社区与学习资源

| 项目 | 简介 | Star |
| --- | --- | ---: |
| [LAION-AI/laion5B](https://github.com/LAION-AI/laion5B) | 大规模图文数据集（链接当前不可用）。 | 不可用 |
| [huggingface/datasets](https://github.com/huggingface/datasets) | 数据集加载与处理库。 | 21.8k |
| [huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub) | Hugging Face Hub 客户端。 | 3.8k |
| [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | AI 应用示例与实践指南。 | 75.0k |
| [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 提示工程学习资源。 | 77.1k |
| [mlabonne/llm-course](https://github.com/mlabonne/llm-course) | LLM 系统学习路线。 | 81.3k |
| [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) | 从零构建语言模型。 | 100.1k |
| [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | AI 入门课程。 | 53.2k |
| [DataTalksClub/llm-zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) | LLM 工程课程。 | 6.9k |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | Awesome 列表规范与入口。 | 490.5k |
| [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | 自托管工具索引，含 AI 分类。 | 309.3k |
| [corona-warn-app/cwa-app-android](https://github.com/corona-warn-app/cwa-app-android) | 开源项目质量实践示例。 | 2.4k |

## 贡献建议

欢迎提交项目。建议每个条目满足以下条件：

1. 代码仓库公开且有明确开源许可证；
2. 与 AI、机器学习、数据智能或其工程生态直接相关；
3. 提供一句准确、简洁的中文说明；
4. 放入最贴切的分类，避免无意义重复。

提交格式：`- [组织/项目](https://github.com/owner/repo) — 一句话说明。`

## 许可证与商标

各项目的许可证、模型权重许可及商标政策以其原仓库为准。收录链接不代表本仓库对任何项目的背书或授权。
