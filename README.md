# AI 开源项目全景导航

> 面向开发者、研究者和产品团队的 AI 开源项目精选索引。按能力、模型、工程与应用场景分类，优先收录活跃、可复用、社区影响力较大的 GitHub 项目。

> **说明**：GitHub 上的 AI 项目持续增长，无法以静态文档“穷尽所有”。本仓库提供一个结构化、可持续更新的高质量入口；欢迎通过 Issue / PR 补充遗漏项目或修正状态。

## 目录

- [基础模型与推理](#基础模型与推理)
- [大语言模型应用与 Agent](#大语言模型应用与-agent)
- [RAG、检索与向量数据库](#rag检索与向量数据库)
- [训练、微调与对齐](#训练微调与对齐)
- [评测、可观测性与安全](#评测可观测性与安全)
- [机器学习框架与 MLOps](#机器学习框架与-mlops)
- [计算机视觉](#计算机视觉)
- [生成式图像与视频](#生成式图像与视频)
- [AI 视频与创作工具](#ai-视频与创作工具)
- [语音、音频与音乐](#语音音频与音乐)
- [自然语言处理](#自然语言处理)
- [多模态与文档智能](#多模态与文档智能)
- [机器人、自动驾驶与具身智能](#机器人自动驾驶与具身智能)
- [科学计算与生物 AI](#科学计算与生物-ai)
- [开发者工具与本地 AI](#开发者工具与本地-ai)
- [数据集、社区与学习资源](#数据集社区与学习资源)

## 基础模型与推理

- [meta-llama/llama](https://github.com/meta-llama/llama) — Llama 系列模型与推理代码。
- [QwenLM/Qwen](https://github.com/QwenLM/Qwen) — 通义千问模型、微调与部署资源。
- [mistralai/mistral-inference](https://github.com/mistralai/mistral-inference) — Mistral 模型参考推理实现。
- [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) — DeepSeek-V3 模型与技术资料。
- [deepseek-ai/DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) — 推理模型与蒸馏模型资源。
- [google-gemini/gemma_pytorch](https://github.com/google-gemini/gemma_pytorch) — Gemma PyTorch 实现。
- [google-research/bert](https://github.com/google-research/bert) — BERT 原始实现与预训练模型。
- [facebookresearch/llama](https://github.com/facebookresearch/llama) — LLaMA 研究代码。
- [EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox) — 大规模语言模型训练与推理。
- [bigscience-workshop/Megatron-DeepSpeed](https://github.com/bigscience-workshop/Megatron-DeepSpeed) — BLOOM 训练技术栈。
- [01-ai/Yi](https://github.com/01-ai/Yi) — Yi 系列模型资源。
- [THUDM/GLM-4](https://github.com/THUDM/GLM-4) — GLM-4 模型与部署示例。
- [InternLM/InternLM](https://github.com/InternLM/InternLM) — 书生大模型生态。
- [BAAI/bge-m3](https://github.com/FlagOpen/FlagEmbedding) — BGE 嵌入、重排与检索模型。
- [togethercomputer/RedPajama-Data](https://github.com/togethercomputer/RedPajama-Data) — 开放训练数据配方。

### 推理与服务

- [vllm-project/vllm](https://github.com/vllm-project/vllm) — 高吞吐 LLM 推理与 OpenAI 兼容服务。
- [sgl-project/sglang](https://github.com/sgl-project/sglang) — 面向复杂 LLM 程序的高性能运行时。
- [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) — Hugging Face 生产级推理服务。
- [NVIDIA/TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA GPU 高性能推理。
- [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) — 训练与推理优化。
- [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) — 跨端模型编译与部署。
- [ollama/ollama](https://github.com/ollama/ollama) — 本地运行与管理 LLM。
- [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) — CPU/边缘设备 LLM 推理。
- [exllamav2/exllamav2](https://github.com/turboderp-org/exllamav2) — 量化模型 GPU 推理。
- [OpenBMB/MiniCPM](https://github.com/OpenBMB/MiniCPM) — 轻量模型与端侧部署。

## 大语言模型应用与 Agent

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — LLM 应用编排框架。
- [run-llama/llama_index](https://github.com/run-llama/llama_index) — 数据连接与 RAG 应用框架。
- [microsoft/autogen](https://github.com/microsoft/autogen) — 多智能体应用框架。
- [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) — AI 编排 SDK。
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — 角色化多智能体协作。
- [langgenius/dify](https://github.com/langgenius/dify) — LLM 应用开发与运营平台。
- [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) — 可视化 LLM 工作流。
- [langflow-ai/langflow](https://github.com/langflow-ai/langflow) — 可视化 AI 应用构建器。
- [BerriAI/litellm](https://github.com/BerriAI/litellm) — 统一 LLM API、代理与网关。
- [open-webui/open-webui](https://github.com/open-webui/open-webui) — 可扩展自托管 AI Web UI。
- [lobehub/lobe-chat](https://github.com/lobehub/lobe-chat) — 个人 AI 助手工作空间。
- [MudBlazor/PromptFlow](https://github.com/microsoft/promptflow) — LLM 应用流编排与评测。
- [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — 自主 Agent 实验平台。
- [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) — 多角色软件开发 Agent。
- [geekan/MetaGPT](https://github.com/geekan/MetaGPT) — 软件公司式多智能体框架。
- [OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin) — 软件工程 Agent 平台。
- [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) — 代码任务智能体。
- [browser-use/browser-use](https://github.com/browser-use/browser-use) — 浏览器自动化 Agent。
- [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver) — 代码优先的任务规划 Agent。
- [composiohq/composio](https://github.com/ComposioHQ/composio) — Agent 工具与集成层。

## RAG、检索与向量数据库

- [deepset-ai/haystack](https://github.com/deepset-ai/haystack) — 生产级 NLP 与 RAG 管线。
- [ragflow/ragflow](https://github.com/infiniflow/ragflow) — 深度文档理解 RAG 引擎。
- [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) — 全栈私有 RAG 应用。
- [chroma-core/chroma](https://github.com/chroma-core/chroma) — AI 原生向量数据库。
- [qdrant/qdrant](https://github.com/qdrant/qdrant) — 高性能向量搜索引擎。
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — 分布式向量数据库。
- [weaviate/weaviate](https://github.com/weaviate/weaviate) — 向量数据库与语义搜索。
- [facebookresearch/faiss](https://github.com/facebookresearch/faiss) — 稠密向量相似度搜索。
- [pgvector/pgvector](https://github.com/pgvector/pgvector) — PostgreSQL 向量扩展。
- [vespa-engine/vespa](https://github.com/vespa-engine/vespa) — 大规模搜索与推荐服务。
- [opensearch-project/OpenSearch](https://github.com/opensearch-project/OpenSearch) — 开源搜索与分析引擎。
- [elastic/elasticsearch](https://github.com/elastic/elasticsearch) — 搜索、分析与向量检索。
- [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) — 非结构化文档解析。
- [jina-ai/reader](https://github.com/jina-ai/reader) — 网页转 LLM 友好文本。
- [FlagOpen/FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding) — 中文/多语种嵌入与重排。

## 训练、微调与对齐

- [huggingface/transformers](https://github.com/huggingface/transformers) — 预训练模型库与训练工具。
- [huggingface/peft](https://github.com/huggingface/peft) — LoRA 等参数高效微调。
- [huggingface/trl](https://github.com/huggingface/trl) — SFT、DPO、RLHF 训练。
- [huggingface/accelerate](https://github.com/huggingface/accelerate) — 统一分布式训练接口。
- [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — 开箱即用 LLM 微调。
- [unslothai/unsloth](https://github.com/unslothai/unsloth) — 高效微调与量化训练。
- [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) — LLM 后训练工具。
- [OpenRLHF/OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) — 高性能 RLHF 框架。
- [volcengine/verl](https://github.com/volcengine/verl) — 大模型强化学习训练。
- [NVIDIA/Megatron-LM](https://github.com/NVIDIA/Megatron-LM) — 超大 Transformer 分布式训练。
- [microsoft/LoRA](https://github.com/microsoft/LoRA) — LoRA 原始实现。
- [artidoro/qlora](https://github.com/artidoro/qlora) — 量化 LoRA 微调。
- [Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) — PyTorch 训练工程化。
- [NVIDIA/NeMo](https://github.com/NVIDIA/NeMo) — 对话、语音与多模态训练框架。

## 评测、可观测性与安全

- [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — 标准化语言模型评测。
- [open-compass/opencompass](https://github.com/open-compass/opencompass) — 大模型中文综合评测。
- [openai/evals](https://github.com/openai/evals) — LLM 评测框架。
- [confident-ai/deepeval](https://github.com/confident-ai/deepeval) — 单元测试式 LLM 评测。
- [langfuse/langfuse](https://github.com/langfuse/langfuse) — LLM 可观测性与评测。
- [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) — AI 可观测性与漂移分析。
- [traceloop/openllmetry](https://github.com/traceloop/openllmetry) — 基于 OpenTelemetry 的 LLM 追踪。
- [microsoft/presidio](https://github.com/microsoft/presidio) — PII 识别与脱敏。
- [NVIDIA/NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — 可编程安全护栏。
- [protectai/llm-guard](https://github.com/protectai/llm-guard) — LLM 输入输出安全。
- [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) — 结构化输出与验证。
- [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — 常用提示词集合。

## 机器学习框架与 MLOps

- [pytorch/pytorch](https://github.com/pytorch/pytorch) — 主流深度学习框架。
- [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) — 端到端机器学习平台。
- [jax-ml/jax](https://github.com/jax-ml/jax) — 高性能数值计算与自动微分。
- [keras-team/keras](https://github.com/keras-team/keras) — 多后端深度学习 API。
- [scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn) — 经典机器学习库。
- [dmlc/xgboost](https://github.com/dmlc/xgboost) — 梯度提升框架。
- [ray-project/ray](https://github.com/ray-project/ray) — 分布式 AI 计算平台。
- [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow) — Kubernetes 上的机器学习工作流。
- [mlflow/mlflow](https://github.com/mlflow/mlflow) — 实验跟踪与模型生命周期管理。
- [dvc/dvc](https://github.com/iterative/dvc) — 数据与模型版本管理。
- [wandb/wandb](https://github.com/wandb/wandb) — 实验追踪客户端。
- [prefecthq/prefect](https://github.com/PrefectHQ/prefect) — 数据/ML 工作流编排。
- [feast-dev/feast](https://github.com/feast-dev/feast) — 特征库。
- [bentoml/BentoML](https://github.com/bentoml/BentoML) — 模型服务与部署。
- [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core) — Kubernetes 模型推理。

## 计算机视觉

- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — YOLO 检测、分割与追踪。
- [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) — 目标检测工具箱。
- [open-mmlab/mmsegmentation](https://github.com/open-mmlab/mmsegmentation) — 语义分割工具箱。
- [open-mmlab/mmpose](https://github.com/open-mmlab/mmpose) — 姿态估计工具箱。
- [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) — 目标检测与分割。
- [opencv/opencv](https://github.com/opencv/opencv) — 通用计算机视觉库。
- [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) — OCR 与文档解析。
- [JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR) — 多语种 OCR。
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — 开放词汇目标检测。
- [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything) — SAM 图像分割。
- [IDEA-Research/Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything) — 检测结合分割。
- [openai/CLIP](https://github.com/openai/CLIP) — 图文对比学习模型。
- [TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN) — 人脸修复。
- [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) — 图像超分辨率。

## 生成式图像与视频

- [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion) — Stable Diffusion 原始代码。
- [Stability-AI/generative-models](https://github.com/Stability-AI/generative-models) — SDXL 等生成模型。
- [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) — Stable Diffusion Web 界面。
- [comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI) — 节点式图像生成工作流。
- [invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI) — 专业级生成图像工具。
- [Fooocus-Project/Fooocus](https://github.com/lllyasviel/Fooocus) — 易用的图像生成 UI。
- [huggingface/diffusers](https://github.com/huggingface/diffusers) — 扩散模型工具库。
- [TencentARC/InstantMesh](https://github.com/TencentARC/InstantMesh) — 单图 3D 网格生成。
- [facebookresearch/pytorch3d](https://github.com/facebookresearch/pytorch3d) — 3D 深度学习库。
- [THUDM/CogVideo](https://github.com/THUDM/CogVideo) — 文本到视频模型。
- [OpenTalker/SadTalker](https://github.com/OpenTalker/SadTalker) — 音频驱动人像视频。
- [TencentARC/PhotoMaker](https://github.com/TencentARC/PhotoMaker) — 个性化图像生成。
- [haofanwang/ControlNet](https://github.com/lllyasviel/ControlNet) — 可控图像生成。
- [guoyww/AnimateDiff](https://github.com/guoyww/AnimateDiff) — 动画扩散模型。

## AI 视频与创作工具

面向视频生成、剪辑、配音及制作流程自动化的开源应用。Star 数为 **2026-07-30** 从 GitHub API 获取的快照，随时间变化；点击项目链接可查看实时数据。

| 项目 | Star（快照） | 用途 |
| --- | ---: | --- |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | 44,009 | Agent 驱动的视频制作系统，含多条制作管线、工具与技能库。 |
| [voicebox](https://github.com/jamiepine/voicebox) | 47,411 | 开源 AI 语音工作室：克隆、口述与生成语音。 |
| [OpenCut](https://github.com/OpenCut-app/OpenCut) | 79,817 | 开源 CapCut 替代品。 |
| [video-use](https://github.com/browser-use/video-use) | 18,128 | 让编码 Agent 自动编辑视频。 |

## 语音、音频与音乐

- [openai/whisper](https://github.com/openai/whisper) — 多语种自动语音识别。
- [ggerganov/whisper.cpp](https://github.com/ggerganov/whisper.cpp) — 本地 Whisper 推理。
- [SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper) — 高效 Whisper 推理。
- [coqui-ai/TTS](https://github.com/coqui-ai/TTS) — 文本转语音训练与推理。
- [myshell-ai/MeloTTS](https://github.com/myshell-ai/MeloTTS) — 多语种 TTS。
- [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) — 开源语音生成模型。
- [FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice) — 多语种语音生成。
- [2Noise/ChatTTS](https://github.com/2Noise/ChatTTS) — 对话式语音生成。
- [facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft) — 音乐与音频生成。
- [suno-ai/bark](https://github.com/suno-ai/bark) — 文本到音频生成。
- [RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) — 检索式音色转换。
- [m-bain/whisperX](https://github.com/m-bain/whisperX) — 带说话人分离的转写。

## 自然语言处理

- [explosion/spaCy](https://github.com/explosion/spaCy) — 工业级 NLP 库。
- [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza) — Stanford NLP 工具包。
- [hanlp-dev/hanlp](https://github.com/hankcs/HanLP) — 中文 NLP 工具包。
- [PaddlePaddle/PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP) — NLP 预训练与应用工具。
- [fastnlp/fastNLP](https://github.com/fastnlp/fastNLP) — NLP 训练框架。
- [google/sentencepiece](https://github.com/google/sentencepiece) — 子词分词器。
- [UKPLab/sentence-transformers](https://github.com/UKPLab/sentence-transformers) — 句向量与语义检索。
- [RasaHQ/rasa](https://github.com/RasaHQ/rasa) — 对话式 AI 框架。
- [microsoft/recognizers-text](https://github.com/microsoft/recognizers-text) — 文本实体识别器。

## 多模态与文档智能

- [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA) — 视觉语言助手。
- [OpenGVLab/InternVL](https://github.com/OpenGVLab/InternVL) — 多模态大模型。
- [QwenLM/Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) — 视觉语言模型。
- [THUDM/GLM-4-Voice](https://github.com/THUDM/GLM-4-Voice) — 端到端语音语言模型。
- [OpenBMB/MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V) — 轻量视觉语言模型。
- [VikParuchuri/marker](https://github.com/VikParuchuri/marker) — PDF 转 Markdown/JSON。
- [opendatalab/MinerU](https://github.com/opendatalab/MinerU) — 复杂 PDF 内容抽取。
- [allenai/olmOCR](https://github.com/allenai/olmocr) — 文档 OCR 与结构恢复。
- [facebookresearch/nougat](https://github.com/facebookresearch/nougat) — 学术文档转 Markdown。
- [ModelTC/lightllm](https://github.com/ModelTC/lightllm) — LLM 推理服务。

## 机器人、自动驾驶与具身智能

- [openai/gym](https://github.com/openai/gym) — 强化学习环境接口。
- [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — 维护中的 Gym API。
- [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3) — 强化学习算法实现。
- [ray-project/ray](https://github.com/ray-project/ray) — Ray RLlib 分布式强化学习。
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) — 物理仿真引擎。
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — GPU 加速机器人学习。
- [openai/robosuite](https://github.com/ARISE-Initiative/robosuite) — 机器人操作仿真。
- [facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab) — 具身 AI 仿真平台。
- [openai/CLIP](https://github.com/openai/CLIP) — 视觉语义表征，常用于机器人感知。
- [autowarefoundation/autoware](https://github.com/autowarefoundation/autoware) — 开源自动驾驶软件栈。
- [commaai/openpilot](https://github.com/commaai/openpilot) — 高级驾驶辅助系统。
- [NVIDIA-Omniverse/IsaacLab](https://github.com/isaac-sim/IsaacLab) — 机器人训练框架。

## 科学计算与生物 AI

- [deepmind/alphafold](https://github.com/google-deepmind/alphafold) — 蛋白质结构预测。
- [sokrypton/ColabFold](https://github.com/sokrypton/ColabFold) — 高效 AlphaFold 工作流。
- [facebookresearch/esm](https://github.com/facebookresearch/esm) — 蛋白质语言模型。
- [aqlaboratory/openfold](https://github.com/aqlaboratory/openfold) — AlphaFold 复现。
- [microsoft/AI4Science](https://github.com/microsoft/AI4Science) — AI for Science 资源集合。
- [microsoft/AI2BMD](https://github.com/microsoft/AI2BMD) — AI 分子动力学模拟。
- [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed) — 科学大模型训练基础设施。
- [NVIDIA/modulus](https://github.com/NVIDIA/modulus) — 物理机器学习框架。
- [google-deepmind/alphamissense](https://github.com/google-deepmind/alphamissense) — 变异致病性预测。

## 开发者工具与本地 AI

- [Aider-AI/aider](https://github.com/Aider-AI/aider) — 终端里的 AI 结对编程。
- [continuedev/continue](https://github.com/continuedev/continue) — IDE 开源 AI 编程助手。
- [TabbyML/tabby](https://github.com/TabbyML/tabby) — 自托管代码补全。
- [microsoft/vscode](https://github.com/microsoft/vscode) — 编辑器生态，众多 AI 扩展的运行平台。
- [e2b-dev/E2B](https://github.com/e2b-dev/E2B) — AI Agent 安全代码沙箱。
- [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) — 自主软件工程 Agent。
- [getcursor/cursor](https://github.com/getcursor/cursor) — AI 代码编辑器相关开源资源。
- [NixOS/nix](https://github.com/NixOS/nix) — 可复现 AI 开发环境管理。
- [lmstudio-ai/lmstudio-js](https://github.com/lmstudio-ai/lmstudio-js) — LM Studio JavaScript SDK。
- [janhq/jan](https://github.com/janhq/jan) — 本地运行模型的桌面应用。
- [lobehub/lobe-chat](https://github.com/lobehub/lobe-chat) — 多模型个人工作台。

## 数据集、社区与学习资源

- [huggingface/datasets](https://github.com/huggingface/datasets) — 数据集加载与处理库。
- [huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub) — Hugging Face Hub 客户端。
- [LAION-AI/laion5B](https://github.com/LAION-AI/laion5B) — 大规模图文数据集。
- [openai/openai-cookbook](https://github.com/openai/openai-cookbook) — AI 应用示例与实践指南。
- [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — 提示工程学习资源。
- [mlabonne/llm-course](https://github.com/mlabonne/llm-course) — LLM 系统学习路线。
- [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) — 从零构建语言模型。
- [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) — AI 入门课程。
- [DataTalksClub/llm-zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) — LLM 工程课程。
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — Awesome 列表规范与入口。
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — 自托管工具索引，含 AI 分类。
- [corona-warn-app/cwa-app-android](https://github.com/corona-warn-app/cwa-app-android) — 开源项目质量实践示例。

## 贡献建议

欢迎提交项目。建议每个条目满足以下条件：

1. 代码仓库公开且有明确开源许可证；
2. 与 AI、机器学习、数据智能或其工程生态直接相关；
3. 提供一句准确、简洁的中文说明；
4. 放入最贴切的分类，避免无意义重复。

提交格式：`- [组织/项目](https://github.com/owner/repo) — 一句话说明。`

## 许可证与商标

各项目的许可证、模型权重许可及商标政策以其原仓库为准。收录链接不代表本仓库对任何项目的背书或授权。
