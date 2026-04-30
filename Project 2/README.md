# DATA 201 — Project 2  
## Model Building, Evaluation, and Improvement (Regression)

### Overview  
This project focuses on building and improving a regression model to predict the number of persons injured in motor vehicle collisions. The analysis includes data exploration, model development, evaluation, and interpretation.

---

### Dataset  
- **Source:** NYC Open Data  
- **Dataset:** Motor Vehicle Collisions – Crashes  
- Each row represents a reported traffic collision in New York City  

---

### Objectives  
- Explore and understand the dataset  
- Build a baseline regression model  
- Improve the model using additional variables  
- Evaluate model performance using RMSE and R²  
- Interpret results in simple terms  

---

### Variables Used  

| Variable | Type | Description |
|------|------|------|
| LATITUDE | Quantitative | Crash location latitude |
| LONGITUDE | Quantitative | Crash location longitude |
| BOROUGH | Categorical | NYC borough where crash occurred |
| NUMBER OF PERSONS INJURED | Quantitative | Target variable |

---

### Data Cleaning  
- Removed rows with missing values  
- Selected relevant columns for analysis  
- Converted categorical variable (BOROUGH) into dummy variables  

---

### Exploratory Data Analysis  
- Histogram showed most crashes result in 0–1 injuries  
- Boxplot revealed presence of outliers (severe crashes)  
- Bar chart showed differences in crash frequency across boroughs  

---

### Modeling  

#### Baseline Model  
- Linear regression using latitude and longitude  
- Produced weak predictions with limited variation  

#### Improved Model  
- Added borough variable using dummy encoding  
- Slight improvement in model performance  

---

### Model Evaluation  

| Metric | Baseline | Improved |
|------|------|------|
| RMSE | 0.6681 | 0.6664 |
| R² | 0.00006 | 0.00519 |

- Improved model shows slightly better performance  
- Overall predictive power remains low  

---

### Key Findings  
- Location variables alone are weak predictors of injury counts  
- Adding borough improves the model slightly  
- Most crashes result in very few injuries  

---

### Limitations  
- Missing important variables such as speed, weather, and driver behavior  
- Low R² indicates limited explanatory power  

---

### Conclusion  
The regression model shows that geographic variables have limited ability to predict injury outcomes. Future improvements could include additional variables and alternative modeling approaches.

---

### Files Included  
- Jupyter Notebook (.ipynb)  
- Dataset (.csv)  
- Visualization images (.png)  
