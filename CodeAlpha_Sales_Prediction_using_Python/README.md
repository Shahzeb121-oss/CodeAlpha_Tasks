# Advertising Sales Prediction

This project predicts sales based on advertising spending on different platforms such as TV, Radio, and Newspaper. It uses a simple machine learning model to understand how each advertising channel impacts sales.

---

## Project Overview

- Load and clean advertising data  
- Use TV, Radio, and Newspaper ad spend as features  
- Predict sales using Linear Regression  
- Show how much each ad type increases sales  
- Provide a simple business tip based on model results  
- Visualize the impact of each advertising channel  

---

## Dataset

- File: `Advertising.csv`  
- Features: TV, Radio, Newspaper (advertising spend)  
- Target: Sales  

---

## Technologies Used

- Python  
- Pandas (data handling)  
- Scikit-learn (machine learning)  
- Matplotlib (visualization)  

---

## How It Works

1. **Data Cleaning**  
   Remove empty and duplicate rows.

2. **Feature Selection**  
   Use ad spending columns as inputs and sales as the target.

3. **Model Training**  
   Train a Linear Regression model on 80% of the data.

4. **Prediction**  
   Predict sales for the remaining 20%.

5. **Insights**  
   See how each ad channel affects sales and find the best ad channel to invest in.

6. **Visualization**  
   Bar chart showing sales increase per unit spent on each ad type.

---

## Sample Output

How advertising affects sales:
TV ads increase sales by 0.047 for each unit spent
Radio ads increase sales by 0.179 for each unit spent
Newspaper ads increase sales by 0.003 for each unit spent

Base sales without advertising: 2.91

Tip: Spend more on Radio ads because it increases sales the most!

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. Install dependencies:

pip install pandas scikit-learn matplotlib

3. Run the script:

python advertising_sales_prediction.py