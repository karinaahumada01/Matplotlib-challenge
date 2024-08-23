# Matplotlib-challenge

## Overview 
### This assignment's repository includes an analysis of a pharmaceutical company's study on a group of mice to test the treatment effectiveness of different drug regimens on reducing tumor size. The analysis uses Python and pandas, and contains data processing, statistical analysis, and data visuals.

## Files
### 1. Pymaceuticals_analysis.ipynb: Where the main analysis is done and includes different plot charts of results and draws conclusions from the data.
### 2. Mouse_metadata.csv: A CSV file with metadata on the studied and experimented on mice: Mouse ID, gender, age, and weight. This is joined with the study csv file for a complete analysis
### 3. Study_results.csv: A CSV file with the study's results, including information on the drug regimens given to the mice, the timepoints for tumor volume measurements, and the metastatic sites.

## Analysis Overview

### 1. Data Merging and Cleaning: The 'Mouse_metadata.csv' and 'study_results.csv' files are merge to make a single dataset, and any duplicates are dropped from the final dataset.

### 2. Statistical Summary: Descriptive statistics are calculated for the tumor volumes for all different drug regimens, including mean, median, variance, standard deviation, and standard error of the mean.

### 3. Data Visualization: bar charts, pie charts, box plots, scatter plots, and linear regression
###   -Bar charts: show the total number of observations for each drug treatment
###   -Pie charts: shows the male and female mice distribution in the study
###   - Box plots: compares the tumor volume distribution for each drug group
###   -Scatter plots and Linear regression: explores the correlation of mouse weight and the average tumor volume with a linear regression line plotted to model the relationship

### 4. Key Observations
### -The analysis reveals Capomulin and Ramicane as the two most effective drug treatments for decreasing tumor size
### - A significant positive relationship between mouse weight and tumor volume is found, with a correlation coefficient of 0.84
### -The gender distribution of the mice in the study is fairly equal


### How to Use...
#### Requirements: Updated Python, Jupyter Notebook, Python libraries--pandas, matplotlib, numpy, and scipy

### Run the Analysis:
#### - clone repo
#### - Open "Pymaceuticals_analysis.ipynb" in Jupyter Notebook
#### - Run each cell in order to generate analysis, dataframe tables, and data visuals


## References

### Ln 4 & 5 ".isin(duplicate_mice_ids)]" 
### GeeksforGeeks. (2023, November 29). Python: Pandas dataframe.isin(). https://www.geeksforgeeks.org/python-pandas-dataframe-isin/

### Ln 3 For correct duplicate value results
### Logan, F., (2024, Aug. 21). Tutoring Zoom Session

### Ln 7 Generating and formatting summary statistics table
### EdX. (2024). Xpert Learning Assistant (August 22 Version). www.bootcampspot.com. 
