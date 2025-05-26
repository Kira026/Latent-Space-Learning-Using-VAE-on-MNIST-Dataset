# Latent Space Learning Using VAE on MNIST Dataset

This project uses a Variational Autoencoder (VAE) to learn a latent space representation of handwritten digits from the MNIST dataset. The model is implemented using PyTorch and demonstrates both reconstruction and generation capabilities.

## 📊 Dataset

- **MNIST**: A benchmark dataset of 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels.

## 🧠 Model Architecture

- **Encoder**: Compresses the input image into a latent vector.
- **Latent Space**: Regularized using KL divergence to ensure a continuous and structured space.
- **Decoder**: Reconstructs the image from the latent vector.

## 🔧 Dependencies

- Python 3.x
- torch
- torchvision
- matplotlib
- numpy

### Install Requirements

```bash
pip install torch torchvision matplotlib numpy
