# Used Car Price Prediction 🚗

A machine learning regression project that predicts the price of used cars based on vehicle characteristics such as brand, model, year, mileage, fuel type, engine, transmission, accident history, and other attributes.

## 📌 Project Overview

This project implements an end-to-end machine learning workflow for **used car price prediction**.

The notebook focuses on:

* Understanding and exploring the raw dataset
* Cleaning and preprocessing the data
* Handling missing and inconsistent values
* Preparing numerical and categorical features
* Building machine learning regression models
* Evaluating model performance
* Comparing model results

The project is implemented in Python using **Pandas, NumPy, Scikit-learn, and KaggleHub**.

## 📊 Dataset

The dataset is the **Used Car Price Prediction Dataset** from Kaggle.

* **Source:** Kaggle
* **Dataset:** Used Car Price Prediction
* **Number of rows:** 4,009
* **Number of columns:** 12
* **Target variable:** `price`

### Features

The dataset contains the following vehicle attributes:

| Feature        | Description                      |
| -------------- | -------------------------------- |
| `brand`        | Vehicle manufacturer             |
| `model`        | Vehicle model                    |
| `model_year`   | Year of the vehicle              |
| `milage`       | Vehicle mileage                  |
| `fuel_type`    | Type of fuel                     |
| `engine`       | Engine specifications            |
| `transmission` | Transmission type                |
| `ext_col`      | Exterior color                   |
| `int_col`      | Interior color                   |
| `accident`     | Accident history                 |
| `clean_title`  | Clean title information          |
| `price`        | Used car price — target variable |

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* KaggleHub
* Jupyter Notebook / Google Colab

## 🔄 Machine Learning Workflow

The project follows a typical machine learning pipeline:

```text
Raw Dataset
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Feature Preprocessing
     ↓
Train / Test Split
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Model Comparison
```

## 📁 Project Structure

```text
Used-Car-Price-Prediction/
│
├── Used_Car_Price_Prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Used-Car-Price-Prediction.git
cd Used-Car-Price-Prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open:

```text
Used_Car_Price_Prediction.ipynb
```

You can run the notebook using **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.

## 📥 Dataset Access

The notebook uses KaggleHub to download the dataset:

```python
import kagglehub

path = kagglehub.dataset_download(
    "taeefnajib/used-car-price-prediction-dataset"
)
```

The dataset does not need to be included directly in this repository.

## 🎯 Objective

The main objective of this project is to develop a regression model capable of estimating used car prices from available vehicle information.

This project demonstrates practical machine learning skills including:

* Data preprocessing
* Feature engineering
* Categorical encoding
* Regression modeling
* Model evaluation
* Machine learning pipeline construction

## 📈 Results

Model performance and evaluation results are available directly in the Jupyter notebook.

The notebook contains the complete experimentation and evaluation process.

## 🔮 Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Feature engineering from engine specifications
* More advanced ensemble models
* Cross-validation
* Deployment using Streamlit or Flask
* Creating an interactive used-car price prediction application


