# Bank Marketing Prediction using Decision Tree Classifier

## 📌 Project Overview
This project builds a **Decision Tree Classifier** to predict whether a customer will **purchase a product or service** (subscribe to a term deposit) based on their **demographic and behavioral data**.

The analysis and model implementation are done using **Python in a Jupyter Notebook**, following standard machine learning steps:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Evaluation and interpretation

---

## 🎯 Problem Statement
> Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

This project solves the problem by:
- Cleaning and preparing the Bank Marketing dataset
- Training a **Decision Tree Classifier**
- Evaluating model performance
- Identifying key factors influencing customer decisions

---

## 📂 Dataset Information
- **Dataset Name:** Bank Marketing Dataset
- **Source:** UCI Machine Learning Repository
- **Description:** Data related to direct marketing campaigns of a Portuguese banking institution.
- **Target Variable:** `y` (whether the client subscribed to a term deposit)

🔗 Dataset Link:  
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – machine learning model building
- **Jupyter Notebook**

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Handled missing and unknown values
- Encoded categorical variables using label encoding / one-hot encoding
- Selected relevant features for modeling
- Split the data into training and testing sets
- Standardized data where required

---

## 🌳 Model Used
- **Algorithm:** Decision Tree Classifier
- **Reason:** 
  - Easy to interpret
  - Handles both categorical and numerical data
  - Suitable for classification problems

---

## 📊 Model Evaluation
The model was evaluated using:
- Accuracy score
- Confusion matrix
- Classification report (precision, recall, F1-score)

The evaluation helps understand how well the model predicts customer subscription behavior.

---

## 📈 Key Insights
- Certain demographic factors (age, job type, education) influence purchase decisions
- Previous marketing interactions significantly affect customer response
- Decision Trees provide clear rules that explain customer behavior

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/bank-marketing-decision-tree.git
cd bank-marketing-decision-tree
