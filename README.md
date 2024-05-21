# Car-Sales-Analysis

## Project Overview

This data analysis project aims to provide insights into the sales perfomance of a car dealership company over the years 2018, 2019 and 2020. By analyzing various aspects of sales data, we seek to identify sales trends, make data-driven recommendations and gain deeper understanding of the dealer's perfomance.

### Data Sources

**Auto Sales Data**: The primary dataset used for this analysis is the Auto Sales Data.csv file, containing information about each sale made by the dealer. 

**DISCLAIMER**: This dataset was downloaded from kaggle and it does not represent any company or known dealer. It is solely aimed at showcasing data analysis skills.

### Tools and Packages

All data preprocessing and analysis were done using R-markdown format in R-studio. Packages utilised include:

- readr - For reading data into the R-studio environment
- dplyr - For data manipulation
- lubridate - For date manipulating date
- ggplot2 - For visualizations
- summaryTools - For summarizing numerical variables
- Rmarkdown - For formating the code and creating R report

### Data Cleaning / Preparation

In the initial data preparation phase, we perfomed the following tasks:

- Checked for missing values
- Changed the date column from character type to date type
- The dealsize, productline and the status variables were also changed to factor variables
-  Created the year, month, day of the month and weekdays variables

### Exploratory Data Analysis

Exploratory data analysis involved exploring the sales data to answer questions such as;

- What are the min, max and average sales values?
- What are the peak sales periods?
- Which categories of dealsize, status, productline have peaking sales?
- In which year, month, weekday and day of the month are of low and heaping sales?

### Results/Findings

- Maximum sales are at 14 082.800 , minimum at 482.130 and average at 3 553.048 million.
- Country USA, Medium deals, Classic cars and the shipped cars has heping sales values.
- Thursdays has lowest values of sales in a week while Sunday, Tuesday, Wednesday and Friday have highest sales.
- Sales perfomance values seem constant throughout all the months of a year, however we see slightly low values in September and April.
- We also see a flactuating but slightly increasing value of sales from the first to the last day of the month. However, sales show a sharp decrease during the 21st day. Sales are the highest during the 28th day of the month.
-The dealer yielded highest sales from the Sharp Gifts Warehouse from San Jose, USA.

### **Recommendations**

Based on the analysis, we recomend the following actions;
- Focus on expanding and promoting cars large deals and the sales of trains.
- Implement effective advertising strategies to improve sales on low sales countries such as the Ireland.


see report (https://github.com/Celumusa91/Car-Sales-Analysis/blob/main/Sales%20Data%20Analysis.Rmd)
