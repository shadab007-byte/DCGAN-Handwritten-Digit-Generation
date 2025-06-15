# DCGAN-Handwritten-Digit-Generation

# 🧠 DCGAN-Handwritten-Digit-Generation

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate realistic images of handwritten digits (0-9) using the MNIST dataset. The model is trained using TensorFlow and visualized in Google Colab.

## 📌 Project Highlights

- Uses DCGAN architecture: a Generator and Discriminator trained adversarially.
- Generator learns to create fake digit images from random noise.
- Discriminator learns to distinguish real images from fake ones.
- Periodic visualization of generated samples using a fixed noise seed.
- Suitable for beginners exploring GANs in computer vision.

## 📁 Files

- `Generate_handwritten_digit_images_DCGAN.ipynb`  
  → Main notebook with model training, loss visualization, and image generation.



## 📦 Dependencies

Ensure the following libraries are installed:

```bash
tensorflow
numpy
matplotlib
