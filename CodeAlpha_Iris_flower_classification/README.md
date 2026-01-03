# 🌸 Iris Flower Classification

This project demonstrates a machine learning classification task using the famous **Iris dataset**.  
The goal is to classify iris flowers into different species based on their physical features.

---

## 📌 Project Overview

This project covers the complete machine learning workflow:

- Load and clean the Iris dataset  
- Remove duplicate and missing values  
- Train a machine learning model to classify iris flower species  
- Evaluate the model using standard metrics  
- Visualize the data for better understanding  

---

## 📂 Dataset Information

- **Dataset Name:** Iris Dataset  
- **File Name:** `Iris.csv`  

### Features Used
- SepalLengthCm  
- SepalWidthCm  
- PetalLengthCm  
- PetalWidthCm  

### Target Column
- Species  

---

## 🛠 Technologies & Libraries Used

- **Python**
- **Pandas** – Data loading and cleaning  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical visualization  
- **Scikit-learn** – Machine learning model and evaluation  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Loaded the dataset using pandas.

### 2️⃣ Data Cleaning
- Removed rows with missing values.
- Removed duplicate records.

### 3️⃣ Feature Selection
- Selected sepal and petal measurements as input features.
- Used species column as the target label.

### 4️⃣ Data Splitting
- Split the dataset into:
  - 80% training data
  - 20% testing data

### 5️⃣ Feature Scaling
- Applied **StandardScaler** to normalize feature values.

### 6️⃣ Model Training
- Trained a **Random Forest Classifier** for multi-class classification.

### 7️⃣ Model Evaluation
- Calculated accuracy score.
- Generated classification report.
- Displayed confusion matrix.

### 8️⃣ Data Visualization
- Created a scatter plot of **Petal Length vs Petal Width** colored by species.

---

## 📊 Model Performance

- **Accuracy:** Displayed after prediction  
- **Classification Report:** Precision, Recall, F1-score  
- **Confusion Matrix:** Shows correct and incorrect predictions  

---

## 📈 Visualization Output

The scatter plot visually shows how different iris species are separated based on:

- Petal Length  
- Petal Width  

This helps understand feature importance and class separation.

---

## 🚀 How to Run This Project

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git

### Step 2: Install required libraries
pip install pandas matplotlib seaborn scikit-learn

### Step 3: Run the Python script
python iris_classification.py
