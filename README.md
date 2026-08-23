# delhi_car_price_prediction
Machin learning model for price prediction.

# 🚗 Delhi Car Price Prediction

### End-to-End Machine Learning Regression Project | Python | Pandas | Scikit-learn

An end-to-end Machine Learning project for predicting the selling price of used cars in Delhi using vehicle characteristics such as manufacturing year, kilometers driven, fuel type, transmission, ownership history, and other available features.

This project demonstrates the complete Machine Learning workflow, including **data exploration, data cleaning, feature engineering, preprocessing, model training, model comparison, evaluation, and model persistence**.

---

## 📌 Project Overview

The used-car market is influenced by multiple factors, making it difficult to estimate a fair selling price using simple rules.

The objective of this project is to build a regression-based Machine Learning model that can learn patterns from historical used-car data and estimate the expected selling price of a vehicle.

### Project Objective

> **Build and evaluate regression models to predict used-car prices and identify the best-performing model based on appropriate evaluation metrics.**

---

## 🎯 Business Problem

Used-car prices depend on several factors, including:

- Vehicle age
- Kilometers driven
- Fuel type
- Transmission type
- Ownership history
- Mileage
- Engine specifications
- Power
- Seating capacity

A data-driven pricing model can help support:

- Used-car valuation
- Price estimation
- Buyer and seller decision-making
- Market analysis
- Automated vehicle-price prediction

---

## 📊 Dataset

The project uses a Delhi used-car dataset containing **899 records**.

The dataset contains information about different characteristics of used vehicles and their selling prices.

### Key Features

| Feature | Description |
|---|---|
| `Name` | Car make/model |
| `Location` | Location of the vehicle |
| `Year` | Manufacturing year |
| `Kilometers_Driven` | Distance driven by the vehicle |
| `Fuel_Type` | Type of fuel used |
| `Transmission` | Manual or Automatic |
| `Owner_Type` | Previous ownership information |
| `Mileage` | Vehicle mileage |
| `Engine` | Engine capacity |
| `Power` | Engine power |
| `Seats` | Seating capacity |
| `Price` | Target variable — selling price |

---

# 🛠️ Technologies & Tools

### Programming Language
- Python

### Data Analysis
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### Model Persistence
- Joblib

### Development
- Jupyter Notebook
- Git
- GitHub

---

# 🔄 Machine Learning Workflow

```text
Raw Dataset
     │
     ▼
Data Loading & Inspection
     │
     ▼
Data Cleaning
     │
     ▼
Exploratory Data Analysis
     │
     ▼
Feature Engineering
     │
     ▼
Data Preprocessing
     │
     ▼
Train-Test Split
     │
     ▼
Model Training
     │
     ├── Linear Regression
     ├── Random Forest
     └── Gradient Boosting
     │
     ▼
Model Evaluation
     │
     ▼
Model Comparison
     │
     ▼
Best Model Selection
     │
     ▼
Model Serialization
