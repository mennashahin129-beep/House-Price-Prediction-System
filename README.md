# House Price Prediction System

## Overview
This project is a Machine Learning-based House Price Prediction System developed using Python and Linear Regression.  
The model predicts house prices based on property features such as:
- Total Area (Square Feet)
- Number of Bathrooms
- Number of Balconies
- Number of Bedrooms (BHK)

The project also includes data preprocessing, outlier handling, visualization, and deployment using Gradio.

---

## Features
- Data Cleaning & Preprocessing
- Feature Engineering
- Outlier Detection using IQR
- Exploratory Data Analysis (EDA)
- Linear Regression Model
- Interactive Web Interface using Gradio

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Gradio

---

## Data Preprocessing
The preprocessing steps include:
- Extracting BHK values from the `size` column
- Converting `total_sqft` values into numerical format
- Handling missing values
- Removing outliers using the IQR method

---

## Model
The project uses:
- Linear Regression

The model is trained using:
- `train_test_split`
- Numerical housing features

---

## Input Features
Users can enter:
- Area (Square Feet)
- Number of Bathrooms
- Number of Balconies
- Number of Bedrooms (BHK)

The system then predicts the estimated house price.

---

## How to Run

### Install Requirements
```bash
pip install -r requirements.txt
#####don't forget to install dataset
