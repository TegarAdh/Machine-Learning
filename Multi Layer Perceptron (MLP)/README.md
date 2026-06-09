# 🌸 MLP Activation Function Comparison on Iris Dataset

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success)

Comparative Analysis of Multi-Layer Perceptron (MLP) Performance Using Different Activation Functions on the Iris Dataset

</div>

---

## 📖 Overview

Activation functions play a crucial role in the learning capability of neural networks. This project investigates how different activation functions affect the performance of a Multi-Layer Perceptron (MLP) classifier on the Iris dataset.

Three activation functions are compared:

- 🔵 Sigmoid (Logistic)
- 🟢 Tanh
- 🔴 ReLU

The study evaluates model performance using multiple classification metrics, cross-validation, and training convergence analysis.

---

## 🎯 Objectives

- Compare the performance of different activation functions in MLP.
- Analyze model stability using cross-validation.
- Evaluate classification effectiveness using standard metrics.
- Visualize training convergence through loss curves.

---

## 📊 Dataset

The project uses the famous Iris Flower Dataset.

| Feature | Description |
|----------|------------|
| Sepal Length | Length of sepal |
| Sepal Width | Width of sepal |
| Petal Length | Length of petal |
| Petal Width | Width of petal |

### Target Classes

| Class |
|---------|
| Iris Setosa |
| Iris Versicolor |
| Iris Virginica |

**Dataset Size:** 150 Samples

---

## ⚙️ Methodology

### Data Preprocessing

- Data Loading
- Data Cleaning
- Label Encoding
- Feature Scaling
- Train-Test Split (80:20)

### Model Configuration

```python
MLPClassifier(
    hidden_layer_sizes=(100, 50),
    activation=<activation_function>,
    solver='adam',
    max_iter=2000,
    random_state=42
)
```

### Activation Functions Compared

| Model | Activation |
|---------|-----------|
| MLP-Sigmoid | Logistic |
| MLP-Tanh | Tanh |
| MLP-ReLU | ReLU |

---

## 📈 Evaluation Metrics

The following metrics are used:

- Accuracy
- Precision
- Recall
- F1-Score
- Cross Validation Score
- Training Time
- Loss Curve Analysis

---

## 📉 Visualization Outputs

### Performance Comparison

- Accuracy Comparison
- Precision Comparison
- Recall Comparison
- F1-Score Comparison

### Model Diagnostics

- Confusion Matrix
- Cross Validation Boxplot
- Training Loss Curve

---

## 🏗️ Project Workflow

```text
Iris Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
MLP Training
 ├── Sigmoid
 ├── Tanh
 └── ReLU
      │
      ▼
Model Evaluation
      │
      ▼
Performance Comparison
```

---

## 📂 Repository Structure

```text
MLP-Iris-Comparison
│
├── Iris.csv
├── mlp_iris_comparison.ipynb
├── README.md
│
├── outputs
│   ├── confusion_matrix.png
│   ├── loss_curve.png
│   └── performance_comparison.png
│
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/TegarAdh/Machine-Learning.git
```

Move into the project directory:

```bash
cd Multi Layer Perceptron (MLP)
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
mlp_iris_comparison.ipynb
```

Run all cells to reproduce the experiment and generate visualizations.

---

## 📋 Results Summary

This project provides insights into:

✅ Classification performance of each activation function

✅ Generalization ability through cross-validation

✅ Convergence behavior during training

✅ Comparative strengths and weaknesses of Sigmoid, Tanh, and ReLU

---

## 🔬 Future Improvements

- Hyperparameter Optimization using GridSearchCV
- Additional Activation Functions (LeakyReLU, ELU, GELU)
- Comparison with Deep Neural Networks
- Performance Evaluation on Larger Datasets
- Integration with TensorFlow/PyTorch

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |

---

## 👨‍💻 Author

**Tegar Adhi Nugraha Christ During**
GitHub: https://github.com/TegarAdh

---

## ⭐ Support

If you find this project useful, consider giving it a star ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.

