# Customer-Churn-Prediction
This project demonstrates a machine learning pipeline to predict customer churn using the **Telco Customer Churn Dataset**. It includes full data preprocessing, EDA, two ML models (Logistic Regression and Random Forest), and a performance comparison.
---

## 📁 Dataset

- **Source**: Telco Customer Churn Dataset (Kaggle)
- **Rows**: 7043 customers
- **Target**: `Churn` (Yes/No)
- **Features**: gender, tenure, monthly charges, services, etc.

---

## ⚙️ Project Workflow

1. **EDA & Data Cleaning**
   - Convert `TotalCharges` to numeric
   - Drop missing values and ID column
2. **Encoding & Scaling**
   - One-hot encode categorical features
   - Standardize numerical features
3. **Train/Test Split**
   - 80/20 stratified split
4. **Modeling**
   - Logistic Regression (baseline)
   - Random Forest (ensemble)
5. **Evaluation**
   - Classification report
   - Confusion matrix
   - ROC Curve & AUC comparison
6. **Feature Importance**
   - Visualized top 10 drivers of churn

---

## 📎 Files

- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — input dataset
- `churn_prediction.ipynb` — full notebook
- `churn_prediction_summary.pdf` — business report
-  `README.md` — this file

---

## License

This project is licensed under the [MIT License](LICENSE).

