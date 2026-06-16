# Customer Churn Prediction using Machine Learning

> **UpSkill Campus — Winter Internship 2026**
> Domain: Data Science & Machine Learning
> Industry Partner: UniConverge Technologies Pvt Ltd (UCT)

---

## 📌 Project Name
**Customer Churn Prediction using Machine Learning**

---

## 📝 Short Summary of Implementation

This project builds a complete end-to-end Machine Learning pipeline to predict whether a telecom customer will churn (leave the service) based on their usage patterns, contract details, and demographics.

**What was implemented:**
- Exploratory Data Analysis (EDA) with visualisations
- Data preprocessing — Label Encoding, Feature Scaling
- Three ML models trained and compared:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Model evaluation using Accuracy, ROC-AUC, Confusion Matrix, and 5-Fold Cross Validation
- Feature Importance analysis to identify key churn drivers

**Best Model Achieved:** ~85%+ Accuracy with ROC-AUC > 0.88

---

## 📁 Repository Structure

```
upskillCampus/
│
├── customer_churn_prediction.py   ← Main ML code (full pipeline)
├── eda_dashboard.png              ← EDA visualisation output
├── model_performance.png          ← ROC Curve & Confusion Matrix
├── feature_importance.png         ← Feature importance chart
├── Internship_Report.docx         ← Final internship report
└── README.md                      ← This file
```

---

## 🔧 Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| NumPy & Pandas | Data manipulation |
| Matplotlib & Seaborn | Data visualisation |
| Scikit-learn | ML model building & evaluation |

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/upskillCampus.git
cd upskillCampus

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn

# 3. Run the project
python customer_churn_prediction.py
```

---

## 📊 Results

| Model | Accuracy | ROC-AUC | CV Score |
|---|---|---|---|
| Logistic Regression | ~79% | ~0.84 | ~0.80 |
| Random Forest | ~85% | ~0.89 | ~0.85 |
| Gradient Boosting | ~86% | ~0.90 | ~0.86 |

---

## 🏢 Internship Details

- **Organisation:** UpSkill Campus & UniConverge Technologies Pvt Ltd
- **Program:** Winter Internship 2026
- **Domain:** Data Science and Machine Learning
- **Duration:** 6 Weeks

---

## 📄 Report

Full internship report is available in `Internship_Report.docx` in this repository.
