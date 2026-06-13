# 🔄 Customer Churn Prediction

> End-to-end Machine Learning project to predict customer churn using Logistic Regression, Decision Tree, and Random Forest.

---

## 📌 Project Overview

This project builds a predictive model to identify customers likely to churn, enabling businesses to take proactive retention actions and reduce revenue loss.

**Goals:**
- Predict whether a customer will churn (Yes) or stay (No)
- Identify the most influential factors driving churn
- Compare three ML models and select the best performer

---

## 📁 Repository Structure

```
Customer-Churn-Prediction/
├── Customer_Churn_Prediction.ipynb   # Full ML workflow notebook
├── Customer_Churn_Dataset.csv        # Dataset used for training & testing
└── Customer_Churn_Report.pdf         # Detailed project report
```

---

## 🔄 Workflow

| Step | Description |
|------|-------------|
| 1️⃣ Data Loading & Inspection | Shape, dtypes, missing values, class distribution |
| 2️⃣ Exploratory Data Analysis | Count plots, boxplots across churn classes |
| 3️⃣ Preprocessing | Encoding, OneHotEncoder, 80/20 stratified split |
| 4️⃣ Model Training & Evaluation | Pipeline per model, 4 evaluation metrics |
| 5️⃣ Feature Importance & Prediction | Best model analysis + new customer prediction |

---

## 📊 Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 85.2% | 82.1% | 79.4% | 80.7% |
| Decision Tree | 83.7% | 80.5% | 78.1% | 79.3% |
| **Random Forest ✅** | **91.4%** | **89.8%** | **88.3%** | **89.0%** |

> ✅ **Random Forest** selected as the final model with **91.4% accuracy**

---

## 🔑 Key Factors Influencing Churn

| Rank | Feature | Importance |
|------|---------|------------|
| 1 | Customer Satisfaction | ⭐⭐⭐⭐⭐ |
| 2 | Contract Length | ⭐⭐⭐⭐⭐ |
| 3 | Monthly Fee | ⭐⭐⭐⭐ |
| 4 | Support Tickets | ⭐⭐⭐ |
| 5 | Login Frequency | ⭐⭐⭐ |

---

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas & NumPy** — Data manipulation and analysis
- **Scikit-Learn** — ML models, preprocessing, and evaluation
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Development environment

---

## 👤 Author

**Mohamed Ahmed Kenawy**
Mechatronics Engineer | SIC Alumni | ML & IoT Developer

- 🔗 [LinkedIn](https://www.linkedin.com/in/mohamed--kenawy/)
- 🐙 [GitHub](https://github.com/kenawy123)
