# AgriSmart AI 🌱

## Intelligent Crop Recommendation System

AgriSmart AI is a machine learning-based crop recommendation system designed to recommend suitable crops based on soil and environmental conditions.

The system uses agricultural parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall to generate crop recommendations.

---

## 🎯 Project Objectives

- Analyze soil and environmental parameters.
- Develop and compare machine learning models.
- Select and optimize a suitable machine learning model.
- Provide explainable crop recommendations using Explainable AI.
- Develop a simple and user-friendly application.

---

## 📌 Project Scope

### In Scope

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Machine Learning Model Development
- Model Evaluation
- Hyperparameter Tuning
- Explainable AI
- Application Development
- Testing and Documentation

### Out of Scope

- Crop Disease Detection
- Crop Yield Prediction
- Fertilizer Recommendation
- Market Price Prediction
- Farmer Marketplace
- Weather Forecasting as a standalone system

---

## 📊 Dataset

The project uses a crop recommendation dataset containing soil and environmental parameters.

### Input Features

| Feature | Description |
|---|---|
| N | Nitrogen |
| P | Phosphorus |
| K | Potassium |
| Temperature | Environmental temperature |
| Humidity | Environmental humidity |
| pH | Soil pH |
| Rainfall | Rainfall |

### Target

`label` — Recommended crop.

The dataset contains **2,200 samples and 22 crop classes**.

---

## 🤖 Machine Learning

The project investigates multiple machine learning approaches for crop classification and recommendation.

Models may include:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- XGBoost

Model performance will be evaluated using appropriate classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score

---

## 🔍 Explainable AI

AgriSmart AI uses Explainable AI techniques to help users understand the factors influencing the model's prediction.

The project uses **SHAP (SHapley Additive exPlanations)** to provide explanations for individual predictions and identify important features.

---

## 🖥️ Application

The system is planned to provide a simple user interface where users can enter soil and environmental parameters and receive:

- Recommended crop
- Prediction probability
- Top candidate crops
- Explanation of the prediction

---

## 🛠️ Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- Streamlit
- Git & GitHub
- Jupyter Notebook

---

## 📁 Project Documentation

The project documentation is organized as follows:

```text
Documentation/
│
├── Project_Planning_Management.pdf
├── Literature_Review.pdf
└── Requirements_Gathering.pdf
