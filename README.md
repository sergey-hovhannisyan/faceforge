# 🎨 FaceForge: Image Generation with WGAN-GP

## 📖 Overview

FaceForge generates realistic human face images using the CelebA dataset. It employs a **Wasserstein Generative Adversarial Network with Gradient Penalty (WGAN-GP)** for stable and high-quality image generation.

## 📊 Visualization

![Training Progress](gifs/training_progress.gif)

## 🌟 Features

- 📸 High-resolution image generation (128x128)
- 🗃️ Utilizes the CelebA dataset
- 🛠️ WGAN-GP for robust training

## 🚀 Training

1. Ensure CelebA dataset paths are set in `paths.yaml`.
2. Start training with the provided training script.

## 🧩 Usage

Load the saved model to generate new images after training. Refer to the usage section in the training script for detailed instructions.

## 🗂️ Directory Structure

- `models/`: Trained model checkpoints
- `imgs/`: Generated images during training
- `gifs/`: Training progress GIF

Enjoy exploring face generation with FaceForge! 🎉
