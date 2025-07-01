# MNIST Digit Classifier using MLP (TensorFlow & Keras)

This project implements a simple **Multilayer Perceptron (MLP)** using **TensorFlow** and **Keras** to classify handwritten digits from the **MNIST dataset**. It demonstrates how machine learning can accurately identify digits written by hand.

---

## ✍️ Real-World Use Case: Handwritten Digit Recognition

This model can serve as the foundation for applications that require **automated recognition of handwritten numbers**, such as:

- 📬 **Postal Code Recognition** (in mail sorting systems)
- 🏦 **Bank Cheque Digitization** (reading handwritten amounts)
- 📄 **Form Scanning & Digitization** (automatically reading filled-in digits)
- 🔢 **Handwriting Analysis Tools**
  
By training on the MNIST dataset — a large database of 70,000 handwritten digits — the model learns to generalize to various writing styles.

---

## 🧠 What is Machine Learning?

**Machine Learning (ML)** is a subfield of artificial intelligence where computers learn from data instead of being explicitly programmed. This project uses **supervised learning**, where the model learns from labeled digit images.

---

## 📚 Dataset: MNIST

- 60,000 training images
- 10,000 test images
- Each image: grayscale, 28x28 pixels
- Labels: Digits from 0 to 9

---

## 🚀 Model Architecture

- **Input Layer**: 784 neurons (flattened from 28x28 image)
- **Hidden Layer 1**: 128 neurons, ReLU activation
- **Hidden Layer 2**: 64 neurons, ReLU activation
- **Output Layer**: 10 neurons, Softmax activation

---

## 📊 Sample Output

- **Test Accuracy:** ~97–98%
- **Example Image Display:** One digit from the test set is shown using `matplotlib`
