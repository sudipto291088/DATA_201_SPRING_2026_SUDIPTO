# DATA 201 – Project 1 (Week 8)

**Author:** Sudipto Bhadra  
**Course:** DATA 201 – Statistical Methods in Data Science  
**Instructor:** Dr. Rebin Muhammad  

---

## Project Overview

This project explores a large dataset of reported crime incidents obtained from **Data.gov**. The goal of the project is to practice data wrangling, exploratory data analysis, and basic statistical inference using Python tools such as **Pandas, NumPy, and visualization libraries**.

The dataset contains more than 150,000 records, where each row represents a single reported crime incident. Variables include information about the type of crime, police district, time of occurrence, and geographic location.

---

## Project Objectives

The project focuses on:

- Understanding the structure of a real-world dataset
- Performing descriptive analysis of quantitative and categorical variables
- Exploring relationships between variables
- Conducting nonparametric statistical inference using sampling
- Interpreting results in context

---

## Analyses Performed

### 1. Quantitative Analysis
The variable **hour** was analyzed to understand how crime incidents are distributed across hours of the day. Summary statistics and a histogram were used to examine measures of center, spread, and the shape of the distribution.

### 2. Categorical Analysis
The variable **text_general_code** was analyzed to determine which crime categories appear most frequently in the dataset. Frequency tables and bar charts were used to summarize the distribution of crime types.

### 3. Exploratory Relationship Analysis
The relationship between **crime type** and **police district** was explored to determine whether certain types of crimes occur more often in particular districts.

### 4. Nonparametric Inference
A random sample of approximately **10% of the dataset** was used to estimate the **median hour of incidents** using a bootstrap simulation approach.

---

## Key Findings

The analyses showed patterns in the timing and types of reported crimes. Certain hours of the day contain higher concentrations of incidents, and some crime categories appear more frequently than others. Exploratory analysis also suggests that crime types may vary across police districts.

---

## Future Work

Further analysis could investigate additional variables such as geographic location patterns or trends over time. More advanced modeling techniques or spatial analysis could help identify deeper patterns and factors associated with crime incidents.

---

## Dataset Source

Data.gov. Crime Incidents Dataset.  
Available at: https://catalog.data.gov/
