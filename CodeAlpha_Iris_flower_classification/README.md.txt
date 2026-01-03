# 🌸 Iris Flower Classification

This project demonstrates a machine learning classification task using the famous Iris dataset.
The goal is to classify iris flowers into different species based on their physical features.

## 📌 Project Overview

In this project, we:

-Load and clean the Iris dataset

-Remove duplicate and missing values

-Train a machine learning model to classify flower species

-Evaluate model performance

-Visualize data for better understanding

## 📂 Dataset

File: Iris.csv

## Features used:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Target column: Species

🛠 Technologies Used

-Python

-Pandas – data loading and cleaning

-Matplotlib & Seaborn – data visualization

-Scikit-learn – machine learning model and evaluation

## 🔄 Steps Performed

-Data Loading

-Read the dataset using pandas

-Data Cleaning

-Remove null values

-Remove duplicate records

-Feature Selection

-Selected flower measurements as input features

-Species used as the target variable

-Data Splitting

-Split data into training and testing sets (80% / 20%)

-Feature Scaling

-Applied StandardScaler for better model performance

-Model Training

-Used Random Forest Classifier

-Model Evaluation

-Accuracy score

-Classification report

-Confusion matrix

-Visualization

-Scatter plot of Petal Length vs Petal Width colored by species

## 📊 Model Performance

-Accuracy: Printed after model prediction

-Classification Report: Precision, recall, and F1-score

-Confusion Matrix: Shows correct and incorrect predictions

## 📈 Visualization

-A scatter plot is generated to show how different iris species are distributed based on:

-Petal Length

-Petal Width

This helps visually understand how well the classes are separated.

##🚀 How to Run the Project

- 1.Clone the repository:
-git clone https://github.com/your-username/your-repo-name.git

- 2.Install required libraries:
- pip install pandas matplotlib seaborn scikit-learn

- 3.How to run ?
- python iris_classification.py
