# 🏨 Hotel Booking Cancellation Prediction using Machine Learning

A complete Machine Learning project that predicts whether a hotel booking will be cancelled based on customer and booking information.

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>

<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

<img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>

<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

</p>

---
---

## 📌 Project Overview

Hotel booking cancellations lead to revenue loss and inefficient resource planning. This project applies supervised machine learning techniques to predict booking cancellations using historical hotel booking data.

The project covers the complete machine learning pipeline, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Building
- Model Evaluation
- Feature Importance Analysis
- Model Comparison

---

## 🎯 Problem Statement

Predict whether a hotel booking will be cancelled before the customer's arrival.

Target Variable:

- **0 → Booking Not Cancelled**
- **1 → Booking Cancelled**

---

## 📂 Dataset

**Dataset Name:** Hotel Booking Demand Dataset

- Records: **119,390**
- Features: **32**
- Target Variable: **is_canceled**

Dataset includes:

- Hotel Type
- Lead Time
- Arrival Date
- Market Segment
- Distribution Channel
- Previous Cancellations
- Deposit Type
- Customer Type
- Average Daily Rate (ADR)
- Special Requests
- And more...

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

- Booking Cancellation Distribution
- Hotel Type Distribution
- Monthly Booking Trend
- Top 10 Countries by Bookings
- Market Segment Distribution
- Lead Time vs Cancellation
- Correlation Heatmap

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## 🏆 Results

Random Forest achieved the highest performance among the implemented models and was selected as the final model.

---

## 📁 Project Structure

```
Hotel-Booking-Cancellation-Prediction/
│
├── data/
│   ├── hotel_bookings.csv
│   └── README.md
│
├── images/
│   ├── Correlation Heatmap.png
│   ├── Decision Tree Confusion Matrix.png
│   ├── KNN Confusion Matrix.png
│   ├── Logistic Regression Confusion Matrix.png
│   ├── ROC Curve Comparison.png
│   ├── Random Forest Confusion Matrix.png
│   ├── Top 10 Important Features.png
│   └── README.md
│
├── notebook/
│   ├── Hotel_Booking_Cancellation_Prediction.ipynb
│   └── README.md
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/shobhityadav-ds/Hotel-Booking-Cancellation-Prediction.git
```

Move into the project directory

```bash
cd Hotel-Booking-Cancellation-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Hotel_Booking_Cancellation_Prediction.ipynb
```

---



## 💡 Business Insights

- City Hotels receive more bookings than Resort Hotels.
- Longer lead times increase the probability of cancellation.
- Previous cancellations strongly influence future cancellations.
- Guests making more special requests are less likely to cancel.
- Online Travel Agencies contribute the largest number of bookings.

---

## 📌 Future Improvements

- Hyperparameter Tuning
- XGBoost Classifier
- LightGBM
- Streamlit Web Application
- Model Deployment using Flask/FastAPI

---

## 👨‍💻 Author

**Shobhit Kumar Yadav**

GitHub: https://github.com/shobhityadav-ds

LinkedIn: *(Add your LinkedIn profile here)*

---

## ⭐ If you found this project helpful, consider giving it a star.
