
# Employee Attrition Prediction

This project builds a predictive model to identify employees at risk of leaving an organization. Built using a real-world HR dataset, it uses logistic regression with class balancing to improve recall for attrition cases.

## 🧠 Objective
To help HR teams flag at-risk employees for proactive intervention.

## 📦 Dataset
- **Source**: IBM HR Analytics Employee Attrition & Performance
- **Records**: 1,470 employees
- **Target**: `Attrition` (Yes/No)

## 🔍 Features Used
- Age, BusinessTravel, Department, DistanceFromHome, JobRole, MonthlyIncome, OverTime, etc.

## 🧮 Model
- **Logistic Regression (Weighted)**
- Accuracy: 68%
- Recall for Attrition = 77%

## 🗃️ Structure

employee-attrition-prediction/
├── data/ # Raw dataset
├── notebooks/ # Final model code (Jupyter)
├── models/ # Saved model (pickle)
├── README.md
├── requirements.txt
└── .gitignore


## 🚀 Usage

1. Clone the repo:
git clone https://github.com/yourusername/employee-attrition-prediction.git
cd employee-attrition-prediction

2. Install dependencies:
pip install -r requirements.txt

3. Open the notebook:
jupyter notebook notebooks/attrition_prediction_final.ipynb


## 📈 Future Enhancements
- Try Random Forest and XGBoost
- SHAP for explainability
- Deploy as Streamlit web app

---












