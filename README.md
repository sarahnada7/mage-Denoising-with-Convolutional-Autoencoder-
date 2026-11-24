# Image Denoising with Convolutional Autoencoder 🖼️

A Deep Learning project that removes artificial noise from images using a **Convolutional Denoising Autoencoder (DAE)** built with TensorFlow and Keras.

## 🚀 Project Overview

The project uses the **Fashion-MNIST dataset**, containing 70,000 grayscale images (28×28 pixels) across 10 clothing categories.

Gaussian noise is artificially added to the images. A Convolutional Autoencoder is then trained to reconstruct the original clean images from their noisy versions.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Google Colab

## 🧠 Model Architecture

The Convolutional Autoencoder consists of three main parts:

1. **Encoder:** Extracts important features and reduces image dimensions using convolution and max-pooling layers.
2. **Bottleneck:** Compresses the extracted information into a smaller representation.
3. **Decoder:** Reconstructs the image using convolution and upsampling layers.

The model is trained using the Adam optimizer and Mean Squared Error (MSE) loss.

## 📊 Features

- Fashion-MNIST dataset loading and preprocessing.
- Gaussian noise generation with adjustable noise levels.
- Convolutional Denoising Autoencoder implementation.
- Model training and validation.
- Image quality evaluation using:
  - MSE (Mean Squared Error)
  - PSNR (Peak Signal-to-Noise Ratio)
  - SSIM (Structural Similarity Index)
- Visual comparison of original, noisy, and denoised images.
- Testing the model with different noise levels without retraining.

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order to load and preprocess the dataset.
3. Generate noisy images and train the autoencoder.
4. Evaluate the model using the implemented metrics.
5. Visualize the denoising results.

---

**Project Focus:** Deep Learning | Computer Vision | Image Processing | Convolutional Autoencoders
