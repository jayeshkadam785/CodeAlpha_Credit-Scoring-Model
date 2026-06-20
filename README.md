# CodeAlpha_Credit-Scoring-Model

## 📌 Task 1: Credit Scoring Model
**CodeAlpha Machine Learning Internship**

### 🎯 Objective
Predict an individual's creditworthiness using past financial data.

### 🛠️ Approach
- Classification algorithms used: **Logistic Regression**, **Decision Tree**, and **Random Forest**
- Feature engineering applied on financial history (income, debt, payment history, etc.)
- Model performance evaluated using **Precision, Recall, F1-Score, and ROC-AUC**

### 📊 Dataset
Financial dataset including features such as:
- Income
- Debt
- Age
- Employment years
- Number of credit lines
- Late payments
- Credit utilization

### ⚙️ Tech Stack
- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Google Colab

### 📈 Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.85 | 0.83 | 0.80 | 0.81 | 0.89 |
| Decision Tree | 0.81 | 0.79 | 0.78 | 0.78 | 0.84 |
| Random Forest | 0.89 | 0.87 | 0.86 | 0.86 | 0.92 |

**Best Model:** Random Forest (highest across all metrics)

### 📁 Files
- `Credit_Scoring_Model.ipynb` — Full Colab notebook with data preprocessing, model training, and evaluation
- `credit_scoring_model.pkl` — Trained Random Forest model
- `scaler.pkl` — Feature scaler used during preprocessing

### 🚀 How to Run
1. Open the notebook in Google Colab
2. Upload your dataset CSV when prompted
3. Run all cells sequentially
4. View model comparison, ROC curve, confusion matrix, and feature importance plots

---
**Author:** Jayesh Kadam
**Internship:** CodeAlpha — Machine Learning Track
