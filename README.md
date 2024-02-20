# My data analysis portfolio

I have recently completed a Level 4 Data Analyst Bootcamp with Cambridge Spark.
This is a portfolio of my projects showcasing skills I acquired on the bootcamp

### Table of Contents
- [Project 1 - Time Use Analysis](#project-1---time-use-analysis)
- [Overview](#overview)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Data Analysis](#data-analysis)
- [Data Filtering](#data-filtering)
- [Data aggregation & transformation](#data-aggregation--transformation)
- [Data Visualisation](#data-visualisation)

## Project 1 - Time Use Analysis

#### Overview

This data analysis project aims to provide insight into time use gender differences across the world, by analysing The OECD (Organisation for Economic Co-operation and Development) Time Use Database. 

#### Data Sources
- The OECD Time Use Database
  - consolidates datasets of large-scale time-use surveys conducted by national statistical agencies. Surveys classify day-to-day activities across the duration of 24 hours (1,440 minutes).  The dataset provides the average time use for OECD countries plus China, India, and South Africa.

- GDP per Capita
  - GDP (in USD) Per Capita Income by Country - uploaded April 2023 Available at Kaggle

#### Tools
- Pandas
  - data cleaning
  - data analysis
- Matplotlib and Seaborn
  - data visualisation

#### Data Cleaning/Preparation
- Initial EDA (exploratory data analysis)
  - data shape
  - data description
  - data types
  - unique values and counts in categorical variables

- Check for:
  - missing values
  - invalid data
- Removal of:
    - data not required
    - missing values
    - incorrect values
- Conversion of values to an appropriate data type
- Update incorrect values
- Rename column names

#### Data Analysis
- What is the mean time taken for activities?
- Which countries record highest and lowest times for activities?
- How does time use vary between men and women, by region and country's income level?
- How does time use vary between countries with low and high gender differences in
  - leisure time
  - over all activities
- What is the relationship between time for activities and GDP per Capita, for men and women?
  
#### Data Filtering
- Masks – row selection
- Defining function
        -Conditional expressions
        -Sorting 
        -indexing

#### Data aggregation & transformation 
- Data aggregation: combining data from several sources
- Joining datasets:  using .merge() method
- Data transformation:  using .groupby() and .pivot()
- Additional columns: for returned calculation results

#### Data Visualisation
  - violin plot
  - catplot 
    - multi rows
    - multi columns
  - correlation heatmap
  - jointplot 
  - scatterplot 
  - barplot
  - lmplot
    - multi columns
  - subplots
        

 
