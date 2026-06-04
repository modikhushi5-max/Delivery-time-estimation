# Delivery Time Estimation

## Project Overview

This project predicts the estimated delivery time of orders using Machine Learning techniques. The model analyzes various order and delivery-related features to estimate the expected delivery duration.

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Model Training
* Delivery Time Prediction
* Streamlit-based User Interface

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Streamlit
* Jupyter Notebook

## Project Structure

```text
porter_final_ml_2.ipynb    # Model training and analysis
app.py                     # Streamlit application
model.pkl                  # Trained machine learning model
```

## Dataset

This project uses the Porter Delivery Time Estimation dataset obtained from Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/ranitsarkar01/porter-delivery-time-estimation/data

### Dataset Information

* Source: Kaggle
* Records: Approximately 200,000 delivery records
* Domain: Food Delivery Time Prediction
* Target Variable: Delivery Time

The dataset contains order, restaurant, and delivery-related features that are used to train a machine learning model for estimating delivery times.
[Estimating Delivery Time for Logistics Using Regression.pptx](https://github.com/user-attachments/files/28586270/Estimating.Delivery.Time.for.Logistics.Using.Regression.pptx)



## How to Run

1. Clone the repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the Streamlit application

```bash
streamlit run app.py
```

## Model Output

The trained model predicts the estimated delivery time based on the input features provided by the user.

## Author

Khushi Modi
