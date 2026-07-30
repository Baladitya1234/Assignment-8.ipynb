# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## Objective

The objective of this project is to develop an Artificial Neural Network (ANN) using TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset. The project demonstrates the complete deep learning workflow, including data preprocessing, model building, training, evaluation, and performance visualization.

---

## Dataset

**MNIST Handwritten Digits Dataset**

Kaggle Link:
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

Dataset Description:
- Training Samples: 60,000
- Testing Samples: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10 (Digits 0–9)

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

---

## Methodology

1. Load the MNIST dataset using Pandas.
2. Display and understand the dataset.
3. Check for missing values.
4. Separate input features and target labels.
5. Normalize pixel values to the range 0–1.
6. Split the dataset into 80% training and 20% testing.
7. Apply One-Hot Encoding to target labels.
8. Build an Artificial Neural Network using TensorFlow/Keras.
9. Train the model for 10 epochs.
10. Evaluate the model using accuracy, confusion matrix, and classification report.
11. Visualize training accuracy and loss using graphs.

---

## Model Architecture

Input Layer:
- 784 Input Features

Hidden Layer 1:
- 128 Neurons
- ReLU Activation

Hidden Layer 2:
- 64 Neurons
- ReLU Activation

Output Layer:
- 10 Neurons
- Softmax Activation

Optimizer:
- Adam

Loss Function:
- Categorical Crossentropy

Evaluation Metric:
- Accuracy

Epochs:
- 10

Batch Size:
- 32

---

## Results

- Successfully trained an ANN model for handwritten digit recognition.
- Achieved high classification accuracy on the test dataset (approximately 97–99%).
- Generated Confusion Matrix and Classification Report.
- Visualized Accuracy vs Epoch and Loss vs Epoch graphs.

---

## Conclusion
The Artificial Neural Network (ANN) was successfully implemented to classify handwritten digits from the MNIST dataset with high accuracy. The preprocessing steps, including normalization and one-hot encoding, improved the model’s learning performance. The two hidden layers enabled the network to learn complex features from the pixel values, resulting in accurate digit classification. Compared with traditional machine learning algorithms, deep learning can automatically extract important features from raw data without manual feature engineering, making it highly suitable for image recognition tasks. However, ANN models require a large amount of training data and computational resources, which increases training time. Overall, the model demonstrated excellent performance and highlighted the effectiveness of deep learning techniques for handwritten digit recognition and real-world applications such as optical character recognition (OCR) and postal code processing.
**Course:** B.Tech – Computer Science and Engineering

**Assignment:** Assignment-8 – Handwritten Digit Recognition using ANN
