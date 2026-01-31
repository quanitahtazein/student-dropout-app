# 🎓 Student Dropout Early Warning System

This is a **Machine Learning and Streamlit application** designed to **predict which students are at risk of dropping out early in the semester**. Advisors can use this system to **identify high-risk students** and understand the **reasons behind the risk**.

---

## **Project Overview**

The university was losing students each semester. This system:

- Predicts student dropout risk early in the semester  
- Provides a **risk score** and **risk label** (Low, Medium, High)  
- Shows the **top reasons for dropout** using feature importance  
- Compares performance of multiple models: Logistic Regression, Decision Tree, Random Forest, XGBoost

---

## **Features**

1. **Upload student CSV file**  
2. **Top 20 high-risk students** table  
3. **Individual student risk score and risk label**  
4. **Bar chart showing top features contributing to dropout risk**  
5. **ROC AUC comparison of all models**

Student_Dropout_Assignment/
├─ app.py # Streamlit app

├─ models/ # Trained ML models (.pkl)

│ ├─ dropout_model.pkl

│ ├─ dropout_model_dt.pkl

│ ├─ dropout_model_rf.pkl

│ └─ dropout_model_xgb.pkl

├─ requirements.txt # Python packages for Streamlit Cloud

├─ data/sample_input.csv # Example CSV for testing

└─ README.md

---

## **Requirements**

All Python packages needed are listed in `requirements.txt`:
streamlit==1.28.0
pandas==2.1.1
numpy==1.25.0
scikit-learn==1.3.2
xgboost==1.7.7
matplotlib==3.8.0
seaborn==0.13.2
joblib==1.3.2

## **Project Structure**

