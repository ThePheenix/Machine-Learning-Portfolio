# Fraud Detection with Imbalanced Data – Oversampling Comparison

This project explores different oversampling techniques for handling class imbalance in a credit card fraud dataset. The focus is on comparing how methods like **Random Oversampling, SMOTE, ADASYN, Borderline-SMOTE, SVM-SMOTE, and K-Means-SMOTE** affect model performance.

---

## 🔍 Project Goals
- Demonstrate the impact of various oversampling strategies.  
- Evaluate models using **confusion matrices** and **classification reports**.  
- Highlight the trade-off between **recall** and **precision** in fraud detection.  

---

## 📊 Key Insights
- Oversampling generally **improves recall** (more fraud cases are detected).  
- Precision often **drops significantly** due to more false positives.  
- This reflects a **typical trade-off in fraud detection**: detecting more fraud comes at the cost of more false alarms.  

---

## 🛠️ Techniques Used
- **Python**: pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn  
- **Oversampling Methods**:  
  - RandomOverSampler  
  - SMOTE, SMOTE-NC, SMOTEN  
  - ADASYN  
  - Borderline-SMOTE (variants 1 & 2)  

---

## Results

**Confusion Matrices**

| ROS | SMOTE |
|-----|-------|
| ![ROS](../../ros_confusion_matrix.png) | ![SMOTE](../../smote_confusion_matrix.png) |

| ADASYN | Borderline-SMOTE |
|--------|------------------|
| ![ADASYN](../../adasyn_confusion_matrix.png) | ![Borderline](../../borderline-smote_confusion_matrix.png) |

---

## Conclusion
Oversampling is a powerful tool for handling imbalanced data, but it introduces a **precision–recall trade-off**. In practice, the optimal method depends on business priorities:  
- High recall is often preferred in fraud detection (better to flag too many than to miss a real fraud).  
- Further improvements could be achieved with **threshold tuning, cost-sensitive learning, or ensemble methods**.  

---

## Repository Structure
- `notebooks/` – Jupyter Notebook with experiments and results  
- `data/` – (link or description, if dataset is not public)  
- `README.md` – Project summary  

---

## Next Steps
- Try **threshold tuning** to optimize the precision-recall balance.  
- Explore **ensemble approaches** for more robust results.  
- Apply the workflow to other real-world imbalanced datasets.

