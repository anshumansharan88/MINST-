# MNIST Digit Classification

A Machine Learning project for classifying handwritten digits from the MNIST dataset using Python and Scikit-learn.

## 📌 Project Overview

The MNIST dataset contains 70,000 images of handwritten digits (0–9). Each image contains 28 × 28 pixels, represented as 784 features.

In this project, I explored the complete Machine Learning classification workflow, including data preprocessing, feature scaling, multiclass classification, model evaluation, error analysis, and data augmentation.

## 📊 Dataset

- **Dataset:** MNIST
- **Total Images:** 70,000
- **Image Size:** 28 × 28 pixels
- **Features per Image:** 784
- **Classes:** 10 (digits 0–9)

## 🛠️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Loading
Loaded the MNIST dataset and explored its structure, dimensions, labels, and class distribution.

### 2. Data Preprocessing
- Split the dataset into training and test sets
- Prepared the input features and target labels
- Converted data into suitable numerical formats

### 3. Binary Classification

Initially explored binary classification by identifying whether an image represents a particular digit.

### 4. Multiclass Classification

Explored multiclass classification using:

- One-vs-Rest (OvR)
- One-vs-One (OvO)
- SGD Classifier
- Support Vector Machine (SVM)

### 5. Feature Scaling

Applied `StandardScaler` to standardize the input features before training the SGD classifier.

### 6. Model Evaluation

Evaluated the model using:

- Cross-validation
- Accuracy
- Confusion Matrix
- Precision
- Recall
- ROC Curve
- ROC-AUC

### 7. Error Analysis

Used the confusion matrix to identify which digits were being misclassified and analyzed the model's errors.

### 8. Data Augmentation

Expanded the training data by shifting handwritten digit images horizontally and vertically.

This helps the model become more robust to small changes in the position of handwritten digits.

## 📈 Results

The SGD Classifier achieved approximately **90% cross-validation accuracy** on the scaled training data.

The confusion matrix and other evaluation metrics were used to understand the strengths and weaknesses of the model rather than relying only on accuracy.

## 📷 Visualizations

### Data Augmentation

Examples of original and shifted MNIST images:

<!-- Add your image here -->

### Confusion Matrix

Model confusion matrix:

<!-- Add your confusion matrix screenshot here -->

## 📁 Project Structure

```text
MNIST-Digit-Classification/
│
├── MNIST.ipynb
├── README.md
├── LICENSE
└── .gitignore
