# Medical Insurance Prediction Model

This repository contains a prediction model built to estimate **medical insurance charges** based on several factors using **Linear Regression**.

---

## Libraries Used

The following libraries were utilized for data manipulation, visualization, and model building:

- **Pandas**: For data manipulation and handling.
- **NumPy**: To create arrays or matrices for mathematical operations.
- **Matplotlib (pyplot)**: Provides a simple interface to create various types of line plots, bar charts, etc.
- **Seaborn**: Used for statistical data visualization, offering a high-level interface to create attractive and informative graphics.
- **Scikit-Learn**: Essential for predictive data analysis, preprocessing, and model selection (functions like `train_test_split`, `LinearRegression`, and `metrics`).

---

## Features and Target Variable

The following features were considered:

- **Age**
- **BMI**
- **Children**
- **Region**

The **target feature** was **charges**.

A model was trained using the above features as inputs, with the goal of predicting medical insurance charges.

---

## Model Training

The model was trained with **Linear Regression** to establish a predictive relationship between the selected features and the target variable, `charges`.

---

## Repository Structure

- The main code can be found in **MedicalInsurance2.ipynb**
- **insurance.csv**: The dataset used for training, sourced from Kaggle ([download link](https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download)).

