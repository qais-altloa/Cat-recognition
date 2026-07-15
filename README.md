# Logistic Regression with a Neural Network Mindset

## Overview

This project implements **Logistic Regression** from scratch using **Python** and **NumPy**, following the concepts taught in **Andrew Ng's Deep Learning Specialization**.

The objective is to build a binary image classifier capable of distinguishing between cats and non-cats without relying on machine learning libraries such as Scikit-learn.

The implementation covers:
- Forward Propagation
- Cost Computation
- Backward Propagation
- Gradient Descent Optimization
- Prediction
- Model Evaluation

---

## Features

- Logistic Regression implemented from scratch
- Sigmoid activation function
- Binary Cross-Entropy Loss
- Forward and Backward Propagation
- Gradient Descent Optimization
- Prediction on unseen data
- Training and testing accuracy evaluation
- Efficient vectorized implementation using NumPy

---

## Technologies Used

- Python 3
- NumPy
- Matplotlib
- h5py

---

## Project Structure

```text
.
├── logistic_regression_with_a_neural_network_mindset.py
├── datasets/
│   ├── train_catvnoncat.h5
│   └── test_catvnoncat.h5
└── README.md
```

---

## Learning Objectives

Through this project, I learned how to:

- Build Logistic Regression from scratch
- Apply the Sigmoid activation function
- Compute Binary Cross-Entropy loss
- Implement Forward and Backward Propagation
- Optimize parameters using Gradient Descent
- Evaluate model performance
- Use vectorized NumPy operations for efficient computation

---

## Results

| Metric | Accuracy |
|---------|----------|
| Training Accuracy | ~99% |
| Test Accuracy | ~70% |

> The difference between training and test accuracy demonstrates the importance of model generalization and highlights potential overfitting on small datasets.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/logistic-regression-neural-network.git
```

Navigate to the project folder:

```bash
cd logistic-regression-neural-network
```

Install the required libraries:

```bash
pip install numpy matplotlib h5py
```

Run the project:

```bash
python logistic_regression_with_a_neural_network_mindset.py
```

---

## Course Reference

This project was completed while studying the **Deep Learning Specialization** by **Prof. Andrew Ng**.

It is intended for **educational purposes** and demonstrates the implementation of Logistic Regression from first principles.

---

## Future Improvements

- Add L2 Regularization
- Experiment with different learning rates
- Visualize the decision boundary
- Train on additional datasets
- Compare with Scikit-learn's Logistic Regression implementation

---

## Author

**Qais Altloa**

Computer Science Student | Artificial Intelligence Enthusiast

Passionate about Machine Learning, Deep Learning, Data Science, and AI application development.