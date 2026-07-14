# fashionMnist
# Fashion MNIST Image Classification using Convolutional Neural Networks (CNN)

## Project Overview

This project implements and compares two Convolutional Neural Network (CNN) models for classifying images from the Fashion MNIST dataset using PyTorch.

The aim is to evaluate the performance of a baseline CNN and an improved CNN architecture, comparing their classification accuracy, robustness to noisy images, and training time.

---

## Dataset

The project uses the **Fashion MNIST** dataset, which contains:

* 60,000 training images
* 10,000 testing images
* 10 clothing categories
* 28 × 28 grayscale images

Classes include:

* T-shirt/Top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle Boot

---

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib

---

## Project Features

* Load and preprocess the Fashion MNIST dataset
* Build a baseline CNN model
* Build an improved CNN model with Batch Normalization and Dropout
* Train both models
* Evaluate performance on clean test images
* Evaluate performance on noisy test images
* Compare model accuracy and training time
* Visualise model performance using graphs

---

## Model Architectures

### Baseline CNN

* 2 Convolutional layers
* ReLU activation
* Max Pooling
* Fully Connected output layer

### Improved CNN

* Additional convolutional layers
* Batch Normalization
* Dropout for regularisation
* Increased feature extraction capability

---

## Results

The project compares both models using:

* Test Accuracy
* Accuracy on noisy images
* Training Time

Results are displayed using bar charts for easy comparison.

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/shabab-123/fashion-mnist-project.git
```

2. Install the required libraries

```bash
pip install torch torchvision matplotlib numpy
```

3. Open the notebook

```bash
jupyter notebook fashionMnist.ipynb
```

or run it using Google Colab.

---

## Repository Structure

```
fashion-mnist-project/
│
├── fashionMnist.ipynb
├── README.md
|-- Dataset
```

---

## Future Improvements

* Train for more epochs
* Apply data augmentation
* Experiment with deeper CNN architectures
* Perform hyperparameter tuning


---

## Author

Created by Shabab Anwar Khan

GitHub: https://github.com/shabab-123

