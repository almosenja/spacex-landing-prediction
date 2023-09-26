# SpaceX Falcon 9 Landing Prediction
## Overview
![image](https://github.com/almosenja/spacex-landing-prediction/assets/94098493/c90745e2-c359-451c-ad24-7809c13e0f78)

This project aims to predict the landing success of SpaceX Falcon 9 first stage. Using a collection of launch data, we create a model to predict whether the Falcon 9 first stage will land successfully.

## Dataset
The dataset consists of information about SpaceX Falcon 9 launches, including date, payload, launch site, and landing outcome. The data is collected from publicly available source, SpaceX API.

## Usage
### Data Collection
`01_spacex_data_engineer.ipynb`
- Request data via SpaceX API
- Clean the requested data
- Data wrangling

### Exploratory Data Analysis (EDA)
`02_spacex_EDA.ipynb`
- Exploratory data analysis
- Preparing data feature engineering

### Data Visualization Map and Dashboard
`03_spacex_map.ipynb` and `03_spacex_dashboard.py`
- Map visualization with location mark
- Create an interactive dashboard

### Machine Learning Modeling
`04_spacex_machine_learning.ipynb`

- Standardize dataset
- Split into training and test data
- Machine Learning Modeling

## Models Used
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Results
The best model achieved an accuracy of 85% on the test dataset. 
