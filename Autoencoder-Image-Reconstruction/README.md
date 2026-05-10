# Autoencoder Image Reconstruction using CNN

This project implements an Autoencoder Neural Network using TensorFlow and Keras on the MNIST handwritten digit dataset. The model is trained to compress and reconstruct grayscale digit images using Convolutional Neural Networks (CNN).

---

##  Project Overview

An Autoencoder is an unsupervised deep learning model used for:

- Image Compression
- Feature Extraction
- Noise Reduction
- Image Reconstruction

This project uses:

- Encoder Network
- Decoder Network
- CNN Layers
- MNIST Dataset

The model learns to encode input images into compressed representations and then reconstruct them back to their original form.

---

##  Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

---

##  Dataset

The project uses the MNIST handwritten digit dataset provided by TensorFlow/Keras.

- 60,000 Training Images
- 10,000 Testing Images
- Image Size: 28×28 grayscale

---

##  Model Architecture

### Encoder
- Conv2D Layer
- MaxPooling2D Layer
- Conv2D Layer
- MaxPooling2D Layer

### Decoder
- Conv2D Layer
- UpSampling2D Layer
- Conv2D Layer
- UpSampling2D Layer
- Output Conv2D Layer

---

##  How to Run


### Install Required Libraries

```bash
pip install tensorflow numpy matplotlib
```

### Run the Project

```bash
python autoencoder.py
```

OR run the notebook in *Google Colab* -- reccomended.

---

##  Output

The model reconstructs handwritten digit images and displays:

- Original Images
- Reconstructed Images

The reconstructed images are generated after training the autoencoder model.

---

## Sample Result

The output displays comparison between:

| Original Image | Reconstructed Image |
|----------------|---------------------|
| MNIST Digit    | Autoencoder Output  |

---

##  Features

- Deep Learning Based Autoencoder
- CNN Architecture
- Image Encoding & Decoding
- MNIST Dataset Support
- Simple and Beginner Friendly Implementation

---

## Learning Outcomes

Through this project, concepts learned include:

- Autoencoders
- Convolutional Neural Networks
- Deep Learning
- Image Reconstruction
- TensorFlow/Keras Model Building

---

##  Author

Babulal Hawaldar  
TY CSE Student  
MIT ADT University

---

##  Future Improvements

- Denoising Autoencoder
- Variational Autoencoder (VAE)
- Color Image Reconstruction
- Custom Dataset Training
- Latent Space Visualization

---