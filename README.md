
# 📘 Machine Learning Roadmap – Notes

---

## 📑 Contents

1. **Introduction to Machine Learning**

   * What is ML?
   * Types of ML (Supervised, Unsupervised, Reinforcement Learning)
   * ML Pipeline Overview

2. **Supervised Learning Algorithms**

   * Regression

     * Linear Regression
     * Multiple Linear Regression
     * Advanced Regression (Ridge, Lasso, Elastic Net)
     * Logistic Regression + Variants
   * Classification

     * Decision Tree
     * Random Forest
     * Support Vector Machine (SVM)
     * k-Nearest Neighbours (kNN)
     * Naive Bayes
     * Gradient Boosting (XGBoost, LightGBM, CatBoost)

3. **Unsupervised Learning Algorithms**

   * Clustering

     * K-Means
     * Hierarchical Clustering
     * DBSCAN
   * Dimensionality Reduction

     * PCA
     * t-SNE
   * Association Rule Mining
   * Anomaly Detection

4. **Model Evaluation**

   * Confusion Matrix
   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * ROC & AUC

5. **Core ML Concepts**

   * Bias–Variance Tradeoff
   * Cross-Validation

6. **Regularization Techniques**

   * Ridge Regression (L2)
   * Lasso Regression (L1)
   * Elastic Net (L1 + L2)
---

## 🧠 Key Visuals

### 🔹 Bias–Variance Tradeoff

```
High Bias (Underfit) → Model too simple
High Variance (Overfit) → Model too complex
Optimal → Balance between the two
```

### 🔹 Cross-Validation (k-Fold Example)

```
Dataset split into k parts
Train on k-1 folds, test on 1
Repeat k times → Average performance
```

### 🔹 Regularization Summary

* **Ridge (L2):** Shrinks coefficients, keeps all features.
* **Lasso (L1):** Shrinks some to zero → feature selection.
* **Elastic Net:** Mix of both, good for correlated features.
