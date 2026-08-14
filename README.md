# Steel Industry Energy Consumption Prediction Using Machine Learning

A machine learning project for predicting electricity consumption in a steel manufacturing environment using electrical and operational parameters.

## Project Overview

Energy consumption is an important operational factor in steel manufacturing. Accurate prediction of electricity usage can help organizations understand consumption patterns and support better energy management.

This project develops and evaluates multiple regression models to predict `Usage_kWh` using electrical and operational features.

The project follows an end-to-end machine learning workflow:

- Data exploration
- Data cleaning
- Exploratory data analysis
- Feature engineering
- Categorical encoding
- Feature scaling
- Train-test splitting
- Regression model training
- Model comparison
- Model evaluation

## Objective

The primary objective is to predict electricity consumption (`Usage_kWh`) based on electrical and operational conditions recorded in a steel manufacturing environment.

## Dataset

The dataset contains **35,040 observations and 11 variables**.

### Target Variable

- `Usage_kWh` — Electricity consumption in kilowatt-hours.

### Key Features

- Lagging Reactive Power
- Leading Reactive Power
- CO₂ emissions
- Power Factor
- NSM (Number of Seconds from Midnight)
- Week Status
- Day of Week
- Load Type

## Machine Learning Problem

This is a **supervised regression problem**.

The models are trained to estimate continuous electricity consumption based on the available electrical and operational parameters.

## Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
