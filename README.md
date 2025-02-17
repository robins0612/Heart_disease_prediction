# Heart Disease Prediction

## Overview
This project aims to predict the likelihood of heart disease in individuals using machine learning models. The workflow includes data preprocessing, model training, evaluation, and deployment. Python libraries such as pandas, numpy, and scikit-learn are used for data handling and machine learning tasks.

## Features
- Importing and preprocessing the dataset
- Splitting the data into training and testing sets
- Implementing and training a Logistic Regression model
- Evaluating the model's accuracy using metrics
- Insights into feature importance and performance evaluation

## Dataset
The dataset used in this project contains various health metrics and attributes, including:
- Age
- Sex
- Resting blood pressure
- Cholesterol levels
- Maximum heart rate achieved
- Fasting blood sugar levels
- Electrocardiographic results
- Exercise-induced angina
- Oldpeak (ST depression induced by exercise)
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia classification

Ensure the dataset is placed in the same directory as the notebook or update the file path in the code. If the dataset source is public, please include its link here.

## Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Required Python libraries:
  - numpy
  - pandas
  - scikit-learn

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the notebook in Google Colab or locally:
   - For Google Colab:
     - Upload the notebook file `Heart_Disease_Prediction.ipynb` to your Google Drive.
     - Open the notebook in Colab and set the runtime to include GPU if necessary.
   - For local setup:
     ```bash
     jupyter notebook Heart_Disease_Prediction.ipynb
     ```
2. Follow the steps in the notebook:
   - Load and preprocess the dataset
   - Train the Logistic Regression model
   - Evaluate the model's accuracy
   - Analyze the results

## Results
- Prediction accuracy of the Logistic Regression model
- Insights into the importance of features in determining heart disease likelihood
