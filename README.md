# 🚗 Used Cars Analysis
## 📌 Project Overview

This project focuses on analyzing a large dataset of used cars to uncover insights about car production trends, pricing, transmission types, and more. The goal is to clean, preprocess, and analyze the dataset to answer business-driven questions and support decision-making.

## 🛠️ Tools & Technologies

Python: Data cleaning & analysis

Pandas / NumPy: Data preprocessing & transformation

Matplotlib / Seaborn: Data visualization & trend analysis

## 📂 Dataset

Source: Vehicles dataset (vehicles.csv)

Size: ~26 features before cleaning

Main features used: Year, price, type, fuel, transmission, title status, description

## 🔎 Data Cleaning & Preparation

Dropped irrelevant or duplicate columns (id, url, image_url, etc.)

Removed columns with >25% missing values

Handled missing data (mean for numeric, mode for categorical)

Converted posting_date to datetime and year to integer

Detected & removed outliers using IQR method

## 📊 Exploratory Data Analysis (EDA)

- Key analyses performed:

Car Production Trends → Most cars produced in 2017

Fuel Types vs. Years → No strong relationship

Car Title Status → “Clean” is the most common status

Transmission Popularity → Automatic dominates (≈80%)

Car Types → Sedan is the most popular

Pricing Trends → Prices rose until 2020, then dropped due to COVID-19 impact

## 📈 Visualizations

Count plots for categorical distributions

Line plots for trends over years

Pie charts for transmission breakdown

Boxplots for outlier detection

## 💡 Key Insights

Sedan and automatic cars dominate the used-car market.

Clean title status is most preferred.

Car prices peaked in 2020, followed by a decline influenced by the COVID-19 pandemic.
 - Solving the issues found in our dataest as much as possible.
 - Answeing some business questions by analyzing our dataset.

## 🚀 How to Run

1- Clone the repo:
  git clone https://github.com/your-username/used-cars-analysis.git
  
  cd used-cars-analysis

2- Install dependencies:
   pip install -r requirements.txt

3- Run the notebook or script:
   jupyter notebook used_cars_analysis.ipynb
## 📌 Future Work

Apply machine learning models to predict car prices

Perform feature engineering for better insights

Build an interactive dashboard for visualization
  

