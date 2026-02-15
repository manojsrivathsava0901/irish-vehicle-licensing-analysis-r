# irish-vehicle-licensing-analysis-r
# 📊 Vehicle Licensing Analysis in Ireland (R)

## Overview

This project analyzes vehicle licensing data in Ireland to understand
how vehicle registrations vary by fuel type, region, and time. Using
modern R data analysis techniques, the project demonstrates end-to-end
data processing, visualization, and custom function development.

The work focuses on producing clear, interpretable insights from
real-world administrative data.

------------------------------------------------------------------------

## Key Skills Demonstrated

-   R Programming
-   Data Wrangling with tidyverse
-   Data Cleaning with janitor
-   Exploratory Data Analysis (EDA)
-   Data Visualization with ggplot2
-   Functional Programming with purrr
-   Custom S3 Class Development
-   Statistical Summarization
-   Reproducible Analysis

------------------------------------------------------------------------

## Dataset

The dataset contains official Irish vehicle licensing records with:

-   3,240 observations
-   8 variables

Key features include: - Fuel Type - Licensing Authority - Vehicle Weight
Class - Year - Vehicle Count (VALUE)

The data was sourced from an official public authority, ensuring
reliability and reproducibility.

------------------------------------------------------------------------

## Data Preparation

Key preprocessing steps: - Converted categorical variables to factors -
Standardized column types - Removed missing values - Cleaned column
names using janitor

These steps ensured consistency and accuracy for downstream analysis.

------------------------------------------------------------------------

## Exploratory Data Analysis

### Regional Analysis

-   Bar charts comparing total vehicles by licensing authority
-   Identified higher registrations in major population centers

### Fuel Type Distribution

-   Boxplots showing variability across fuel types
-   Diesel vehicles dominate total registrations
-   Electric and hybrid vehicles show lower but growing presence

### Time-Series Trends

-   Line plots tracking diesel vehicle registrations over time
-   Revealed fluctuations influenced by policy and market changes

### Fuel Composition by Region

-   Stacked bar charts showing regional adoption patterns
-   Traditional fuels remain dominant in most regions

------------------------------------------------------------------------

## Functional Programming with purrr

The analysis uses purrr::map_dfr() to: - Split data by licensing
authority - Apply summary functions - Recombine results efficiently

This demonstrates scalable and reusable data workflows.

------------------------------------------------------------------------

## R Package Usage (janitor)

The project applies janitor functions to: - Clean column names -
Generate frequency tables - Format percentage summaries

This improves code readability and reporting quality.

------------------------------------------------------------------------

## Custom Analysis Framework (S3 Class)

A custom S3 class vehicle_analysis was developed, including:

-   vehicle_group_analysis() function
-   print() method
-   summary() method
-   plot() method

Features: - Input validation - Automated group-wise statistics -
Integrated visualization - Reusable analysis object

This demonstrates advanced R programming and object-oriented design.

------------------------------------------------------------------------

## Key Findings

-   Diesel vehicles account for the largest share of registrations
-   Urban regions show higher vehicle density
-   Alternative fuel adoption remains limited but present
-   Vehicle counts vary significantly across authorities

------------------------------------------------------------------------
