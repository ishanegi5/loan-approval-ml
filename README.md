# Loan Approval Prediction 🏦

This project aims to predict **loan approval** using different machine learning algorithms.  
The dataset used is the **Loan Approval Dataset**.  

## 📌 Project Overview
Financial institutions need quick and reliable ways to decide whether a loan application should be approved or rejected.  
This project applies various machine learning models to automate and compare performance on the loan approval dataset.

## ⚙️ Dataset
- **Source:** Loan Approval Dataset  
- **Target:** Loan_Status (Approved / Not Approved)  
- **Features:** Applicant income, education, credit history, property area, etc.  

## 🧑‍💻 Models Implemented
The following machine learning algorithms were trained and evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Bernoulli Naive Bayes
- Support Vector Classifier (SVC)
- XGBoost Classifier

## 📊 Model Comparison

| Model                | Accuracy |
|-----------------------|----------|
| Random Forest         | **0.6875** |
| KNN                   | 0.6666 |
| XGBoost               | 0.6458 |
| Gaussian NB           | 0.6250 |
| SVC                   | 0.6145 |
| Bernoulli NB          | 0.5937 |
| Logistic Regression   | 0.5833 |
| Decision Tree         | 0.5830 |

✅ **Best Performing Model:** Random Forest with ~68.75% accuracy.  

## 📈 Evaluation
- Accuracy, Confusion Matrix, and Classification Report were used for evaluation.  
- ROC-AUC curves were plotted for selected models.  

## 🔧 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ishanegi5/loan-approval-ml.git
Navigate into the project:

bash
Copy code
cd loan-approval-ml
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run Jupyter Notebook or Python scripts to train models.

📌 Future Improvements
Feature engineering for better predictive performance

Hyperparameter tuning with more advanced search strategies

Try ensemble techniques for boosting accuracy beyond 70%

👤 Author
GitHub: @ishanegi5
