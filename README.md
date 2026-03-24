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

### Week 01 — Attention Introduction
- [x] **Lecture:** Deep learning recap, embeddings, RNN bottleneck, from recurrence to attention
- [x] **Seminar:** Torch basics recap, implementing Bahdanau attention

### Week 02 — Transformer Basics
- [x] **Lecture:** QKV attention, feed-forward networks, residual connections, layer normalization, positional encoding, dropout, tokenization, sampling
- [x] **Seminar:** Transformer implementation from scratch
- [x] **Homework 1** is out

### Week 03 — Transformers in NLP
- [x] **Lecture:** Transfer learning, BERT, BART, RoBERTa, GPT, T5
- [x] **Seminar:** Hugging Face Transformers

### Week 04 — Transformers in Computer Vision
- [x] **Lecture:** DETR, ViT, Swin Transformer
- [x] **Seminar:** ViT deep dive

### Week 05 — Transformer Training
- [ ] **Lecture:** Pretraining objectives, prefix tuning, PEFT, LoRA, DPO
- [ ] **Seminar:** Hugging Face TRL
- [ ] **Homework 2** is out

### Week 06 — Multimodal Transformers
- [x] **Lecture:** MLLMs, image-text fusion, vision-language models
- [x] **Seminar:** vLLM introduction

### Week 07 — Efficient Transformers
- [x] **Lecture:** KV cache, pruning, quantization, distillation, GPU parallelism
- [ ] **Seminar:** To be announced

### Week 08 — Memory in Transformers
- [ ] **Lecture:** Memory classification, Transformer-XL, RMT, Memory Transformer, RAG, Titans
- [ ] **Seminar:** Transformer-XL implementation
- [ ] **Homework 3** is out

### Week 09 — Transformers in Other Domains
- [ ] **Lecture:** Audio, robotics, tabular ML, biology
- [ ] **Seminar:** SmolVLA overview

### Week 10 — Exam Consultation
- [ ] **Consultation session**

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
