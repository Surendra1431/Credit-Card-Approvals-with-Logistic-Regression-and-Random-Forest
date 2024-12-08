![credit_card](https://github.com/user-attachments/assets/24ee9cca-8859-446f-a287-81068d347f21)

# 💳 Credit Card Approvals with Machine Learning

This project leverages machine learning to predict credit card approvals, tackling real-world challenges in financial decision-making. We preprocess data, engineer features, and use models like Logistic Regression and Random Forest to make accurate predictions. 🚀

---

## 📌 Problem Statement

Credit card approval is a critical decision for financial institutions. 🏦 It requires assessing applicants' financial stability and risk while maintaining fairness. This project addresses key challenges in the approval process:

### 🛑 **Key Challenges**
1. 🔍 **Incomplete Data**: Missing or invalid entries (e.g., `'?'`) require proper handling.
2. ⚖️ **Imbalanced Classes**: Disproportionate numbers of approvals and rejections could bias models.
3. 📏 **Feature Scaling**: Attributes like income and credit score operate on different scales, needing standardization.
4. 🎛️ **Hyperparameter Optimization**: Ensuring models are finely tuned to avoid overfitting while maintaining accuracy.

---

## 🎯 Objectives
1. **📂 Data Preprocessing**:
   - Replace invalid placeholders like `'?'` with `NaN` and impute missing values using mean imputation.
   - Scale numeric features using `StandardScaler` to normalize data distributions.
2. **🤖 Model Training**:
   - Train Logistic Regression and Random Forest models to predict credit card approvals.
   - Optimize models through hyperparameter tuning using `GridSearchCV`.
3. **📊 Evaluation**:
   - Perform cross-validation for robust performance metrics.
   - Analyze results using classification reports, accuracy scores, and confusion matrices.

---

## 🛠️ Key Concepts

### **1. 📏 StandardScaler**
- Standardizes features by removing the mean and scaling to unit variance.
- Helps ensure features with different scales (e.g., income vs. credit history) contribute equally to the model.

### **2. 🎛️ Hyperparameter Tuning**
- Optimizes models for better performance:
  - **Logistic Regression**: Regularization type (`l1`, `l2`), `C` (regularization strength).
  - **Random Forest**: `n_estimators` (number of trees), `max_depth`, and more.

### **3. 🔁 Cross-Validation**
- Used **StratifiedKFold** (5-fold) to:
  - Ensure balanced class distribution across folds.
  - Prevent overfitting and improve generalization.

---

## 🏆 Results
1. **📈 Logistic Regression**:
   - Provided a strong baseline after data preprocessing and scaling.
2. **🌲 Random Forest**:
   - With hyperparameter tuning, delivered higher accuracy and better handling of class imbalances.
3. **🔍 Cross-Validation**:
   - Ensured robust performance metrics and avoided overfitting.

---

## 📂 How to Use
1. 🚀 Open `notebook.ipynb` in Jupyter Notebook.
2. 🔧 Follow preprocessing steps to clean and scale the data.
3. 🧠 Train and evaluate models using the provided code.
4. 📊 Review results and insights in the notebook output.

---

## 📊 Dataset
The dataset includes anonymized attributes representing user financial and demographic data:
- **Inputs**: Features like income, credit history, and existing debts.
- **Target**: Binary labels indicating approval (`1`) or rejection (`0`) of credit card applications.

---

## 📜 License
This project is open-source and available for educational purposes. 🧑‍💻

---

✨ **Happy Predicting!** ✨
