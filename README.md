# Exploratory Data Analysis (EDA) on Student Performance Dataset

![Python](https://img.shields.io/badge/python-3.x-blue.svg)

This repository contains an Exploratory Data Analysis (EDA) of the Student Performance dataset. The analysis covers data exploration, cleaning, and visualization to understand student performance metrics better.

# Dataset
 -The dataset used is StudentsPerformance.csv, which includes student performance data across different subjects, parental level of education, race/ethnicity, and gender.

      # Load the dataset
      data = pd.read_csv(r"D:\Projects\EDA\StudentsPerformance.csv")

      #link https://www.kaggle.com/datasets/spscientist/students-performance-in-exams




# Steps and Analysis

- Loading Libraries and Dataset
       
   Imported necessary libraries for data manipulation and visualization.Loaded the dataset from a local file path.
       
- Initial Data Exploration
       
   Displayed the first and last few rows of the dataset to understand its structure.Checked the shape of the dataset and reviewed basic statistics.
Examined column names and unique values in specific columns.Checked for missing values to assess data completeness.

- Data Cleaning
       
   Removed unnecessary columns that are not relevant for the analysis, specifically race/ethnicity and parental level of education.
 
- Correlation Analysis
       
   Selected numerical columns and computed their correlations.Visualized the correlation matrix using a heatmap to understand the relationships between different scores.
 
- Pair Plot
       
   Created pair plots to explore the relationships between math, reading, and writing scores.
 
- Relationship Plots
       
   Visualized relationships between different scores (math, reading, writing) with color-coded gender information to understand how gender affects performance.
 
- Distribution Plots
       
   Plotted histograms with Kernel Density Estimate (KDE) for math, reading, and writing scores to visualize their distributions.
 
- Box Plot
       
   Created a box plot for math scores to visualize the distribution and detect potential outliers.
       
# Summary

   This analysis provides insights into student performance through various visualizations, helping to understand the distribution of scores, relationships between different subjects, and the impact of gender on performance.


## Requirements

```
pip install -r requirements.txt
```


---
**Last updated:** 2026-08-10
