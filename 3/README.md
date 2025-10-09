# 🚀 Lecture 3: Transformers Advanced

This lecture explores advanced concepts in modern Transformer architectures and how they drive today's large language models. We'll start with Scaling Laws — the mathematical principles behind model and data scaling — then move to inference optimization techniques like KV-cache and speculative decoding that make LLMs faster in practice. Next, we'll dive into architectural innovations such as GQA/MQA, sliding-window, sparse attention, and Mixture of Experts, which enable massive models to train and infer efficiently. Finally, we'll cover lightweight fine-tuning methods like LoRA, explaining how they allow researchers to adapt huge models cheaply and effectively — and look at the latest research and tools built around them.

## 📹 Video Content
- **Lecture & Practice:** [Watch on Yandex Disk](https://disk.yandex.ru/d/lWjrCgtjuBof3A)

## 📚 Course Materials

### 📖 Lecture Slides
- **PDF Version:** [`3_transformer_advanced.pdf`](./3_transformer_advanced.pdf)
- **PowerPoint Version:** [`3_transformer_advanced.pptx`](./3_transformer_advanced.pptx)

### 💻 Practice Notebook
- **Jupyter Notebook:** [`3_lora_qlora_finetune.ipynb`](./3_lora_qlora_finetune.ipynb)

## 📝 Homework Assignment
- **Assignment Details:** [Google Drive Document](https://docs.google.com/document/d/1dyrNkDTJfaolxkdJJ9-3F1fMCthoeXgtrBxxJ0FRXEI/edit?usp=sharing)

## 🎯 Key Topics Covered

### 📊 Scaling Laws
- **Power law relationships** in neural network scaling
- **Model size, data size, and compute** trade-offs
- **Chinchilla scaling laws** and optimal training
- **Emergent abilities** in large language models

### ⚡ Inference Optimization
- **KV-cache mechanism** for faster autoregressive generation
- **Speculative decoding** and parallel sampling
- **Flash Attention** and memory-efficient attention
- **Quantization techniques** for deployment

### 🏗️ Advanced Architectural Innovations
- **GQA (Grouped Query Attention)** and **MQA (Multi-Query Attention)**
- **Sliding-window attention** mechanisms
- **Sparse attention patterns** and efficient transformers
- **Mixture of Experts (MoE)** architectures
- **Router mechanisms** and expert selection strategies

### 🔧 Parameter-Efficient Fine-Tuning
- **LoRA (Low-Rank Adaptation)** principles and implementation
- **QLoRA** for quantized fine-tuning
- **Adapter modules** and their variants
- **Prompt tuning** and soft prompts
- **Latest research** in efficient adaptation methods
- **Tools and frameworks** for PEFT (HuggingFace PEFT, etc.)

### 🛠️ Practical Applications
- **Fine-tuning large models** on limited hardware
- **Multi-task learning** with adapters
- **Merging and sharing** LoRA weights
- **Production deployment** considerations

---

*This lecture provides deep insights into the cutting-edge techniques that make modern LLMs both powerful and practical, from training at scale to efficient fine-tuning and deployment.*

