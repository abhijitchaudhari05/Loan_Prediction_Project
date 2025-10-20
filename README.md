# 🏦 Loan Approval Prediction Project

### 📘 Overview
This project predicts loan approval using machine learning.  
It includes data cleaning, visualization, feature engineering, and model evaluation.

### ⚙️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- SMOTE for handling class imbalance

### 🧩 Project Workflow
1. Data Preprocessing (Handling nulls, encoding)
2. Exploratory Data Analysis (EDA)
3. Feature Scaling
4. Model Building (Logistic Regression)
5. Model Evaluation (Accuracy, ROC-AUC, F1-score)
6. Feature Importance Interpretation

### 📊 Results
| Model | Accuracy | ROC-AUC |
|:------|:---------:|:-------:|
| Logistic Regression | 0.789 | 0.75 |
| Class-weighted Logistic Regression | 0.748 | 0.75 |
| SMOTE Logistic Regression | **0.78** | **0.78** |

### 🧠 Key Insights
- Credit History is the strongest predictor of loan approval.
- Income and loan amount are skewed; scaling/log transformation helps.
- SMOTE balanced the dataset and improved minority class recall.

### 👤 Author
**Abhijit Chaudhari**  
📍 Pune, Maharashtra  
🔗 [LinkedIn](https://www.linkedin.com/in/abhijitchaudhari05) | [GitHub](https://github.com/abhijitchaudhari05)
