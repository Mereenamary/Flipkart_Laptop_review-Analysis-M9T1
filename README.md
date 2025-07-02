# Flipkart Laptop Review – Exploratory Data Analysis (EDA)

This project presents a structured exploratory analysis of laptop reviews sourced from Flipkart. The objective is to identify patterns in customer sentiment, assess product visibility, and understand which features influence high or low ratings. The findings contribute towards developing a decision support system (DSS) for evaluating product performance.

## Overview

This analysis is part of a Decision Support Systems (DSS) assignment for the PG Diploma in Artificial Intelligence at IDEA College, Malta. The dataset consists of 600+ laptop product entries along with user ratings, written reviews, and product specifications.

The notebook uses Python, Jupyter, and libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn to clean, visualise, and interpret the data.

## Contents

### Introduction to DSS
- Brief explanation of what Decision Support Systems are
- Relevance of DSS in e-commerce and review mining
- Evolution of DSS over time (Power, 2002; Turban et al., 2015)

### Data Loading and Cleaning
- Importing dataset and required libraries
- Removing duplicates
- Converting text-based numeric columns to integers
- Initial structure and column overview

### Descriptive Analysis
- Summary statistics (mean, median, standard deviation)
- Histograms and boxplots of ratings and reviews
- Detection of skewness and outliers

### Relationship Analysis
- Correlation between number of ratings and average rating
- Scatter plot with regression line
- Log transformation to improve interpretability

### Review Content Analysis
- Text processing of review content
- Frequency plots of words in positive and negative reviews
- Identification of commonly mentioned features in good vs bad reviews

###  Product-Level Insights
- Top 10 most-reviewed laptops
- Top 10 highest-rated laptops with minimum 50 reviews
- Review length vs star rating analysis
- Correlation heat-map of key variables

### Final Summary and Recommendations
- Key findings summarised in bullet points
- Practical implications for product managers and marketers
- Recommendations for DSS integration

### References
- All academic references are provided in British Harvard style

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scipy

## Author

MEREENA MARY ABRAHAM  
PG Diploma in Artificial Intelligence  
IDEA College, Malta  
Student ID: INT-IA-0000530
Cohort: 2
