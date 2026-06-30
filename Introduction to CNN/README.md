# 🧠 Introduction to CNN: Garbage Classification with ResNet50

> A practical deep learning project that introduces the fundamentals of **Convolutional Neural Networks (CNN)** and extends them to **Transfer Learning** using **ResNet50** for automatic garbage classification.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras">
  <img src="https://img.shields.io/badge/Model-ResNet50-success">
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab">
</p>

---

# 📖 Project Overview

This notebook is part of the **Introduction to Convolutional Neural Networks (CNN)** learning series in the **Machine-Learning** repository.

The project begins by introducing the core concepts of CNNs, including how convolution, activation functions, pooling layers, and fully connected layers work together to extract visual features from images. After understanding these fundamentals, the notebook demonstrates how modern computer vision systems can achieve higher accuracy by applying **Transfer Learning** with a pre-trained **ResNet50** model.

To reinforce these concepts, the project implements a real-world application: **automatic garbage classification**. The model learns to recognize different categories of waste, illustrating how deep learning can support intelligent waste sorting and recycling systems.

Rather than building a CNN entirely from scratch, this notebook highlights how pre-trained models can significantly improve performance while reducing training time and computational requirements.

---

# 🎯 Learning Objectives

After completing this notebook, you will be able to:

* Understand the fundamental architecture of Convolutional Neural Networks.
* Explain how convolution and pooling layers extract image features.
* Understand the motivation behind Transfer Learning.
* Implement image classification using ResNet50.
* Prepare image datasets for deep learning.
* Apply data augmentation techniques.
* Train and validate a deep learning model.
* Evaluate model performance using common classification metrics.
* Predict the class of previously unseen images.

---

# 🧠 Learning Progression

```text
Computer Vision
        │
        ▼
Introduction to CNN
        │
        ├── Image Representation
        ├── Convolution
        ├── ReLU
        ├── Max Pooling
        ├── Flatten
        └── Fully Connected Layer
                │
                ▼
      Traditional CNN Model
                │
                ▼
      Transfer Learning
                │
                ▼
         ResNet50
                │
                ▼
 Garbage Image Classification
```

This progression helps bridge theoretical knowledge with practical implementation, making the notebook suitable for beginners transitioning into real-world deep learning projects.

---

# 🏗 Model Architecture

```text
Input Image (224 × 224 × 3)
            │
            ▼
Data Augmentation
            │
            ▼
Image Preprocessing
            │
            ▼
Pre-trained ResNet50
(ImageNet Weights)
            │
            ▼
Global Average Pooling
            │
            ▼
Dropout
            │
            ▼
Dense Layer
            │
            ▼
Softmax Classifier
            │
            ▼
Predicted Garbage Class
```

---

# 📂 Project Structure

```text
Introduction to CNN/
│
├── trash_split/
│   ├── train/
│   ├── validation/
│   └── test/
├── dataset/TrashType_Image_Dataset/
│   ├── cardboard/
│   ├── glass/
│   ├── metal/
│   ├── paper/
│   ├── plastic/
│   └── trash/
├── Garbage_Classification_CNN--ResNet50.ipynb
├── best_resnet50_quant.tflite
└── README.md
```

---

# 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

# 📦 Dataset

The project uses an image dataset containing multiple categories of household waste. Each category is stored in its own directory, allowing Keras data generators to automatically create labels.

Typical categories include:

* Cardboard
* Glass
* Metal
* Paper
* Plastic
* Trash

---

# 🚀 Running the Project

Clone the repository:

```bash
git clone https://github.com/TegarAdh/Machine-Learning.git
```

Move into the project directory:

```bash
cd Machine-Learning/Introduction\ to\ CNN
```

Open:

```text
Garbage_Classification_CNN--ResNet50.ipynb
```

Run the notebook sequentially to reproduce the training process.

---

# 🔄 Workflow

```text
Image Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
Transfer Learning
(ResNet50)
      │
      ▼
Model Training
      │
      ▼
Validation
      │
      ▼
Evaluation
      │
      ▼
Prediction
```

---

# 📊 Model Evaluation

The notebook evaluates model performance using several common metrics:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

Training curves are also visualized to monitor convergence and detect potential overfitting.

---

# 💡 Key Concepts Covered

* Deep Learning
* Computer Vision
* Artificial Neural Networks (ANN)
* Convolutional Neural Networks (CNN)
* Feature Extraction
* Image Classification
* Transfer Learning
* Residual Networks (ResNet)
* Data Augmentation
* Model Evaluation

---

# 🌱 Future Improvements

Potential enhancements for this project include:

* Fine-tuning additional ResNet50 layers
* Hyperparameter optimization
* Learning rate scheduling
* Early stopping
* Batch normalization
* Class imbalance handling
* EfficientNet implementation
* MobileNet implementation
* TensorFlow Lite deployment
* Real-time webcam classification
* Edge AI deployment on embedded devices

---

# 🎓 Conclusion

This project serves as a bridge between learning the **fundamental principles of Convolutional Neural Networks** and applying **state-of-the-art Transfer Learning techniques** to solve a practical computer vision problem.

By combining CNN theory with the power of ResNet50, the notebook demonstrates how modern deep learning models can efficiently classify garbage images with improved accuracy while requiring significantly less training time than training a deep network from scratch.

Whether you are beginning your journey in deep learning or exploring transfer learning for computer vision applications, this notebook provides a structured and practical learning experience.

---

# 👨‍💻 Author

**Tegar Adh**

Machine Learning & Robotics Enthusiast

GitHub: https://github.com/TegarAdh

---

## ⭐ Support

If you find this project helpful for learning CNN or Transfer Learning, consider giving this repository a **Star**. Your support motivates future educational and open-source projects.

