# DATA 201 Final Project  
## Predicting Traffic Accidents Using Machine Learning Models

### Author
Sudipto Bhadra

---

## Project Overview

This project analyzes the Montgomery County Traffic Violations dataset using machine learning techniques. The main goal of the project is to predict whether a traffic stop was associated with an accident using tree-based machine learning models.

The project includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Decision Tree modeling
- Random Forest modeling
- Gradient Boosting modeling
- Model evaluation and comparison
- Feature importance analysis

---

## Dataset

Dataset Name:
**Traffic Violations Dataset**

Source:
Montgomery County Open Data Portal

The dataset contains information related to:
- Traffic stops
- Vehicle details
- Driver demographics
- Accident records
- Traffic violations
- Geographic location data

After cleaning the dataset:
- Rows: 1,214
- Columns: 24

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models Used

### 1. Decision Tree
A Decision Tree model was used to understand how feature-based splits help predict accident outcomes.

### 2. Random Forest
Random Forest combined multiple decision trees and produced the best overall performance.

### 3. Gradient Boosting
Gradient Boosting also produced strong predictive results using ensemble learning techniques.

---

## Model Performance

| Model | Accuracy |
|---|---|
| Decision Tree | Evaluated |
| Random Forest | 98.35% |
| Gradient Boosting | 97.53% |

The Random Forest model achieved the highest overall performance.

---

## Important Features

The top features identified by the Random Forest model were:
1. Latitude
2. Year
3. Longitude

Feature importance indicates strong relationships with prediction outcomes but does not prove causation.

---

## Project Structure

- `Final_proj_SUDIPTO_BHADRA.ipynb` → Main Jupyter Notebook
- `renew.csv` → Cleaned dataset
- Visualization images
- Final report and presentation materials

---

## Key Learning Outcomes

Through this project, the following concepts were practiced:
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Classification models
- Ensemble learning
- Model evaluation
- Feature importance interpretation
- Machine learning workflow using real-world data

---

## Conclusion

This project demonstrated how machine learning models can identify important patterns in traffic violation and accident data. Among all the models tested, Random Forest provided the best balance between prediction accuracy and model stability.

The project also helped build a stronger understanding of how machine learning models make predictions using real-world datasets.
