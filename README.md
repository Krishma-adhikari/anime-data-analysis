# Anime Data Analysis & Classification

## 📌 Project Overview
This project focuses on analyzing an Anime dataset and building a machine learning model to predict the **Type of anime**. The workflow includes data cleaning, handling missing values, exploratory analysis, and applying classification algorithms.

---

## 📂 Dataset Information
The dataset contains multiple features such as:
- Episodes
- Rating
- Tags
- Release_year
- Type (Target variable)

⚠️ The dataset had a large number of missing values, which made preprocessing an important step.

---

## 🧹 Data Preprocessing
- Handled missing values in numerical and categorical columns
- Encoded categorical features where necessary
- Prepared data for machine learning models

---

## 📊 Models Used
- Logistic Regression
- Random Forest Classifier

---

## ⚙️ Model Evaluation
The models were evaluated using accuracy score on training and testing data.

### Observations:
- Training accuracy: ~69%
- Testing accuracy: ~63%
- When increasing `max_depth` significantly (e.g., 90), the model showed unstable behavior and overfitting patterns
- In the final configuration, the accuracy dropped to around **30%**

---

## 📈 Key Learnings
- Importance of handling missing values properly
- Effect of hyperparameters on model performance
- Understanding overfitting and underfitting
- Difference between training and testing accuracy
- Impact of data quality on machine learning models

---

## 🧠 Conclusion
This project helped in understanding the complete machine learning pipeline from data preprocessing to model evaluation. It also showed how data quality, missing values, and hyperparameter tuning can strongly affect model performance. In the end, the model achieved an accuracy of around **30%**, highlighting the challenges in working with noisy and incomplete datasets.

---

## 🚀 Future Improvements
- Better encoding of Tags column
- Feature engineering to improve accuracy
- Hyperparameter tuning using GridSearchCV
- Trying advanced models like XGBoost

---

## 👨‍💻 Author
Krishma Adhikari
