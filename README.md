# CNN Autoencoder using Fashion MNIST Dataset

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN) based Autoencoder** using the Fashion MNIST dataset. The model learns to compress grayscale clothing images into a lower-dimensional representation and reconstruct them with minimal loss.

It demonstrates **image compression, feature extraction, and reconstruction** using deep learning.

---

## 🎯 Objective

* To build a CNN-based Autoencoder for image data
* To compress Fashion MNIST images into a latent space
* To reconstruct images from compressed representation
* To analyze reconstruction quality

---

## 🧠 What is an Autoencoder?

An Autoencoder is an unsupervised neural network that learns to encode input data into a compressed form and then decode it back to the original.

It consists of:

* **Encoder** → Extracts features and reduces dimensionality
* **Decoder** → Reconstructs the original image

---

## 📊 Dataset

* **Fashion MNIST dataset**
* 70,000 grayscale images of clothing items
* Image size: 28 × 28 pixels
* Categories include shirts, shoes, bags, etc.

Fashion MNIST is a more complex alternative to MNIST, used for image classification and reconstruction tasks.

---

## 🏗️ Model Architecture

The model uses convolutional layers for better image feature extraction:

### Encoder:

* Conv2D layers extract spatial features
* Downsampling reduces image dimensions

### Decoder:

* Upsampling / Conv2D layers reconstruct the image
* Restores original 28×28 dimensions

---

## ⚙️ Algorithm

1. Import required libraries
2. Load Fashion MNIST dataset
3. Normalize pixel values (0–1)
4. Reshape images for CNN input
5. Build encoder using Conv2D layers
6. Build decoder using Conv2D / UpSampling layers
7. Combine into Autoencoder model
8. Compile using Mean Squared Error (MSE)
9. Train model using dataset
10. Generate reconstructed images
11. Visualize original vs reconstructed output

---

## 📈 Results

* Model successfully learns compressed representations
* Reconstructed images retain key visual features
* CNN improves performance compared to dense models

---

## 📷 Output Visualizations

The notebook includes:

* Sample Fashion MNIST images
* Model summary
* Training loss graph
* Original vs reconstructed images

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 🚀 How to Run

1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells sequentially
4. Observe training and reconstruction results

---

## 🔗 GitHub Repository

(Add your repository link here)

---

## 👩‍💻 Author

**Charvi B**

---

## 📌 Notes

* CNN Autoencoders are better suited for image data due to spatial feature extraction
* This model can be extended for applications like image denoising and compression

---
