# BestCropOfDistrictToCultivate
This project applies Machine Learning and Data Science techniques to predict crop yields and recommend the best-performing crops per state and category (Cereals, Pulses, Oilseeds, etc.) using historical agricultural data. The goal is to assist farmers, policymakers, and researchers in making data-driven agricultural decisions.

## Features

📊 Exploratory Data Analysis (EDA):
- Yield distribution across years, seasons, states, and crop categories
- Correlation analysis of rainfall, fertilizer, pesticide usage with yield

🤖 Machine Learning Models:
- Decision Tree Regressor
- Random Forest Regressor (with GridSearchCV and Optuna hyperparameter tuning)
- Support Vector Regressor (SVR)

🧪 Evaluation Metrics:
- Mean Squared Error (MSE)
- R² Score (model accuracy)
- Cross-validation with TimeSeriesSplit

🌍 Crop Recommendation System:
- Predicts best crop per state within each category (Cereals, Pulses, Oilseeds, etc.)
- Compares predicted vs. actual best crop for validation years

📈 Visualizations:
- Heatmaps of crop distribution per state (by category)
- Feature importance plots (to interpret ML models)


## Dataset
The dataset contains agricultural data such as:
- Crop Name, Crop Category, Season, State
- Crop Year, Area, Production, Yield
- Annual Rainfall, Fertilizer Use, Pesticide Use

The dataset is from Mendeley Dataset website >> [Link](https://data.mendeley.com/datasets/ncw2vbcgnk/2) 

