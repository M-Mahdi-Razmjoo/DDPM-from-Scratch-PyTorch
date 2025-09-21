# A Comprehensive Guide to Diffusion Models (DDPM) in PyTorch

This repository contains a complete educational Jupyter Notebook for learning and implementing **Denoising Diffusion Probabilistic Models (DDPM)** from scratch using the PyTorch framework. This step-by-step guide will walk you through both the theoretical concepts and the practical aspects of these powerful generative models.

## About This Project

The notebook is divided into three main parts:

1.  **Understanding the Diffusion Framework:** This section introduces the fundamental concepts of the **Forward Process** and **Reverse Process** through visual examples and code, building a solid theoretical foundation.
2.  **DDPM Implementation from Scratch:** A complete DDPM with a **U-Net** architecture is implemented in PyTorch. The model is then trained on the **MNIST dataset** to generate images of handwritten digits.
3.  **Empirical Model & Optimal Noise Prediction:** This part delves into advanced concepts from the paper **[On the Generalization of Diffusion Model](https://arxiv.org/pdf/2305.14712)**, implementing an optimal model on the **CIFAR-10 dataset**.

## Key Features

- **Conceptual Walkthrough:** Starts from the mathematical and theoretical basics of diffusion models.
- **Implementation from Scratch:** Gain a deeper understanding by building all model components in PyTorch.
- **Practical Examples:** Train models on standard datasets like MNIST and CIFAR-10.
- **Image Generation:** Use the trained model to generate new samples from pure noise.
- **Performance Evaluation:** Includes code to calculate the **Fréchet Inception Distance (FID)** to measure the quality of generated images.
- **Advanced Theoretical Concepts:** Implements theoretical findings to build an optimized model.

## References and Resources

This notebook is based on the concepts and ideas presented in the following papers and resources:

- **Denoising Diffusion Probabilistic Models** by Ho et al. [[arXiv:2006.11239]](https://arxiv.org/abs/2006.11239)
- **On the Generalization of Diffusion Model** by Chen et al. [[arXiv:2305.14712]](https://arxiv.org/pdf/2305.14712)
- **Lilian Weng's Blog Post on Diffusion Models**: [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
