# CodeAlpha_DiseasePrediction
# 🩺 Disease Prediction from Medical Data

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-CodeAlpha-yellow)

---

## 📌 Project Overview

This project focuses on predicting diseases using machine learning algorithms based on patient medical data such as symptoms, age, and test results.

It also includes an interactive Streamlit web application that allows users to input patient data and receive real-time predictions.

---

## 🎯 Objective

The goal of this project is to build a system that can:

* Predict diseases accurately
* Compare multiple machine learning models
* Provide an easy-to-use healthcare prediction interface

---

## 🧠 Algorithms Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

---

## 📊 Exploratory Data Analysis

### 🔥 Correlation Heatmap

![Heatmap](images/heatmap.png)

### 📈 Disease Distribution

![Distribution](images/distribution.png)

---

## 🏗️ Project Structure

```
Disease-Prediction/
│── training_data.csv
│── test_data.csv
│── app.py
│── model.py
│── README.md
│── images/
```

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn, XGBoost
* Streamlit

---

## 🔄 Workflow

```mermaid
graph TD
A[Data Collection] --> B[Data Preprocessing]
B --> C[Exploratory Data Analysis]
C --> D[Model Training]
D --> E[Model Evaluation]
E --> F[Best Model Selection]
F --> G[Streamlit Deployment]
```

---

## 📈 Model Performance

| Model               | Performance |
| ------------------- | ----------- |
| Logistic Regression | Good        |
| SVM                 | Good        |
| Random Forest       | ⭐ Best      |
| XGBoost             | High        |

---

## 🖥️ Streamlit App

### 🚀 How to Run

#### 1. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost streamlit
```

#### 2. Run the Model

```bash
python model.py
```

#### 3. Run the Web App

```bash
streamlit run app.py
```

---

## 🌐 Deployment

You can deploy this project using:

* Streamlit Cloud
* Render
* Ngrok / Cloudflare Tunnel

---

## ✨ Features

✔ Multiple ML model comparison
✔ Data visualization
✔ Real-time prediction
✔ User-friendly interface
✔ Actionable health insights

---

## 🔗 Submission Requirements Completed

✔ LinkedIn Post
✔ GitHub Repository
✔ Model Implementation
✔ Evaluation Metrics (Precision, Recall, F1-score, ROC-AUC)

---

## 👨‍💻 Author

**Swadip Santra**
CodeAlpha Machine Learning Intern

---

## 📜 License

This project is developed for educational purposes under the CodeAlpha Machine Learning Internship Program.

