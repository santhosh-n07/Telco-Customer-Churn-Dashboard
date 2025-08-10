# Telco Customer Churn Prediction & Dashboard

## 📌 Project Overview
This project predicts customer churn for a telecom company using machine learning and presents an interactive Power BI dashboard for insights. The goal is to identify customers likely to churn and understand the key factors driving churn for better retention strategies.

## 📂 Dataset
The data comes from the popular Telco Customer Churn dataset available on Kaggle:  
[Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
It includes 7,043 customer records with demographics, account info, service details, and churn labels.

## 🛠 What We Did
- **Data Cleaning & Preprocessing:**  
  Handled missing values, converted data types, label encoded categorical variables, and standardized numeric columns for modeling.
- **Modeling:**  
  Trained a Random Forest Classifier using an 80/20 stratified train-test split.
- **Evaluation:**  
  Assessed model performance using accuracy, precision, recall, F1-score, and ROC-AUC. Achieved ROC-AUC of approximately 0.86.
- **Feature Importance:**  
  Extracted feature importance to reveal top factors influencing churn like contract type, tenure, and monthly charges.
- **Power BI Dashboard:**  
  Created visualizations including:  
  - Churn rate card  
  - Clustered bar chart comparing actual vs predicted churn  
  - Metrics table summarizing model scores  
  - Feature importance chart  
  - Confusion matrix and ROC curve images  
  - Slicers for interactive filtering by gender, contract type, payment method, and tenure groups

## 📁 Files Included
| File                      | Description                                         |
|---------------------------|-----------------------------------------------------|
| `Telco_Customer_Churn.pbix` | Power BI dashboard file with all visuals and slicers |
| `churn_predictions.csv`   | Predicted and actual churn labels for test customers |
| `feature_importance.csv`  | Feature importance scores exported from Python      |
| `roc_curve.png`           | ROC curve image created in Python                    |
| `confusion_matrix.png`    | Confusion matrix image created in Python             |
| `README.md`               | Project documentation file                           |

## 📈 Key Insights
- The model performs well with ROC-AUC ~0.86.
- Contract type, tenure, and monthly charges are key churn drivers.
- The dashboard helps identify and visualize at-risk customer segments for targeted retention.

## 🚀 How to Run
1. **In Python (Jupyter Notebook):**  
   - Run data preprocessing and train the Random Forest model.  
   - Generate outputs: `churn_predictions.csv`, `feature_importance.csv`, `roc_curve.png`, and `confusion_matrix.png`.

2. **In Power BI:**  
   - Open the provided `.pbix` file.  
   - Load or refresh the CSV files and images.  
   - Use slicers and visuals to explore the churn data interactively.

## 🛠 Tools & Technologies
- Python: pandas, scikit-learn, matplotlib, seaborn  
- Power BI Desktop  
- Jupyter Notebook  

## 📄 License
This project is intended for educational use. Dataset sourced from Kaggle [here](https://www.kaggle.com/blastchar/telco-customer-churn).

---

Feel free to contact me for help running or extending this project!
