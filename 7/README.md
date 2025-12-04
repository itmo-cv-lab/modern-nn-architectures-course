# 🎯 Lecture 7: Efficient Deep Learning — Quantization, Pruning & Distillation

This lecture explores essential model compression and optimization techniques that enable deploying large neural networks efficiently in production environments. Modern transformer models have grown from hundreds of megabytes to hundreds of gigabytes (100+ GB in FP32), creating a critical challenge for deployment on resource-constrained devices.

We'll dive deep into four main optimization approaches: **Quantization** — the primary focus, covering number formats (FP32, FP16, BF16, INT8, INT4), linear quantization principles, symmetric vs asymmetric modes, post-training quantization (PTQ) vs quantization-aware training (QAT); **Pruning** — techniques for removing least significant weights through magnitude pruning, iterative magnitude pruning, and structured pruning methods; **Knowledge Distillation** — transferring knowledge from large teacher models to compact student models through offline, online, and self-distillation approaches, including feature-based and relation-based variants; and **Mixed Precision Training** — using FP16 for forward/backward passes while maintaining FP32 master weights for precision, resulting in 30–50% VRAM savings and 1.5–2.5x speedup. These techniques are critical for deploying LLMs on limited resources, reducing inference costs, and working with mobile and edge devices.

## 📚 Course Materials

### 📖 Lecture Slides
- **PDF Version:** [`7_qpd.pdf`](./7_qpd.pdf)
- **PowerPoint Version:** [`7_qpd.pptx`](./7_qpd.pptx)

### 💻 Practice Notebook
- **Jupyter Notebook:** [`knowledge_distil.ipynb`](./knowledge_distil.ipynb)

## 📝 Homework Assignment
- **Assignment Details:** [Google Drive Folder](https://docs.google.com/document/d/1leCDGSiVA9wwLebYONn1ssB5bzAkf1tpjLZ8mifZrYU/edit?usp=sharing)

---

*This lecture provides deep insights into efficient deep learning techniques — the essential knowledge for optimizing and deploying large models, enabling state-of-the-art neural networks to run efficiently on edge devices, mobile platforms, and production environments with limited computational resources.*

