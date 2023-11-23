# EDA with R - Cumulative Lab
## Introduction
In this section, you've learned a lot about importing, cleaning up, analyzing (using descriptive statistics) and visualizing data. In this cumulative lab, you'll get a chance to practice all of these skills with the Ames Housing dataset, which contains information about home sales in Ames, Iowa between 2006 and 2010.

## Objectives
You will be able to:

Practice loading data with pandas
Practice calculating measures of centrality and dispersion with pandas
Practice creating subsets of data with pandas
Practice using data visualizations to explore data, and interpreting those visualizations
Perform a full exploratory data analysis process to gain insight about a dataset
Your Task: Explore the Ames Housing Dataset with R
aerial photo of a neighborhood


## Data Understanding
Each record (row) in this dataset represents a home that was sold in Ames, IA.

Each feature (column) in this dataset is some attribute of that home sale. You can view the file data/data_description.txt in this repository for a full explanation of all variables in this dataset — 80 columns in total.

We are going to focus on the following features:

SalePrice: Sale price of the house in dollars

TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)

OverallCond: Rates the overall condition of the house

       10	Very Excellent
       9	 Excellent
       8	 Very Good
       7	 Good
       6	 Above Average	
       5	 Average
       4	 Below Average	
       3	 Fair
       2	 Poor
       1	 Very Poor
YrSold: Year Sold (YYYY)

YearBuilt: Original construction date

LandSlope: Slope of property

       Gtl	Gentle slope
       Mod	Moderate Slope	
       Sev	Severe Slope
## Requirements
In this lab you will use your data munging and visualization skills to conduct an exploratory analysis of the dataset.

1. Load the Dataset with R
Load the data into a dataframe with the standard name df.

2. Explore Data Distributions
Produce summary statistics, visualizations, and interpretive text describing the distributions of SalePrice, TotRmsAbvGrd, and OverallCond.

3. Explore Differences between Subsets
Separate the data into subsets based on OverallCond, then demonstrate how this split impacts the distribution of SalePrice.

4. Explore Correlations
Find the features that have the strongest positive and negative correlations with SalePrice, and produce plots representing these relationships.

5. Engineer and Explore a New Feature
Create a new feature Age, which represents the difference between the year sold and the year built, and plot the relationship between the age and sale price.
