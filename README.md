# Default Credit Card Clients

## 📌 Project Overview
This project focuses on predicting whether a credit card client will default on their payment in the upcoming month. Using historical client data, the goal is to build a machine learning model that can classify clients into **default** or **non-default** categories.  

Such prediction models are crucial for financial institutions to minimize risk, improve lending strategies, and enhance customer management.

---

## 📊 Dataset
The dataset contains information about credit card clients, including:
- **Demographics**: Age, Gender, Education, Marital Status
- **Financials**: Credit Limit, Payment History, Bill Statements
- **Behavioral Data**: Past payment delays, default history

Target variable:  
- `default.payment.next.month` → `1` (Default) or `0` (No Default)

---

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** to understand client behavior.
- Clean and preprocess the dataset (handle missing values, encode categorical variables, scale numerical features).
- Build and evaluate classification models:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting
- Compare model performance using metrics like **Accuracy, Precision, Recall, F1-score, and ROC-AUC**.
- Provide business insights for risk management.

---

## ⚙️ Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` → Data handling
  - `matplotlib`, `seaborn` → Visualization
  - `scikit-learn` → Machine Learning models
  - `xgboost` / `lightgbm` → Advanced boosting algorithms
- **Environment**: Jupyter Notebook / VS Code

---

## 🚀 Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/default-credit-card-clients.git
2. Navigate to the project folder:

bash
cd default-credit-card-clients
3. Install dependencies:

bash
pip install -r requirements.txt
4. Run the Jupyter Notebook:

bash
5. jupyter notebook
Open default_credit_card_clients.ipynb and execute cells step by step.
