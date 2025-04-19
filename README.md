[Generative AI _NVIDIA.pdf](https://github.com/user-attachments/files/19821207/Generative.AI._NVIDIA.pdf)# 🧠 Generative AI with Diffusion Models - NVIDIA Assessment (MNIST)

This project was completed as part of the **"Generative AI with Diffusion Models"** course by **NVIDIA**. The main objective is to build a **diffusion-based generative model** capable of creating realistic handwritten digits (0–9) using the **MNIST dataset**.

---

## 🎯 Assessment Goal

> Train a generative model that can produce images of handwritten digits, which are recognized with at least **95% accuracy** by a **pre-trained MNIST classifier** (accuracy > 99%).

The model successfully achieved a **96.0% final accuracy**, meeting the certification requirement:
![image](https://github.com/user-attachments/assets/0b75082d-f700-4cd4-91c1-6230a6a8af4b)


✅ **NVIDIA certificate earned successfully!**
[Uploading Generative AI _NVIDIA.pdf…]()

---

## 🧠 Technical Overview

The model uses a **conditional U-Net architecture** with **classifier-free guidance**. It learns to denoise images step-by-step through a reverse diffusion process.

### 🔧 Key Components

- **Dataset**: MNIST (28x28 grayscale images)
- **U-Net Network**: Handles time-step and label conditioning
- **Diffusion Process**: Forward noise addition and reverse denoising
- **Conditioning**: Digit label is encoded and injected at each step
- **Guidance**: Uses classifier-free guidance to control generation
---
🎉 Thanks to NVIDIA for the opportunity to explore cutting-edge generative AI techniques. Proud to have earned the certificate in Generative AI with Diffusion Models! 🧠✨



