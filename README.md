# Machine Learning Classification Model Selection

This repository demonstrates the implementation and comparison of **7 classification algorithms** in Python using the **Breast Cancer Wisconsin Dataset**.

---

## 📖 Dataset Description

- **Rows:** ~600  
- **Columns:** 11  
- **Target:** `Class` (2 = Benign, 4 = Malignant)  
- Features:
  - Clump Thickness
  - Uniformity of Cell Size
  - Uniformity of Cell Shape
  - Marginal Adhesion
  - Single Epithelial Cell Size
  - Bare Nuclei
  - Bland Chromatin
  - Normal Nucleoli
  - Mitoses

---

## 🧠 Algorithms Used

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Support Vector Machine (SVM)  
4. Kernel SVM  
5. Naive Bayes  
6. Decision Tree  
7. Random Forest  

---

## 📊 Model Comparison

| Model | Accuracy | Confusion Matrix |
|-------|---------|-----------------|
| Logistic Regression | 94.74% | [[103, 4], [5, 59]] |
| KNN | 94.74% | [[103, 4], [5, 59]] |
| SVM | 94.15% | [[102, 5], [5, 59]] |
| Kernel SVM | 95.32% | [[102, 5], [3, 61]] |
| Naive Bayes | 94.15% | [[99, 8], [2, 62]] |
| Decision Tree | 95.91% | [[103, 4], [3, 61]] |
| Random Forest | 93.57% | [[102, 5], [6, 58]] |

**Best Model:** ⭐ Decision Tree (Accuracy = 95.91%)

---

## ⚙️ How to Run

1. Open any `.ipynb` notebook in Google Colab or Jupyter Notebook.  
2. Ensure `breast_cancer_data.csv` is in the `dataset/` folder.  
3. Run all cells to see:
   - Data preprocessing
   - Model training
   - Predictions
   - Confusion Matrix
   - Accuracy

---

## 💻 Notebooks

| Notebook | Description |
|----------|------------|
| 01_logistic_regression.ipynb | Logistic Regression Implementation |
| 02_knn.ipynb | K-Nearest Neighbors Implementation |
| 03_svm.ipynb | Linear SVM Implementation |
| 04_kernel_svm.ipynb | Kernel SVM Implementation |
| 05_naive_bayes.ipynb | Naive Bayes Implementation |
| 06_decision_tree.ipynb | Decision Tree Implementation |
| 07_random_forest.ipynb | Random Forest Implementation |

---

## 🔥 Notes

- Accuracy and Confusion Matrix are provided for easy comparison.  
