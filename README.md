# Indian-startup-funding-analysis
Data cleaning, exploratory data analysis and visualization of Indian startup funding data using Python.
# Indian Startup Funding Analysis 📊

## 📌 Project Overview

This project analyzes funding received by Indian startups using Python.

The main purpose of this project is to clean the dataset, analyze startup funding patterns, and create visualizations to understand trends in the Indian startup ecosystem.

## 🎯 Objectives

- Clean the startup funding dataset
- Handle missing values
- Check and remove duplicate records
- Convert data into suitable data types
- Detect funding outliers
- Analyze startup industries and cities
- Analyze investment types
- Find the most funded startups
- Create meaningful visualizations
- Generate useful insights from the data

## 📂 Dataset

The dataset used in this project is the **Indian Startup Funding Dataset**.

📂 [Dataset – Indian Startup Funding](https://www.kaggle.com/datasets/sudalairajkumar/indian-startup-funding)

It contains information such as:

- Startup Name
- Industry Vertical
- SubVertical
- City Location
- Investors Name
- Investment Type
- Funding Amount
- Funding Date

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 🔍 Data Cleaning

The dataset was cleaned before analysis.

The following steps were performed:

1. Checked the dataset structure and columns
2. Identified missing values
3. Filled missing categorical values with `Unknown`
4. Checked duplicate records
5. Converted dates into proper date format
6. Extracted the year from the date
7. Cleaned the funding amount column
8. Converted funding amounts into numerical values
9. Detected outliers using the IQR method

## 📊 Data Analysis & Visualizations

The project includes visualizations such as:

- Total Startup Funding by Year
- Top 10 Startup Industries
- Top 10 Indian Cities by Number of Startups
- Top Investment Types
- Top 10 Most Funded Startups
- Top Industries by Total Funding
- Top Cities by Total Funding
- Funding Amount Distribution
- Normal Values vs Outliers

These visualizations help us understand how startup funding is distributed across different years, industries, cities, and startups.

## 💡 Key Insights

From the analysis, we can understand that:

- Startup funding varies significantly across different years.
- Some industries receive much more funding than others.
- Major cities contribute a large portion of the startup ecosystem.
- A few startups receive very large amounts of funding.
- Funding data contains several high-value outliers.
- Investment types vary across startups.
- Startup funding is not evenly distributed.

## 📈 Outlier Detection

The **Interquartile Range (IQR)** method was used to identify unusually high or low funding values.

Outliers were not removed because large investments can represent genuine startup funding and may provide useful information for analysis.

## ✅ Conclusion

This project demonstrates the complete process of data analysis, starting from raw data cleaning and ending with meaningful insights.

Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn were used to clean, analyze, and visualize the Indian startup funding data.

The project helps us understand funding trends and the overall structure of the Indian startup ecosystem.

## 👩‍💻 Project By

**Hani Nayi & Jiya Patel**

Indian Startup Funding Analysis  
Data Analysis Project
