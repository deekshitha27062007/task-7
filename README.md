#  Task 7: Support Vector Machines (SVM) – Breast Cancer Classification

##  Objective
This project demonstrates the application of Support Vector Machines (SVMs) for binary classification using the **Breast Cancer Wisconsin Diagnostic Dataset**. Both **linear** and **non-linear (RBF)** kernels are used, with emphasis on margin maximization, kernel trick, and hyperparameter tuning.

---

##  Tools & Libraries Used
- Python
- NumPy
- Matplotlib
- scikit-learn (SVC, PCA, GridSearchCV, etc.)

---

##  Dataset
- **Name**: Breast Cancer Wisconsin (Diagnostic)
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- **Features**: 30 real-valued features
- **Target**: Binary classification – Malignant (1) or Benign (0)

---

##  Features Implemented
-  Data standardization using `StandardScaler`
-  Dimensionality reduction to 2D using PCA (for visualization)
-  SVM model training with:
  - Linear kernel
  - RBF kernel
-  Visualization of decision boundaries
-  Hyperparameter tuning using `GridSearchCV`
-  Model evaluation using:
  - Classification report
  - Confusion matrix
  - Cross-validation scores

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/svm-breast-cancer.git
   cd svm-breast-cancer
2.Install the required libraries

      pip install -r requirements.txt
3.  Run the main script

python svm_classification.py
