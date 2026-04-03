# AI Papers Reading List 📚

**A curated collection of 45 essential AI papers, organized by 7 research areas × 3 priority levels.**

AI 产品经理/工程师核心论文阅读清单 — 三级优先级 × 七大研究方向 × 45 篇必读论文

> From Transformer to Diffusion Models, from RLHF to Multimodal — the papers that shaped modern AI.

### How to use this list

- **Priority 1 (范式奠基):** Must-read foundations — start here
- **Priority 2 (技术突破):** Key breakthroughs that moved the field forward
- **Priority 3 (前沿探索):** Cutting-edge research directions

If you're an AI PM, read Priority 1 first. If you're a researcher, go deep into your area of interest.

---

## 🏛️ 范式奠基类（12 篇）

### 大语言模型

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 1 | Attention Is All You Need | Vaswani et al. (Google) | 2017 | 提出 Transformer 架构，奠定现代 LLM 基础 | [📄](https://arxiv.org/abs/1706.03762) |
| 2 | BERT: Pre-training of Deep Bidirectional Transformers | Devlin et al. (Google) | 2018 | 双向预训练+微调范式，NLP 任务 SOTA | [📄](https://arxiv.org/abs/1810.04805) |
| 3 | Language Models are Unsupervised Multitask Learners (GPT-2) | Radford et al. (OpenAI) | 2019 | 证明大规模预训练的零样本能力 | — |
| 4 | Language Models are Few-Shot Learners (GPT-3) | Brown et al. (OpenAI) | 2020 | 175B 参数，涌现 In-Context Learning 能力 | [📄](https://arxiv.org/abs/2005.14165) |
| 5 | Scaling Laws for Neural Language Models | Kaplan et al. (OpenAI) | 2020 | 建立参数/数据/算力的幂律缩放法则 | [📄](https://arxiv.org/abs/2001.08361) |

### 扩散模型/图像生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 6 | Denoising Diffusion Probabilistic Models (DDPM) | Ho et al. (UC Berkeley) | 2020 | 扩散模型的标准化框架，奠定理论基础 | [📄](https://arxiv.org/abs/2006.11239) |
| 7 | Score-Based Generative Modeling through SDEs | Song et al. (Stanford) | 2021 | 连续时间扩散，统一理解框架 | [📄](https://arxiv.org/abs/2011.13456) |

### 多模态/跨模态

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 8 | CLIP: Learning Transferable Visual Models From NL Supervision | Radford et al. (OpenAI) | 2021 | 对比学习连接视觉-语言，多模态基石 | [📄](https://arxiv.org/abs/2103.00020) |
| 9 | ViT: An Image is Worth 16x16 Words | Dosovitskiy et al. (Google) | 2021 | Transformer 应用于纯视觉任务 | [📄](https://arxiv.org/abs/2010.11929) |

### 声音生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 10 | WaveNet: A Generative Model for Raw Audio | van den Oord et al. (DeepMind) | 2016 | 自回归音频生成，高质量语音合成 | [📄](https://arxiv.org/abs/1609.03499) |
| 11 | Tacotron: Towards End-to-End Speech Synthesis | Wang et al. (Google) | 2017 | 端到端 TTS 架构，序列到序列 | [📄](https://arxiv.org/abs/1703.10135) |
| 12 | SoundStream: An End-to-End Neural Audio Codec | Zeghidour et al. (Google) | 2021 | 神经音频编解码器，VALL-E/AudioLM 基础组件 | [📄](https://arxiv.org/abs/2107.03312) |

---

## 🚀 关键性突破（21 篇）

### 大语言模型

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 13 | InstructGPT: Training LMs to Follow Instructions | Ouyang et al. (OpenAI) | 2022 | RLHF 范式，解决对齐问题 | [📄](https://arxiv.org/abs/2203.02155) |
| 14 | Chain-of-Thought Prompting Elicits Reasoning in LLMs | Wei et al. (Google) | 2022 | 开创 CoT 推理范式，激发逐步推理能力 | [📄](https://arxiv.org/abs/2201.11903) |
| 15 | Constitutional AI: Harmlessness from AI Feedback | Bai et al. (Anthropic) | 2022 | RLAIF，无需人工标注实现对齐 | [📄](https://arxiv.org/abs/2212.08073) |
| 16 | Retrieval-Augmented Generation (RAG) | Lewis et al. (Meta) | 2020 | 检索增强生成，解决知识更新与幻觉 | [📄](https://arxiv.org/abs/2005.11401) |
| 17 | LLaMA: Open and Efficient Foundation Language Models | Touvron et al. (Meta) | 2023 | 开源高效 LLM，解决算力门槛 | [📄](https://arxiv.org/abs/2302.13971) |
| 18 | GPT-4 Technical Report | OpenAI | 2023 | 多模态 LLM，推理能力质变 | [📄](https://arxiv.org/abs/2303.08774) |
| 19 | DeepSeek-V2 | DeepSeek-AI | 2024 | MLA 注意力 + DeepSeekMoE，推理成本降至 1/5 | [📄](https://arxiv.org/abs/2405.04434) |
| 20 | DeepSeek-V3 Technical Report | DeepSeek-AI | 2024 | 671B MoE, FP8 训练, $5.576M 达 GPT-4o 水平 | [📄](https://arxiv.org/abs/2412.19437) |
| 21 | DeepSeek-R1 | DeepSeek-AI | 2025 | 纯 RL(GRPO) 涌现推理能力，对标 OpenAI o1 | [📄](https://arxiv.org/abs/2501.12948) |

### 扩散模型/图像生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 22 | Diffusion Models Beat GANs on Image Synthesis | Dhariwal & Nichol (OpenAI) | 2021 | 超越 GAN，扩散模型成为主流 | [📄](https://arxiv.org/abs/2105.05233) |
| 23 | Classifier-Free Diffusion Guidance | Ho & Salimans (Google) | 2022 | 无需分类器的引导采样，核心技术 | [📄](https://arxiv.org/abs/2207.12598) |
| 24 | DALL-E 2 | Ramesh et al. (OpenAI) | 2022 | CLIP 驱动 T2I 里程碑 | [📄](https://arxiv.org/abs/2204.06125) |
| 25 | Imagen | Saharia et al. (Google) | 2022 | 纯文本编码器(T5)驱动高质量 T2I | [📄](https://arxiv.org/abs/2205.11487) |
| 26 | Latent Diffusion Models (LDM / Stable Diffusion) | Rombach et al. (LMU Munich) | 2022 | 潜空间扩散，降低计算成本约 1000 倍 | [📄](https://arxiv.org/abs/2112.10752) |
| 27 | DiT: Scalable Diffusion Models with Transformers | Peebles & Xie (Berkeley/NYU) | 2023 | Transformer 替代 U-Net，可扩展性突破 | [📄](https://arxiv.org/abs/2212.09748) |

### 多模态/跨模态

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 28 | Flamingo | Alayrac et al. (DeepMind) | 2022 | 少样本多模态学习，视觉对话 | [📄](https://arxiv.org/abs/2204.14198) |
| 29 | GPT-4V(ision) System Card | OpenAI | 2023 | 原生多模态理解，视觉推理能力 | [📄](https://openai.com/index/gpt-4v-system-card/) |
| 30 | Gemini | Google DeepMind | 2023 | 原生多模态架构，统一编码器 | [📄](https://arxiv.org/abs/2312.11805) |
| 31 | Segment Anything Model (SAM) | Kirillov et al. (Meta) | 2023 | 通用分割基础模型，SA-1B 数据集 | [📄](https://arxiv.org/abs/2304.02643) |

### 声音生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 32 | AudioLM | Borsos et al. (Google) | 2022 | LM 范式生成音频，长序列一致性 | [📄](https://arxiv.org/abs/2209.03143) |
| 33 | Whisper | Radford et al. (OpenAI) | 2022 | 大规模弱监督 ASR，多语言通用 | [📄](https://arxiv.org/abs/2212.04356) |
| 34 | VALL-E | Wang et al. (Microsoft) | 2023 | 零样本语音克隆，离散 token 表示 | [📄](https://arxiv.org/abs/2301.02111) |

### 视频生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 35 | CogVideo | Hong et al. (Tsinghua/Zhipu) | 2022 | 大规模 T2V 预训练早期探索 | [📄](https://arxiv.org/abs/2205.15868) |
| 36 | Sora | OpenAI | 2024 | 长时视频生成，世界模拟器定位 | [📄](https://openai.com/index/video-generation-models-as-world-simulators/) |

### AI Agent

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 37 | ReAct: Synergizing Reasoning and Acting in LMs | Yao et al. (Princeton/Google) | 2022 | 推理+行动交替范式，Agent 奠基工作 | [📄](https://arxiv.org/abs/2210.03629) |

---

## 🔧 优化雕花（12 篇）

### 大语言模型

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 38 | LoRA: Low-Rank Adaptation of Large LMs | Hu et al. (Microsoft) | 2021 | 参数高效微调，降低部署成本 | [📄](https://arxiv.org/abs/2106.09685) |
| 39 | FlashAttention | Dao et al. (Stanford) | 2022 | IO 优化，加速训练推理 | [📄](https://arxiv.org/abs/2205.14135) |
| 40 | Self-Consistency Improves CoT Reasoning | Wang et al. (Google) | 2022 | 多路径投票提升推理准确性 | [📄](https://arxiv.org/abs/2203.11171) |
| 41 | QLoRA | Dettmers et al. (UW) | 2023 | 4bit 量化微调，单 GPU 训练大模型 | [📄](https://arxiv.org/abs/2305.14314) |
| 42 | DPO: Direct Preference Optimization | Rafailov et al. (Stanford) | 2023 | 去掉 reward model，简化 RLHF | [📄](https://arxiv.org/abs/2305.18290) |
| 43 | Mixtral of Experts | Jiang et al. (Mistral AI) | 2024 | 稀疏 MoE 架构，效率质量平衡 | [📄](https://arxiv.org/abs/2401.04088) |

### 扩散模型/图像生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 44 | DPM-Solver | Lu et al. (Tsinghua) | 2022 | 加速采样，10-20 步达 1000 步效果 | [📄](https://arxiv.org/abs/2206.00927) |
| 45 | ControlNet | Zhang & Agrawala (Stanford) | 2023 | 精确可控生成，保持预训练权重 | [📄](https://arxiv.org/abs/2302.05543) |
| 46 | Consistency Models | Song et al. (OpenAI) | 2023 | 单步生成，极速采样 | [📄](https://arxiv.org/abs/2303.01469) |
| 47 | SDXL | Podell et al. (Stability AI) | 2023 | 架构优化，1024 原生高清 | [📄](https://arxiv.org/abs/2307.01952) |
| 48 | Latent Consistency Models | Luo et al. (Tsinghua) | 2023 | 少步蒸馏，近实时生成 | [📄](https://arxiv.org/abs/2310.04378) |

### 多模态/跨模态

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 49 | LLaVA | Liu et al. (UW/Microsoft) | 2023 | 指令微调多模态，数据高效 | [📄](https://arxiv.org/abs/2304.08485) |
| 50 | Depth Anything | Yang et al. (HKU/TikTok) | 2024 | 零样本单目深度估计 | [📄](https://arxiv.org/abs/2401.10891) |

### 声音生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 51 | FastSpeech 2 | Ren et al. (Zhejiang/Microsoft) | 2021 | 非自回归 TTS，并行推理 | [📄](https://arxiv.org/abs/2006.04558) |
| 52 | Bark | Suno AI | 2023 | 开源多语言 TTS，情感韵律 | [📄](https://github.com/suno-ai/bark) |
| 53 | MusicGen | Copet et al. (Meta) | 2023 | 文本生成音乐，条件控制 | [📄](https://arxiv.org/abs/2306.05284) |

### 视频生成

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 54 | VideoPoet | Kondratyuk et al. (Google) | 2024 | LLM 统一框架处理多种视频任务 | [📄](https://arxiv.org/abs/2312.14125) |

### AI Agent

| # | 论文标题 | 作者/团队 | 年份 | 核心贡献 | 链接 |
|---|---------|----------|------|---------|------|
| 55 | Toolformer | Schick et al. (Meta) | 2023 | LLM 自主学习使用外部工具 API | [📄](https://arxiv.org/abs/2302.04761) |

---

## 📊 统计概览

| 维度 | 分类 | 数量 |
|------|------|------|
| **优先级** | 🏛️ 范式奠基类 | 12 |
| | 🚀 关键性突破 | 21 |
| | 🔧 优化雕花 | 12 |
| **方向** | 大语言模型 | 17 |
| | 扩散模型/图像生成 | 12 |
| | 多模态/跨模态 | 8 |
| | 声音生成 | 9 |
| | 视频生成 | 3 |
| | AI Agent | 2 |

---

*最后更新：2025年*

---

## Contributing

Know a paper that should be on this list? Open an issue or PR! Please include:
- Paper title and arXiv link
- Which category it belongs to
- A one-line description of its core contribution

## Star History

If this list helped you, a ⭐ would be appreciated!

---

**Curated by:** [Yueying Wu](https://yueyingai.com) · [GitHub](https://github.com/yueying526) · [X](https://x.com/wuyueying526)

