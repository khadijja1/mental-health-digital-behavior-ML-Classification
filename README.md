📘 Mental Health & Digital Behavior — Classification Using Logistic Regression
A Beginner Machine Learning Project Exploring How Digital Behavior Influences Mental Focus

📌 Project Overview
This project explores the relationship between digital behavior (screen time, notifications, app switching frequency) and mental health indicators, specifically the focus score.
The goal was to classify whether a person has a decline in focus (1) or not (0) based on features extracted from the dataset.

This project highlights my learning journey in:

Core Python programming

Data handling with NumPy and Pandas

Visualization using Matplotlib

Basic feature engineering

Manual implementation of Logistic Regression (gradient descent, sigmoid, cost function, normalization)

The dataset used:
mental_health_and_digital_behavior_data.csv, sourced from Kaggle.

📂 Project Structure
├── Mental_health_and_Digitalbehavior.ipynb   # Jupyter notebook with full workflow

├── mental_health_digital_behavior_data.csv   # Dataset used (from Kaggle)

└── README.md                                 # Documentation (this file)

Problem Statement
Digital device usage is often linked to declining mental well-being.

This beginner project studies:

How screen time affects focus

How notification overload impacts attention

Whether digital habits predict a “decline in focus”

🔍 What This Project Does


✔ Loads and explores the dataset
Checks missing values

Summary statistics

Data distribution plots

Scatter plots for behavioral correlations

✔ Feature Engineering

Selected features:

notification_count

daily_screen_time_min

num_app_switches

Target variable creation:

focus_target → 1 if focus score ≥ 7, else 0

Z-score normalization performed manually:

X_norm = (X - mean) / std
✔ Manual Implementation of Logistic Regression
Instead of using Scikit-Learn, I coded:

Sigmoid function

Cost function

Gradient calculation

Gradient descent loop

Predictions and evaluation

This helped me deeply understand the internal mechanics of ML algorithms.

✔ Model Evaluation

Predictions for test set

Accuracy score

Classification report

📊 Visualizations Included
Distribution of screen time

Scatter plots showing relationships between features

Correlation matrix heatmap

These help understand which digital behaviors relate most to declining focus.

🔧 Technologies Used
Python

NumPy

Pandas

Matplotlib

Scikit-Learn (only for train-test split & evaluation)

Jupyter Notebook

🎯 Project Goal
Learn the machine learning workflow

Understand logistic regression deeply

Practice feature engineering

Build intuition for data relationships

Apply core Python libraries confidently



