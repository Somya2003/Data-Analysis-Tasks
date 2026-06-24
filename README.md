# Data Analysis Project (Titanic & Advertising Dataset)

## Project Overview
This project focuses on data analysis using Python. It includes data cleaning, exploratory data analysis (EDA), visualization, descriptive statistics, and data aggregation using real-world datasets like Titanic and Advertising dataset.

The goal is to extract useful insights from raw data using Pandas, NumPy, Matplotlib, and Seaborn.

---

## Datasets Used
- Titanic Dataset (Passenger survival analysis)
- Advertising Dataset (Sales analysis)

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Steps

### 1. Data Cleaning
- Removed irrelevant columns (PassengerId, Name, Cabin, Ticket)
- Handled missing values:
  - Age → filled with mean/median
  - Fare → filled with mean
  - Embarked → handled missing values
- Prepared clean dataset for analysis

---

### 2. Exploratory Data Analysis (EDA)
- Age distribution analysis
- Fare distribution analysis
- Gender count analysis
- Survival analysis by class and age
- Heatmap for missing values and correlation

---

### 3. Data Visualization
- Scatter plot (Age vs Fare)
- Bar chart (Passenger Class distribution)
- Pie chart (Gender distribution)
- Boxplot (Age vs Survival)
- Pairplot for feature relationships

---

### 4. Descriptive Statistics
- Used describe() for statistical summary
- Calculated mean, median, mode
- Checked data types and handled conversions
- Analyzed data distribution

---

### 5. Data Aggregation
- Created Sales categories (Low, Medium, High)
- Used groupby() for analysis
- Applied aggregation functions (mean, sum, count)
- Used pivot tables for insights

---

## Key Insights
- Passenger class and gender strongly affect survival rate
- Higher class passengers had higher survival chances
- TV advertising has strong impact on sales
- Grouping helps in better understanding of data patterns

---

## How to Run
1. Clone the repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Run the Jupyter Notebook

---

## Conclusion
This project demonstrates end-to-end data analysis workflow including data cleaning, visualization, and insights extraction using Python.


