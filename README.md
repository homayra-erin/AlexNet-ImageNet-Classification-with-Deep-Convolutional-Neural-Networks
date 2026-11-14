
# 🧠 AlexNet: Deep Learning for Image Classification

<p align="center">
  <img src="figures/alexnet_architecture.png" width="750" alt="AlexNet Architecture">
</p>

<p align="center">
  <b>A Deep Learning Implementation of AlexNet CNN Architecture</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-orange">
  <img src="https://img.shields.io/badge/Framework-PyTorch-red?logo=pytorch">
  <img src="https://img.shields.io/badge/Project-Image%20Classification-success">
</p>

---

## 📌 Overview

This project explores the implementation of **AlexNet**, 
a pioneering Convolutional Neural Network (CNN) architecture 
introduced by Alex Krizhevsky, Ilya Sutskever, and 
Geoffrey Hinton in 2012.

The primary goal is to understand how deep convolutional 
neural networks extract meaningful features from images 
and perform image classification tasks.

The project covers the complete deep learning workflow, 
from dataset exploration and preprocessing to model 
implementation, training, and performance evaluation.

## 🎯 Project Objectives

- Understand the fundamental concepts of CNNs.
- Explore the architecture and working principles of AlexNet.
- Implement AlexNet using Python and PyTorch.
- Perform image preprocessing and augmentation.
- Train the model for image classification.
- Evaluate model performance using standard classification metrics.
- Visualize and analyze experimental results.

## 🏗️ AlexNet Architecture

AlexNet is a deep CNN architecture consisting of:

- **5 Convolutional Layers** – Extract hierarchical image features.
- **ReLU Activation** – Introduces non-linearity.
- **Max Pooling** – Reduces spatial dimensions.
- **3 Fully Connected Layers** – Perform classification.
- **Dropout** – Helps reduce overfitting.
- **Softmax** – Produces class probabilities.

## 🔄 Project Workflow

```text
Dataset Collection
       |
       ▼
Data Exploration
       |
       ▼
Data Preprocessing
       |
       ▼
AlexNet Implementation
       |
       ▼
Model Training
       |
       ▼
Model Evaluation
       |
       ▼
Performance Visualization
       |
       ▼
Final Analysis
```

## 📂 Repository Structure

```text
AlexNet-Deep-Learning/
│
├── data/
├── notebooks/
├── src/
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   └── dataset.py
│
├── figures/
├── results/
├── docs/
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## 🛠️ Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| NumPy | Numerical Computation |
| Pandas | Data Analysis |
| Matplotlib | Data Visualization |
| Scikit-learn | Model Evaluation |
| Jupyter Notebook | Experimentation |

## 📊 Experimental Results

Model performance will be evaluated using:

| Evaluation Metric | Description |
|-------------------|-------------|
| Accuracy | Overall classification performance |
| Precision | Correct positive predictions |
| Recall | Ability to identify actual positives |
| F1-Score | Balance between precision and recall |
| Confusion Matrix | Class-wise prediction analysis |

### 📈 Visualizations

The following visualizations will be included:

- Training and Validation Accuracy
- Training and Validation Loss
- Confusion Matrix
- Actual vs Predicted Images

> Note: Experimental results and visualizations will be 
> updated after completing model training and evaluation.

## ⚙️ Installation & Usage

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/AlexNet-Deep-Learning.git
```

**2. Navigate to the project directory**

```bash
cd AlexNet-Deep-Learning
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the notebooks**

Open Jupyter Notebook and explore the notebooks 
inside the `notebooks/` directory.

## 🚀 Future Improvements

- Hyperparameter optimization
- Advanced image augmentation
- Transfer learning experiments
- Comparison with other CNN architectures
- Model efficiency and performance analysis

## 📚 References

1. Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012).
   ImageNet Classification with Deep Convolutional Neural Networks.
   Advances in Neural Information Processing Systems (NeurIPS).

## 👩‍💻 Author

**Homayra Erin**

- GitHub: [homayra-erin](https://github.com/homayra-erin)

---

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>

<p align="center">
  <i>Learning • Experimenting • Building with Deep Learning</i>
</p>
