# 🔢 Handwritten Digit Recognition using MNIST

A simple **Deep Learning project** that recognizes handwritten digits from **0 to 9** using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

## 📌 Overview

This project uses the **MNIST dataset** to train a neural network that identifies handwritten digits. The model learns patterns from images and predicts digits accurately.

## ✨ Features

- 🔢 Recognizes handwritten digits (0–9)
- 🧠 Uses an Artificial Neural Network (ANN)
- 📊 Trained on the MNIST dataset
- 📈 Displays training and validation accuracy and loss graphs
- 💾 Saves the trained model for future use

## 📂 Dataset

The **MNIST dataset** contains:

- **60,000** training images
- **10,000** testing images
- **28 × 28** grayscale images
- **10 classes** (digits 0–9)

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Matplotlib**

## 🧠 Model Architecture

The model uses a simple neural network:

```text
Input Image (28 × 28)
         ↓
     Flatten Layer
         ↓
 Dense (512, ReLU)
         ↓
    Dropout (0.2)
         ↓
 Dense (10, Softmax)
         ↓
  Predicted Digit
```

**Training Configuration:**

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Validation Split: 20%

## 🚀 How to Run

**1. Clone the repository**

```bash
git clone https://github.com/KarthikJ-2008/HandWritten-digits-classification-using-MNIST.git
```

**2. Install required libraries**

```bash
pip install tensorflow matplotlib
```

**3. Run the project**

Open `MNIST.ipynb` in Jupyter Notebook or Google Colab and run all cells.

## 📊 Model Evaluation

The model is evaluated using the MNIST test dataset.

- Training and validation accuracy
- Training and validation loss
- Test accuracy and loss

The trained model is saved as **`MNIST_model.keras`**.

## ⭐ Support

If you find this project useful, consider giving the repository a **⭐ Star** on GitHub!

---
