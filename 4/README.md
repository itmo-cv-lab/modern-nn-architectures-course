# 🎨 Lecture 4: Generative Computer Vision Basic

This lecture explores the fundamental theory of generative models and their classification based on density approximation approaches. We'll examine how generative models are categorized into three main types: those that compute density directly (ARMs), those that approximate it using ELBO (VAE, Diffusion Models), and those that don't rely on density estimation (GANs). The lecture covers the theoretical foundations and practical implementations of these different approaches to generative modeling.

## 📹 Video Content
- **Lecture & Practice:** [Watch on Yandex Disk](https://disk.yandex.ru/d/lWjrCgtjuBof3A)

## 📚 Course Materials

### 📖 Lecture Slides
- **PDF Version:** [`4_gencv_basic.pdf`](./4_gencv_basic.pdf)
- **PowerPoint Version:** [`4_gencv_basic.pptx`](./4_gencv_basic.pptx)

### 💻 Practice Notebook
- **Jupyter Notebook:** [`4_vae_train_example.ipynb`](./4_vae_train_example.ipynb)

## 📝 Homework Assignment
- **Assignment Details:** [Google Drive Document](https://docs.google.com/document/d/1EQLRjF_T8aPOyiFCu2RuIYwS_s0IU-LavuqWzCw7t4c/edit?usp=sharing)

## 🎯 Key Topics Covered

### 🔢 Autoregressive Models (ARMs)
- **Pixel CNN** architecture and implementation
- **Autoregressive generation** principles
- **Conditional probability** modeling

### 🎭 Generative Adversarial Networks (GANs)
- **Problem of likelihood** in theoretical example
- **GAN optimization** challenges and solutions
- **GAN problems** Mode collapse, Vanishing gradients
- **Earth Mover's Distance** (EMD) and Wasserstein distance
- **Wasserstein GAN (WGAN)** improvements

### 🔄 Variational Autoencoders (VAE)
- **Bayesian Framework** for generative modeling
- **Latent Variable Models** and their properties
- **Variational Lower Bound (ELBO)** derivation and optimization
- **Reparameterization Trick** for gradient estimation
- **VAE architecture** and training procedures
---

*This lecture provides comprehensive coverage of the fundamental approaches to generative modeling, from theoretical foundations to practical implementations, setting the stage for understanding modern generative AI systems.*
