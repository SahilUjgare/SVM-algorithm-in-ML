# 🧠 Support Vector Machine (SVM) Algorithm in Python

This repository demonstrates how to implement and understand the **Support Vector Machine (SVM)** algorithm using Python.  
SVM is a powerful supervised learning model used for **classification** and **regression** tasks, known for its effectiveness in high-dimensional spaces.

---

## 📘 Project Overview

This notebook covers:
- Introduction to the **Support Vector Machine (SVM)** algorithm
- Understanding **linear** and **non-linear** decision boundaries
- Implementation using **scikit-learn**
- Visualization of classification results
- Model evaluation using accuracy and confusion matrix

---

## 🧩 Key Concepts

### What is SVM?
Support Vector Machine (SVM) is a supervised machine learning algorithm that finds the best hyperplane that separates data into different classes.  
It aims to maximize the **margin** — the distance between the hyperplane and the nearest data points from each class.

### Types of SVM:
- **Linear SVM**: Used when data is linearly separable.
- **Non-linear SVM**: Uses kernels (e.g., RBF, polynomial) to map data into higher dimensions for better separation.

---

## 🚀 Implementation Steps

1. **Import Libraries**  
   Load essential Python libraries like `numpy`, `pandas`, `matplotlib`, and `sklearn`.

2. **Load Dataset**  
   Import a sample dataset (e.g., Iris dataset or custom CSV).

3. **Preprocess Data**  
   Handle missing values, split data into training and testing sets, and scale features.

4. **Train SVM Model**  
   Use `sklearn.svm.SVC()` with different kernels (`linear`, `rbf`, `poly`) and train the model.

5. **Evaluate Model**  
   Measure accuracy, visualize decision boundaries, and display confusion matrix.

6. **Conclusion**  
   Summarize the performance and highlight advantages of SVM over other algorithms.

---

