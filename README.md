# Titanic EDA — Exploratory Data Analysis

Exploratory data analysis on the Titanic dataset to uncover survival patterns
using Python, Pandas, NumPy and Matplotlib.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- 891 passengers, 12 columns

## Questions Answered
1. What was the overall survival rate?
2. Did passenger class affect survival?
3. Did gender affect survival?
4. What age group had the highest survival rate?
5. Which port of embarkation had the highest survival rate?
6. Did fare paid correlate with survival?

## Key Findings
- Only 38% of passengers survived overall
- 1st class passengers had the highest survival rate
- Females survived at ~74% vs males at ~19%
- Age group 26–53 had the highest survival count
- Southampton (S) had the most survivors (217) but Cherbourg (C) had the highest survival rate at 55%
- Survivors paid on average higher fares than non-survivors

## Project Structure
titanic-eda/
├── titanic_eda.ipynb   ← main analysis notebook
├── train.csv           ← dataset
└── README.md

## How to Run
1. Clone the repo
   git clone https://github.com/hima933/titanic-eda

2. Open in Google Colab
   Go to colab.google.com → File → Upload notebook → select titanic_eda.ipynb

3. Upload train.csv when prompted

4. Run all cells (Runtime → Run all)

## Tools Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Google Colab

## What I Learned
- How to clean real-world data (null values, duplicates, type conversion)
- How to use groupby to find patterns across categories
- How to visualise data insights using bar charts and histograms
- How conclusions from count data vs rate data can be completely different
