# 📊 Unemployment Analysis in India

This project analyzes unemployment trends in India using real-world data.  
It focuses on understanding how unemployment rates changed over time, especially during the COVID-19 period, and identifies seasonal and yearly patterns.

---

## 📌 Project Overview

In this project, we:
- Load and clean the unemployment dataset
- Remove duplicate and missing values
- Convert date columns into proper datetime format
- Analyze unemployment trends over time
- Study the impact of COVID-19 on unemployment
- Explore monthly and yearly unemployment patterns
- Visualize data using line plots
- Provide key insights based on analysis

---

## 📂 Dataset Information

- Dataset Name: Unemployment in India  
- File Name: `Unemployment in India.csv`

### Key Columns Used
- Region  
- Date  
- Frequency  
- Unemployment_Rate  
- Employed  
- Labour_Participation_Rate  
- Area  

---

## 🛠 Technologies & Libraries Used

- Python  
- Pandas – Data cleaning and manipulation  
- Matplotlib – Data visualization  
- Warnings – To suppress unnecessary warnings  

---

## 🔄 Steps Performed

### Data Loading
- Loaded the dataset using pandas.

### Data Cleaning
- Removed duplicate rows.
- Removed rows with null values.
- Cleaned and renamed column names for readability.

### Date Processing
- Converted the Date column to datetime format.
- Extracted Year and Month for trend analysis.

### Overall Unemployment Trend
- Calculated average unemployment rate per date.
- Visualized the trend using a line plot.

---

## 🦠 COVID-19 Impact Analysis

- COVID-19 period considered from March 2020 onwards.
- Compared unemployment rates before and during COVID-19.
- Visualized the comparison using line graphs.

---

## 📅 Monthly & Yearly Trend Analysis

- Calculated average unemployment rates for each month and year.
- Plotted monthly unemployment trends across different years.
- Identified seasonal patterns in unemployment.

---

## 📈 Visualizations Included

- Average unemployment rate over time
- Impact of COVID-19 on unemployment
- Monthly unemployment trends across years

All visualizations are created using Matplotlib for simplicity and clarity.

---

## 🧠 Key Insights

- Unemployment rates increased sharply during the COVID-19 period.
- Highest spikes occurred around April and May 2020 due to lockdowns.
- Before COVID-19, unemployment remained relatively stable with seasonal changes.
- COVID-19 caused uneven unemployment impacts across regions.
- Such analysis can help policymakers design better recovery strategies.

---

## 🚀 How to Run the Project

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git

### Step 2: Install required libraries
```bash
pip install pandas matplotlib

### Step 3: Run the Python script
```bash
python unemployment_analysis.py

