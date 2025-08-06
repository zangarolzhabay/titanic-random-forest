# 🎯 Titanic Survival – My First ML Pet Project

This is my first personal project where I applied everything I’ve learned about data preprocessing, Random Forest, and hyperparameter tuning. The goal is to predict who survived the Titanic disaster based on the given features.

---

## 🔍 What I Did

- Cleaned the dataset (removed `Cabin`, `Ticket`, filled missing values)
- Selected features like `Sex`, `Age`, `Fare`, `Embarked`, etc.
- Converted categorical data using `get_dummies`
- Used `train_test_split` to split the dataset
- Trained a **RandomForestClassifier**
- Tuned it with **GridSearchCV** (used `recall` as scoring)
- Evaluated the model with `accuracy_score` and `classification_report`

---

## 📈 Model Performance

- Accuracy: ~81%
- Focused on **recall** (better to guess more survivors than miss them)
- Used cross-validation to choose the best model

---

## 📂 What's Inside

- `titanic_first_petproject.ipynb` — full notebook with comments and results
- Clean pipeline: from loading the data to final prediction and evaluation
- GridSearch results shown clearly

---

## ⚙️ Stack

- Python
- Pandas, NumPy
- scikit-learn (RandomForestClassifier, GridSearchCV)
- Matplotlib, Seaborn (optional)

---

## 👨‍🎓 About Me

I'm a 4th year student majoring in Math and Statistics.  
This is my first real try at solving a classic ML task step by step.

More pet-projects coming soon 🚀
