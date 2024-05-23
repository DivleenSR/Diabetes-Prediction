# Diabetes Prediction Using PySpark Machine Learning Library (MLLIB)

## Project Overview

This project focuses on three main objectives:
1. Building a Logistic Regression Classifier using PySpark MLLIB.
2. Setting up PySpark on the Colab Environment.
3. Working with Spark DataFrames.

By the end of this project, you will have a logistic regression classifier built using the PySpark Machine Learning library (MLLIB) and Python to classify diabetic and non-diabetic patients. You will also be able to set up and work with PySpark on the Google Colab Environment, as well as clean and prepare data for analysis.

## Problem Statement

The goal of this project is to build a model that can predict whether a patient has diabetes based on various medical attributes. Using the Pima Indians Diabetes Database, we will perform data preprocessing, feature selection, model training, and evaluation to create a reliable diabetes prediction model.

## Data Description

The dataset contains the following features:

- **Pregnancies**: Number of times pregnant.
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test (mg/dL). A value between 140 and 200 mg/dL indicates impaired glucose tolerance (pre-diabetes), while a value of 200 mg/dL or higher is used to diagnose diabetes.
- **Blood Pressure**: Diastolic blood pressure (mmHg). A diastolic BP > 90 indicates high blood pressure (high probability of diabetes), while a diastolic BP < 60 indicates low blood pressure (less probability of diabetes).
- **Skin Thickness**: Triceps skin fold thickness (mm). Normal value in women is 23mm. Higher values indicate obesity and increased chances of diabetes.
- **Insulin**: 2-hour serum insulin (mu U/ml). Normal insulin level ranges from 16-166 mIU/L. Values above this range can be alarming.
- **BMI**: Body mass index (weight in kg/height in m²). A BMI of 18.5 to 25 is normal, 25 to 30 is overweight, and 30 or above is obese.
- **Diabetes Pedigree Function**: Indicates diabetes history in relatives and the genetic relationship of those relatives with the patient. Higher values indicate a higher likelihood of diabetes.
- **Age**: Age of the patient (years).
- **Outcome**: Class variable (0 or 1) where ‘0’ denotes no diabetes and ‘1’ denotes diabetes.

## Project Structure

The project is divided into several tasks:

### Task 1: Introduction & Install Dependencies
- Introduction to the purpose of the project and the dataset.
- Install PySpark on the Google Colab Environment.
- Create and run a Spark session.

### Task 2: Clone and Explore the Dataset
- Clone the Diabetes Dataset from the GitHub repository.
- Work with PySpark DataFrame.
- Explore the dataset to get the total number of rows and columns, extract meaningful information, and analyze summary statistics.

### Task 3: Data Cleaning and Preparation
- Check for null values.
- Remove or replace unnecessary values in the dataset.

### Task 4: Correlation Analysis and Feature Selection
- Conduct correlation analysis among the input and output variables.
- Select the input features.

### Task 5: Build a Logistic Regression Classifier
- Split the dataset into training and testing sets.
- Build and train the logistic regression model.

### Task 6: Evaluate & Save the Model
- Evaluate and test the model on the test data.
- Save the model to disk.
- Load the saved logistic regression model on Colab to predict on a new set of data.

### Task 7: Model Prediction on a New Set of Unlabelled Data
- Create a Spark DataFrame.
- Use the saved model to predict diabetes on the new set of test data.

## Project Setup

1. **Clone the repository:**

    git clone https://github.com/DivleenSR/diabetes-prediction.git
    
2. **Navigate to the project directory:**
   
    cd diabetes-prediction
    
3. **Install the required packages:**
    
    pip install -r requirements.txt
    

