# Transformers in Deep Learning Course

Lecture and hands-on materials for each week are organized in the `./week*` folders.  
All assignments can be completed either locally or in **Google Colab** — see the corresponding README files inside each weekly folder for setup and instructions.

<img width="1536" height="1024" alt="example 10" src="https://github.com/user-attachments/assets/154892d7-eaaa-4838-8a21-b94e8d73198b" />

This course provides a practical introduction to **transformer architectures** and their applications across natural language processing, computer vision, multimodal learning, efficient inference, and embodied AI.  
We start from the motivation behind attention, build transformer models from scratch, and gradually move toward modern training techniques, memory mechanisms, and domain-specific applications.

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

![Untitled Diagram](https://github.com/user-attachments/assets/f4e13f31-db50-46ae-9929-a929fd5a6217)



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
- [ ] **Lecture:** PEFT, prompt tuning, prefix tuning, adapters, LoRA, pruning, mixed precision, quantization, QLoRA, distillation
- [x] **Seminar:** PEFT, quantization, and model compression in practice

### Week 08 — Distributed Training and Efficient Inference
- [x] **Lecture:** Data parallelism, pipeline parallelism, tensor parallelism, ZeRO, efficient attention, KV-cache, inference optimization
- [x] **Seminar:** Distributed training and efficient attention in practice

### Week 09 — Memory in Transformers and Retrieval
- [x] **Lecture:** Long-context transformers, memory compression, memory evaluation, Transformer-XL, RMT, retrieval-augmented generation (RAG)
- [x] **Seminar:** Transformer-XL / memory-augmented transformer implementation
- [ ] **Homework 3** is out


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
