# 🍔 Food Delivery Time Prediction using EDA, Linear Regression & Logistic Regression

## 📌 Project Overview

This project focuses on analyzing and predicting food delivery times using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling with Linear Regression and Logistic Regression. The objective is to identify the factors that influence delivery time and generate actionable insights for improving delivery efficiency.

---

## 🎯 Objectives

* Analyze food delivery data to understand delivery patterns.
* Identify key factors affecting delivery times.
* Perform data cleaning and preprocessing.
* Build predictive models for delivery time estimation.
* Classify deliveries as **Fast** or **Delayed**.
* Provide operational insights to optimize delivery services.

---

## 📂 Dataset

The dataset contains information related to food delivery operations, including:

* Distance between restaurant and customer
* Delivery Time
* Weather Conditions
* Traffic Conditions
* Order Cost
* Vehicle Type
* Delivery Person Experience
* Order Priority

**Dataset File:** `Food_Delivery_Time_Prediction.csv`

---

## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

### Data Cleaning

* Handling missing values
* Removing inconsistencies
* Data transformation

### Feature Encoding

* Label Encoding
* One-Hot Encoding

### Data Scaling

* Normalization of numerical features

### Statistical Analysis

* Mean
* Median
* Variance
* Standard Deviation

### Visualization

* Correlation Heatmaps
* Pair Plots
* Scatter Plots
* Box Plots
* Distribution Graphs

---

## ⚙️ Feature Engineering

To improve model performance:

* Distance-related features were analyzed.
* Time-based attributes were created.
* Rush-hour patterns were identified.
* Relevant variables were selected based on correlation analysis.

---

## 🤖 Machine Learning Models

### 1️⃣ Linear Regression

Used for predicting the exact delivery time.

#### Features

* Distance
* Traffic Conditions
* Weather Conditions
* Order Priority
* Delivery Person Experience

#### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R-Squared Score (R²)

---

### 2️⃣ Logistic Regression

Used for classifying deliveries into:

* Fast Delivery
* Delayed Delivery

#### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📊 Model Evaluation

The models were evaluated using multiple performance metrics and visualizations:

* Confusion Matrix
* Correlation Analysis
* Regression Performance Metrics
* Comparative Analysis of Models

---

## 📈 Key Insights

✔️ Traffic conditions significantly impact delivery times.

✔️ Longer distances generally increase delivery duration.

✔️ Weather conditions influence delivery efficiency.

✔️ Experienced delivery personnel tend to complete deliveries faster.

✔️ Order priority affects delivery scheduling and completion time.

---

## 💡 Business Recommendations

* Optimize routes during peak traffic hours.
* Increase delivery staff during high-demand periods.
* Implement dynamic delivery scheduling.
* Use predictive analytics for better resource allocation.
* Provide additional training for delivery personnel.

---

## 📁 Project Structure

```bash
Food-Delivery-Time-Prediction/
│
├── data/
│   └── Food_Delivery_Time_Prediction.csv
│
├── notebooks/
│   └── Food_Delivery_Time_Prediction.ipynb
│
├── images/
│   └── Visualizations
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/Diyasaxena0111/Food-delivery-time-prediction-EDA-linear-logistic-Regression-.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## 📌 Future Improvements

* Random Forest Regression
* XGBoost Regressor
* Gradient Boosting Models
* Real-time Delivery Prediction
* Deployment using Flask/Streamlit
* Integration with GPS-based route optimization

---

## 👩‍💻 Author

**Diya Saxena**
B.Tech CSE (AI & ML)
Data Science | Machine Learning | AI Enthusiast

### ⭐ If you found this project useful, don't forget to star the repository! ⭐

```
```
