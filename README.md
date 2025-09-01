
```markdown
## 📊 Customer Churn Prediction (Random Forest)
Predicting customer churn is essential for businesses to reduce customer loss and improve retention strategies.  
This project applies a **Random Forest Classifier** to analyze telecom customer data and predict churn.

---

## 🔎 Overview
- **Objective:** Predict whether a customer will churn (leave) or stay.  
- **Dataset:** churn-bigml-80.csv (telecom dataset with 3993 rows, 21 columns).  
- **Workflow:**
  1. Data Preprocessing (encode categorical + handle numerical features).  
  2. Train/Test Split (80/20).  
  3. Model Training using **Random Forest Classifier**.  
  4. Evaluation via Accuracy, Confusion Matrix, Classification Report.  

---

## 📂 Project Structure
Customer-Churn-Prediction-(Random Forest)/
- Customer Churn Prediction.ipynb   # Jupyter Notebook
- churn-bigml-80.csv                # Dataset
- requirements.txt                  # Dependencies
- README.md                         # Project Documentation

---

## ⚙️ Installation
Clone the repository and install dependencies:
git clone https://github.com/abdullahq-mlworks/Costumer-Churn-Prediction.git
cd Customer-Churn-Prediction-(Random Forest)
pip install -r requirements.txt

---

**Requirements:**
pandas
scikit-learn

---

## 🧾 Dataset
* **Features:**
  * Numerical → Total day minutes, Total eve calls, Total intl charge, etc.
  * Categorical → State, International plan, Voice mail plan
* **Target:** Churn (Yes/No)

---

## 🤖 Model
* Algorithm: **RandomForestClassifier** (sklearn.ensemble)
* Hyperparameters:
  * n_estimators = 100
  * max_depth = None
  * random_state = 42

---

## 📊 Results
* **Accuracy:** \~95%
* **Confusion Matrix & Classification Report:** Strong precision and recall for both churned and non-churned customers.

---

## 🚀 Future Work
* Compare with other models: Logistic Regression, Decision Tree, XGBoost, SVM.
* Feature Importance Analysis to understand drivers of churn.
* Hyperparameter Tuning (GridSearchCV/RandomizedSearchCV).
* Deploy as a **Streamlit/Flask Web App**.

---