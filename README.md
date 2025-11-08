# Heart-Disease-Dataset-Analysis

This project explores a heart disease dataset to uncover factors that may contribute to heart disease risk. Using Python and popular data analysis libraries such as pandas, matplotlib, and seaborn, the project walks through all major steps of data science — from data ingestion and cleaning to visualization and statistical analysis.
The primary goal is to understand how patient characteristics like age, blood pressure, cholesterol, and heart rate relate to the presence of heart disease.
The inevitable dysfunctions of the human both fascinate, and scare me so personally I found working with this dataset intriguing. Questions were easily answered with the steps I describe below. Truth is I had no questions in specific those formulated along the way. Happens to be I also learned a few abbreviations for medical terms.


Data Cleaning
Key cleaning steps included:
Handling missing values:
Dropped the ca column (≈60% missing) and thal column (≈52% missing).
For columns with a small percentage of missing data (like oldpeak or slope), missing values were filled using the median or mean.
Ensured all numeric variables were properly formatted for analysis.
Duplicate check:
No duplicate patient IDs were found

Data Manipulation
Created age groups for easier trend visualization
Grouped data by disease status to compare averages across key metrics.
Filtered subsets to examine relationships between exercise, blood pressure, and cholesterol.

Data Visualization

Scatter plot — Age vs Cholesterol vs Max Heart Rate
Demonstrates the relationship between age, cholesterol, and max heart rate, with bubble color indicating heart disease.

Heatmap — Disease Rate by Age Group and Sex
Key insight: showing that males and older age groups have higher disease prevalence.

Bar chart - Chest Pain Type vs. Probability of Heart Disease
Simply visualizes what chest pains types had the highest and lowest probability of heart disease.

Descriptive Statistics

Using df.describe(), key insights were found:

Average age ≈ 54 years
Average resting blood pressure ≈ 132 mmHg
Average cholesterol ≈ 210 mg/dL

Average max heart rate ≈ 140 bpm

Other descriptive statistics included:
Comparing patients with vs without heart disease.

Top correlations with heart disease.








