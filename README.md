# 📊 Bank Marketing Campaign — Term Deposit Prediction

This project aims to analyze data from a bank's marketing campaign to **predict whether a client will subscribe to a term deposit**, using machine learning classification models.

---

## 🗂️ Dataset

The dataset includes attributes like:
- Personal: `age`, `job`, `marital`, `education`
- Financial: `balance`, `housing`, `loan`
- Campaign-related: `contact`, `month`, `day_of_week`, `duration`
- Other: `poutcome`, `emp.var.rate`, `euribor3m`, etc.

🗃️ Source: Provided as `bankmarketing.csv`

---

## 🔍 What We Did

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Encoded categorical variables and scaled numerical features
- Trained Logistic Regression, Decision Tree, and Random Forest
- Evaluated models using accuracy, precision, recall, and F1-score

---

## 📈 Key Insights

- `duration`, `poutcome`, and `contact` were strong predictors.
- The campaign was more successful in **May** and **August**.
- Longer call durations led to a higher chance of subscription.
- **Random Forest** performed best overall.

---

## 💻 Technologies Used

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 File Structure

