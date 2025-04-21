<h1 align="center">CNN-Project</h1>


# 🧥 Fashion-MNIST Image Classification with PyTorch

Welcome! In this project, we’ll build a Convolutional Neural Network (CNN) using PyTorch to classify clothing images from the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). Whether you're just getting into deep learning or brushing up on PyTorch, this project is a hands-on way to see how it all fits together.

---

## 📌 Overview

Fashion-MNIST is a dataset of Zalando's article images—consisting of 28x28 grayscale images of 10 fashion categories, with 60,000 training images and 10,000 test images.

In this notebook, we’ll walk through how to:

- Load and preprocess the Fashion MNIST dataset
- Create a custom `Dataset` class
- Build a CNN model using PyTorch
- Train and evaluate the model
- Visualize the results

---

## 🛠️ Technologies Used

Here are the main tools and libraries we’ll be working with:

- Python
- PyTorch
- torchvision
- matplotlib
- PIL (Python Imaging Library)

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/oussamale/CNN-Project.git
   cd CNN-Project
   ```

2. **Install dependencies:**

   ```bash
   pip install torch torchvision matplotlib
   ```

3. **Launch the notebook:**

   ```bash
   jupyter notebook "Fashion-MNIST Project.ipynb"
   ```

---

## 📊 Model Architecture

The CNN model includes:

- Convolutional layers with ReLU activation
- Max pooling layers
- Fully connected layers
- Dropout regularization

We’ll watch the model learn and improve as we train it over several epochs.

---

## 📈 Results

Once the training’s done, we’ll evaluate our model on the test set. We’ll look at accuracy, plot the loss curve, and visualize some predictions to understand how well the model performs.

---


> Made with ❤️ using PyTorch
