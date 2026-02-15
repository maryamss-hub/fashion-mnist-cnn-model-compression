# Lightweight CNN for Fashion-MNIST Classification (Model Compression)

## Overview

This project reproduces and extends the CNN-3-128 model for Fashion-MNIST image classification and proposes a lightweight architecture using depthwise-separable convolutions and Global Average Pooling.

The modified model reduces parameters by **91.3%** while maintaining **98.98% accuracy**, demonstrating an efficient deep learning design.

---

## Objectives

• Reproduce CNN-3-128 baseline model
• Compare with classical machine learning models
• Design lightweight CNN architecture
• Reduce model size while maintaining accuracy

---

## Dataset

Fashion-MNIST dataset

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28
* 10 clothing categories

Examples include:

* T-shirt
* Shoe
* Coat
* Bag

---

## Models Implemented

### Classical Machine Learning

* Logistic Regression
* Random Forest
* Decision Tree
* Support Vector Machine
* KNN
* Naive Bayes
* MLP

Accuracy range:

59% – 89%

---

### Deep Learning Models

## Baseline CNN-3-128

Architecture:

* 3 Convolution layers
* Dense classifier

Parameters:

2,067,850

Accuracy:

99.67%

---

## Proposed Lightweight CNN (Our Model)

Modifications:

* Depthwise-Separable Convolution
* Global Average Pooling

Parameters:

178,968

Accuracy:

98.98%

Parameter reduction:

91.3%

---

## Results Comparison

| Model           | Parameters | Accuracy |
| --------------- | ---------- | -------- |
| CNN-3-128       | 2.06M      | 99.67%   |
| Lightweight CNN | 0.18M      | 98.98%   |

---

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* NumPy
* Deep Learning

---

## Key Concepts Demonstrated

* Convolutional Neural Networks
* Model Compression
* Efficient Deep Learning
* Image Classification
* Depthwise Separable Convolution

---

## Applications

* Mobile AI
* Edge Computing
* Embedded Systems
* Efficient Deep Learning deployment

---

## Repository Contents

```
paper.pdf
README.md
```

---

## Skills Demonstrated

* Deep Learning
* CNN Architecture Design
* Model Optimization
* Python Programming
* Machine Learning Research

---

## Authors

Maryam Khalid
BS Data Science
FAST National University Islamabad
