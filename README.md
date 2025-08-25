# Machine Learning Portfolio

Welcome to my **Machine Learning Portfolio**!  
This repository showcases projects and notebooks where I apply practical ML techniques, focusing on **imbalanced data handling**, **feature engineering**, and **feature selection**. Each project includes clean code, visualizations, and explanations for reproducibility and interpretability.

---

# 🌟 Featured Notebook: Feature Selection Demo

Check out my **top notebook** demonstrating advanced feature selection techniques with the Breast Cancer dataset.  
It combines **wrapper and embedded methods**, visualizations, and clear explanations – perfect for showcasing interpretability and ML best practices.

[📓 Open Notebook on GitHub](02_feature_selection/notebooks/Wisconsin_Breast_Cancer/Feature_Selection_Demonstration_with_the_Breast_Cancer_Dataset.ipynb)

**Key Highlights:**
- Recursive Feature Elimination (RFE) and Random Forest feature importance
- Visual interpretation of the top 10 features
- Step-by-step explanations for reproducibility
- Modular and clean code ready to adapt to other datasets

---
## 📂 Project Overview

### 01. Feature Engineering
- Explore techniques to improve model performance by creating and transforming features.
- Includes scaling, encoding, interaction features, and dimensionality reduction.
- Highlights the impact of engineered features on model accuracy.

### 02. Feature Selection
- Demonstrates different **feature selection methods**: Filter, Wrapper (RFE), and Embedded (Random Forest/Lasso).
- Shows how to improve interpretability and robustness without necessarily increasing accuracy.
- **Feature Importance Visualization:**
  
  ![Top Features](02_feature_selection/images/feature_importances.png)
- **Top 10 Features by Random Forest**

  | Rank | Feature                | Importance Score |
  |------|------------------------|------------------|
  | 1    | worst area             | 0.140016         |
  | 2    | worst concave points   | 0.129530         |
  | 3    | worst radius           | 0.097696         |
  | 4    | mean concave points    | 0.090885         |
  | 5    | worst perimeter        | 0.072226         |
  | 6    | mean perimeter         | 0.069574         |
  | 7    | mean radius            | 0.068676         |
  | 8    | mean concavity         | 0.057638         |
  | 9    | mean area              | 0.049172         |
  | 10   | worst concavity        | 0.034340         |

### 03. Imbalanced Data Handling
- Focuses on classification with **imbalanced datasets**.
- Demonstrates resampling techniques (SMOTE, Random Oversampling/Undersampling), threshold tuning, and evaluation metrics beyond accuracy (F1-score, ROC-AUC).
- Provides a step-by-step guide to building robust classifiers in real-world scenarios.

---

## 📊 Highlights
- Clear, modular notebooks with explanations and code comments.
- Visualizations for interpretability, including feature importance plots.
- Best practices: preprocessing pipelines, cross-validation, and model evaluation.

---

## 🔧 Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebooks for interactive demonstrations

---

## ✅ How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/ThePheenix/Machine-Learning-Portfolio.git
2. Install required libraries (e.g., via pip install -r requirements.txt).
3. Open notebooks in Jupyter or VSCode.
4. Follow the explanations and run cells step-by-step.

## 📈 Contact / Hire Me

If you are interested in ML consulting, feature engineering, or data science projects, feel free to reach out via Upwork or GitHub discussions.
