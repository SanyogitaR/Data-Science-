# Cricket Match Winner Prediction using Machine Learning  

## Problem Statement  
To predict the winner of a cricket match based on available features using classification algorithms.

---

## Tools & Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-Learn  
- XGBoost  
- SMOTE (for handling class imbalance)  
- Jupyter Notebook  

---

## Project Workflow  

### 1. Data Cleaning & Preprocessing  
- Handled missing values  
- Encoded categorical variables  

### 2. Feature Engineering  
- Score Difference (`score_diff`)  
- Wicket Difference (`wkt_diff`)  
- Toss Impact Feature (`toss_match`)  
- Extracted `month` and `day` from date  

---

## Models Used  

- Random Forest Classifier  
- XGBoost Classifier  
- Voting Classifier (Ensemble of RF & XGB)  

---

## Accuracy Achieved  

| Model | Accuracy |
|-------|----------|
| Random Forest | 46% - 52% |
| XGBoost | 59% |
| Voting Classifier | 59% |
| Cross Validation Accuracy | 53.46% |

---

## Final Deliverables  

- `cricket_prediction_final.ipynb` : Final Jupyter Notebook  
- `final_xgb_model.pkl` : Saved Machine Learning Model  
- `requirements.txt` : Required Libraries  

---

## How to Run  

Install dependencies:  
```bash
pip install -r requirements.txt
