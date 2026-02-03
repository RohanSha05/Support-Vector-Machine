# **MODULE 15: SUPPORT VECTOR MACHINE (SVM & SVR)**

## **PROJECT DESCRIPTION**
This repository contains a Google Colab notebook titled **"Module 15: Support Vector Machine"**, which provides a comprehensive overview of **Support Vector Machines (SVM)** for classification and **Support Vector Regression (SVR)** for regression tasks.

The notebook progresses from intuitive toy examples to real-world datasets, demonstrating how different kernels, hyperparameters, and model choices affect performance in both classification and regression settings.

---

## **OBJECTIVE**
The goal of this notebook is to:
- Explain the core intuition behind SVMs
- Demonstrate linear and non-linear decision boundaries
- Explore the impact of kernel functions
- Analyze the effect of key hyperparameters
- Apply SVM and SVR to real-world datasets
- Evaluate model performance using appropriate metrics

---

## **PROJECT STRUCTURE**

### **SECTION 0: SETUP & IMPORTS**
- Import essential libraries:
  - `NumPy`
  - `Pandas`
  - `Matplotlib`
  - `scikit-learn`
- Load tools for:
  - Data generation
  - Preprocessing and scaling
  - Model training
  - Evaluation metrics

---

### **SECTION 1: SIMPLE LINEAR SVM (TOY DATASET)**
- Generate a linearly separable toy dataset
- Visualize the data distribution
- Train a **Linear SVM classifier**
- Evaluate classification performance
- Plot the decision boundary and margins

---

### **SECTION 2: KERNELS — LINEAR, POLYNOMIAL, AND RBF**
- Introduce kernel functions for non-linear data
- Use the **make_moons** dataset to demonstrate:
  - Linear kernel
  - Polynomial kernel
  - Radial Basis Function (RBF) kernel
- Visualize decision boundaries
- Compare model accuracy across kernels

---

### **SECTION 3: SVM CLASSIFICATION ON REAL DATA**
- Dataset: **Breast Cancer Dataset**
  - Source: `sklearn.datasets.load_breast_cancer`
- Perform:
  - Train–test split
  - Feature scaling
- Train an **RBF SVM classifier**
- Evaluate performance using:
  - Accuracy
  - Classification report
  - Confusion matrix

---

### **SECTION 4: EFFECT OF HYPERPARAMETERS (C & GAMMA)**
- Explore the impact of:
  - **C** (regularization parameter)
  - **gamma** (kernel coefficient)
- Train multiple RBF SVM models with different parameter values
- Present results in a tabular comparison
- Analyze performance trade-offs

---

### **SECTION 5: INTRODUCTION TO SUPPORT VECTOR REGRESSION (SVR)**
- Introduce the concept of SVR
- Apply SVR to a 1D noisy regression dataset
- Visualize:
  - True values
  - SVR predictions
- Evaluate model performance using:
  - Mean Squared Error (MSE)
  - R² score

---

### **SECTION 6: SVR ON REAL DATA**
- Dataset: **Diabetes Dataset**
  - Source: `sklearn.datasets.load_diabetes`
- Perform:
  - Data splitting
  - Feature scaling
- Train an **SVR model**
- Evaluate regression performance using:
  - MSE
  - R² score

---

## **DATASETS USED**
- Toy datasets (synthetic)
- Breast Cancer Dataset
- Diabetes Dataset  
  *(All datasets provided by `scikit-learn`)*

---

## **TECHNOLOGIES USED**
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **scikit-learn**
- **Google Colab**

---

## **HOW TO RUN**
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Run all cells sequentially.
3. All datasets are loaded directly from `scikit-learn`.

---

## **LEARNING OUTCOMES**
By completing this notebook, you will understand:
- How SVMs construct decision boundaries
- The role of kernels in handling non-linear data
- How hyperparameters affect SVM performance
- The difference between SVM classification and SVR
- How to evaluate SVM and SVR models on real datasets
