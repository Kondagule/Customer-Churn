# CUSTOMER CHURN PREDICTION USING MACHINE LEARNING
# 📊 Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to stop using their services. This project uses machine learning techniques to analyze customer information and predict whether a customer is likely to churn.

The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment through a Streamlit web application.

---

## 🎯 Objectives

* Analyze customer data to understand churn patterns.
* Perform data cleaning and preprocessing.
* Build and compare machine learning models.
* Select the best-performing model for prediction.
* Deploy the model using Streamlit for real-time predictions.

---

## 📂 Dataset

The dataset contains customer demographic and service-related information.

### Features

* CustomerID
* Age
* Gender
* Tenure
* MonthlyCharges
* ContractType
* InternetService
* TotalCharges
* TechSupport
* Churn (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Streamlit
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following visualizations were created during EDA:

* Dataset Preview
* Churn Distribution
* Feature Distribution Plots
* Boxplots
* Feature vs Churn Analysis
* Correlation Heatmap

---

## 🤖 Machine Learning Models

The following algorithms were evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

The Random Forest model was selected as the final model based on its performance.

---

## 📈 Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

---

## 💻 Streamlit Application

The application allows users to:

* Enter customer information.
* Predict customer churn probability.
* View churn risk as Low, Moderate, or High.
* Display prediction probability in an interactive interface.

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── customer_churn_data.csv
├── new_nb(2).ipynb
├── app.py
├── randomforest_churn_model.pkl
├── requirements.txt
├── README.md
└── screenshots/
    ├── dataset.png
    ├── churn_distribution.png
    ├── correlation_heatmap.png
    ├── streamlit_home.png
    └── prediction_result.png
```

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

### Navigate to the project folder

```bash
cd customer-churn-prediction
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

### Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📷 Project Screenshots

Include screenshots of:

* Dataset Preview
* Churn Distribution
* Correlation Heatmap
* Streamlit Home Page
* Prediction Output

---

## 🚀 Future Improvements

* Improve prediction accuracy using advanced algorithms.
* Apply hyperparameter tuning.
* Connect the application to a real-time database.
* Deploy the application on cloud platforms.
* Add a customer retention recommendation system.

---

## 👩‍💻 Author

**Krutika Kondagule**

M.Sc. Statistics (Data Science)

Vishwakarma University, Pune

---

## 📜 License

This project was developed for academic and learning purposes as part of the Summer Internship Program.
