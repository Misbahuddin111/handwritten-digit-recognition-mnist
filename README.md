

# MNIST Handwritten Digit Classification with Neural Networks

A simple yet effective implementation of a feedforward neural network to classify handwritten digits from the MNIST dataset using TensorFlow/Keras.

## 📊 Project Overview

This project demonstrates a basic neural network architecture for image classification on the MNIST dataset, achieving **96.31% test accuracy**.

## 🏗️ Model Architecture

- **Input Layer**: 784 neurons (28×28 pixel images flattened)
- **Hidden Layer 1**: 32 neurons with ReLU activation
- **Hidden Layer 2**: 64 neurons with ReLU activation  
- **Output Layer**: 10 neurons with Softmax activation (digit classes 0-9)

**Total Parameters**: 27,882

## 🔧 Data Processing

- Dataset: MNIST (60,000 training, 10,000 test images)
- Data split: 80% training, 20% validation
- Preprocessing:
  - Images flattened to 1D vectors
  - Feature scaling using StandardScaler

## 🎯 Training Configuration

- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy  
- **Batch Size**: 100
- **Epochs**: 10
- **Validation Split**: 20%

## 📈 Performance Metrics

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0 | 0.96 | 0.99 | 0.98 |
| 1 | 0.99 | 0.99 | 0.99 |
| 2 | 0.95 | 0.97 | 0.96 |
| 3 | 0.95 | 0.96 | 0.96 |
| 4 | 0.97 | 0.96 | 0.97 |
| 5 | 0.96 | 0.94 | 0.95 |
| 6 | 0.96 | 0.97 | 0.97 |
| 7 | 0.96 | 0.96 | 0.96 |
| 8 | 0.95 | 0.93 | 0.94 |
| 9 | 0.97 | 0.95 | 0.96 |

**Overall Accuracy**: 96.31%

## 🚀 Key Features

- Simple, interpretable architecture
- Efficient data preprocessing pipeline
- Clear performance metrics and classification report
- Reproducible results with random seed (42)

## 📚 Dependencies

- Python 3.x
- TensorFlow/Keras
- NumPy
- Pandas
- Scikit-learn

## 💡 Learning Outcomes

This project serves as a foundational implementation of neural networks for image classification, demonstrating:
- Basic neural network architecture design
- Data preprocessing techniques
- Model training and evaluation
- Performance analysis using classification metrics

---
