# Latent Diffusion Model

This project implements a **Latent Diffusion Model (LDM)** for image generation using PyTorch. It is inspired by the CVPR 2022 paper *"High-Resolution Image Synthesis with Latent Diffusion Models"* by Rombach et al.

## 📘 Overview

Latent Diffusion Models work by learning to denoise data in a lower-dimensional latent space rather than pixel space, which allows for high-resolution and efficient image generation. This notebook covers:
- VAE training and latent space encoding
- U-Net based denoising model
- DDPM training pipeline in latent space
- Sampling using DDIM for faster inference
- Conditional generation and inpainting (if available)

## 🧠 Key Concepts

> Add project-specific explanation of latent encoding, noise schedule, and generation steps based on your own markdown notes.

## 🔧 Requirements

- Python 3.8+
- PyTorch
- torchvision
- numpy
- matplotlib
- tqdm
- scikit-learn
- PIL
- transformers (if using text prompts)

Install all dependencies using:
```bash
pip install -r requirements.txt
