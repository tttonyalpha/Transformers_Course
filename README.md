# Transformers in Deep Learning Course


[Transformer Deep Learning Models](https://www.hse.ru/en/edu/courses/1048887081) is a 3-ECTS course taught at HSE University by the Faculty of Computer Science during Module 3 of the 2025/2026 academic year. 

Lecture and hands-on materials for each week are organized in the `./week*` folders. All assignments can be completed either locally or in **Google Colab** — see the corresponding README files inside each weekly folder for setup and instructions.

![Untitled Diagram](https://github.com/user-attachments/assets/f4e13f31-db50-46ae-9929-a929fd5a6217)

This course provides a practical introduction to **transformer architectures** and their applications across natural language processing, computer vision, multimodal learning, efficient inference, and embodied AI. We start from the motivation behind attention, build transformer models from scratch, and gradually move toward modern training techniques, memory mechanisms, and domain-specific applications.

<div align="center">

[![Course](https://img.shields.io/badge/course-transformers%20in%20deep%20learning-6C63FF?style=for-the-badge)](#syllabus)
[![Materials](https://img.shields.io/badge/materials-weekly%20lectures%20%26%20seminars-111111?style=for-the-badge)](#syllabus)
[![Additional%20Resources](https://img.shields.io/badge/resources-extra%20reading-0EA5E9?style=for-the-badge)](#additional-materials)

</div>

<br/>

## Contents
* [**📚 Syllabus**](#syllabus)
* [**🗂 Repository Structure**](#repository-structure)
* [**📖 Additional Materials**](#additional-materials)
* [**👩‍🏫 Course Staff**](#course-staff)

---

<h2 id="syllabus">📚 Syllabus</h2>

### Week 01 — Attention Introduction
- [x] **Lecture:** Course introduction, transformers timeline, embeddings, seq2seq models, RNN bottleneck, encoder-decoder attention
- [x] **Seminar:** Torch basics recap, implementing Bahdanau attention

### Week 02 — Transformer Basics
- [x] **Lecture:** Self-attention, masked attention, multi-head attention, encoder-decoder architecture, feed-forward blocks, residual connections, layer normalization, positional encoding
- [x] **Seminar:** Transformer implementation from scratch
- [x] **Homework 1** is out

### Week 03 — Transformers in NLP
- [x] **Lecture:** Transfer learning, BERT, GPT, MLM vs LM objectives, downstream fine-tuning, RoBERTa, ELECTRA, BART, T5
- [x] **Seminar:** Hugging Face Transformers

### Week 04 — Transformers in Computer Vision
- [x] **Lecture:** Vision Transformer (ViT), patch embeddings, ViT pretraining, ViT vs CNNs, Swin Transformer, DETR, SegFormer
- [x] **Seminar:** ViT deep dive

### Week 05 — Multimodal Transformers
- [x] **Lecture:** Multimodal learning, multimodal embeddings, CLIP, SigLIP, image tokenization, fusion architectures for vision-language models
- [x] **Seminar:** Vision-language models and multimodal embeddings
- [x] **Homework 2** is out

### Week 06 — Transformer Training and Adaptation
- [x] **Lecture:** Training basics, scaling laws, instruction tuning, RLHF, DPO, reinforcement learning, Chain-of-Thought, test-time scaling
- [x] **Seminar:** Hugging Face TRL and practical fine-tuning workflows

### Week 07 — Efficient Fine-Tuning and Compression
- [x] **Lecture:** PEFT, prompt tuning, prefix tuning, adapters, LoRA, pruning, mixed precision, quantization, QLoRA, distillation
- [x] **Seminar:** PEFT, quantization, and model compression in practice

### Week 08 — Distributed Training and Efficient Inference
- [x] **Lecture:** Data parallelism, pipeline parallelism, tensor parallelism, ZeRO, efficient attention, KV-cache, inference optimization
- [x] **Seminar:** Distributed training and efficient attention in practice

### Week 09 — Memory in Transformers and Retrieval
- [x] **Lecture:** Long-context transformers, memory compression, memory evaluation, Transformer-XL, RMT, retrieval-augmented generation (RAG)
- [x] **Seminar:** Transformer-XL / memory-augmented transformer implementation
- [x] **Homework 3** is out


### Week 10 — Diffusion Transformers
- [x] **Lecture:** Diffusion models, conditional generation, U-Net, Diffusion Transformers (DiT), text-to-image generation, ControlNet, Whisper
- [x] **Seminar:** DiT and diffusion-model pipeline walkthrough

> Syllabus is subject to minor updates during the course.
---

<h2 id="repository-structure">🗂 Repository Structure</h2>

The repository is organized by week:

```bash
.
├── week01/
├── week02/
├── week03/
├── ...
└── week10/

```

<h2 id="additional-materials">📖 Additional Materials</h2>

Each weekly folder contains additional study materials related to that week's topics. For students who would like to go deeper, a list of recommended external courses and recorded lecture series is also provided below.

  - [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — one of the most authoritative lecture series focused specifically on transformers, with talks from leading researchers and broad coverage of LLMs, multimodality, robotics, biology, and current frontier directions.
  - [Stanford CS224N: Natural Language Processing with Deep Learning](https://web.stanford.edu/class/cs224n/) — a flagship NLP course that covers modern transformer-based NLP, including attention, encoder-decoder models, pretraining, post-training, efficient adaptation, and language model agents.
  - [Stanford CS336: Language Modeling from Scratch](https://cs336.stanford.edu/) — an excellent advanced course on how modern language models are actually built, from data collection and preprocessing to transformer design, training, evaluation, and deployment.
  - [CMU 11-777: Multimodal Machine Learning](https://cmu-mmml.github.io/) — a top academic course on multimodal learning, covering alignment, fusion, reasoning, generation, multimodal transformers, and real applications across language, vision, and audio.
  - [UC Berkeley CS 198-126: Deep Learning for Visual Data](https://ml.berkeley.edu/decal) — a very relevant course for the vision and generative parts of your syllabus, with lectures on attention and transformers, vision transformers, CLIP, multimodality, vector quantization, and diffusion models.
  - [MIT 6.5940 / EfficientML.ai: TinyML and Efficient Deep Learning Computing](https://hanlab.mit.edu/courses/2024-fall-65940) — one of the strongest openly available courses on efficiency topics such as pruning, quantization, distillation, vision transformers, diffusion, long-context LLMs, and distributed training.
  - [MIT 6.S183: A Practical Introduction to Diffusion Models](https://www.practical-diffusion.org/) — a focused and very useful course for the final part of your program, with lecture videos on diffusion fundamentals, DDPM/DDIM, conditioning, guidance, distillation, and applications.
  - [Full Stack Deep Learning: LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) — a practical industry-oriented lecture series on LLM foundations, prompt engineering, retrieval, LLMOps, product design, and building real-world LLM-powered systems.


<h2 id="course-staff">👩‍🏫 Course Staff</h2>

- [Nikita Kachaev](https://tttonyalpha.github.io) - lectures, seminars

