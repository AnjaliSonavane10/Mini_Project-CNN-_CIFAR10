# CIFAR-10 Image Classification Using CNN

## 📌 Project Overview

This mini-project focuses on building and training a **Convolutional Neural Network (CNN)** for image classification using the **CIFAR-10 dataset**.

The main objective of this project was to understand the basic workflow of a CNN-based image classification model, including dataset loading, preprocessing, model creation, training, and evaluation.

## 📊 Dataset

The **CIFAR-10 dataset** contains 60,000 RGB images of size **32 × 32 pixels**, divided into 10 different classes.

* 50,000 training images
* 10,000 testing images
* 10 image classes

### Classes

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## 🧠 Model

A Convolutional Neural Network was implemented using **PyTorch**.

The model uses:

* Convolutional layers for extracting image features
* ReLU activation functions
* Pooling layers for reducing spatial dimensions
* Fully connected layers for classification
* Output layer with 10 classes

### Model Workflow

```text
CIFAR-10 Dataset
       ↓
Data Preprocessing
       ↓
CNN Model
       ↓
Training
       ↓
Loss Calculation
       ↓
Backpropagation & Optimization
       ↓
Testing
       ↓
Accuracy Evaluation
```

## ⚙️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Jupyter Notebook

## 🔄 Project Steps

### 1. Dataset Loading

The CIFAR-10 training and testing datasets were loaded using `torchvision`.

### 2. Data Preprocessing

The images were converted into tensors and normalized before being provided to the CNN.

### 3. CNN Model Creation

A CNN architecture was created using PyTorch's `nn.Module` and different neural network layers.

### 4. Model Training

The CNN was trained on the CIFAR-10 training dataset.

The training process involved:

* Forward propagation
* Calculating the loss
* Backpropagation
* Updating model parameters using an optimizer

### 5. Model Evaluation

After training, the model was evaluated using the **CIFAR-10 test dataset**.

The predictions were compared with the actual labels to calculate the model's classification accuracy.

## 📈 Results

The trained CNN was evaluated on the CIFAR-10 test dataset.

**Test Accuracy:** `XX.XX%`

> Replace `XX.XX%` with the accuracy achieved by your model.

