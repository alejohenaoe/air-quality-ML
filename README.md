# Air Quality Prediction in Medellín Using Machine Learning

## Project Description
This project aims to analyze the relationship between PM2.5 concentrations and meteorological variables in Medellín. Using Machine Learning techniques, patterns and trends were identified to help predict air quality and formulate pollution mitigation strategies.

## Data Used
- **Air Quality**: Historical PM2.5 data obtained from monitoring stations in Medellín.
- **Meteorological Variables**: Temperature, humidity, wind speed, and atmospheric pressure.

The data was collected from the **Early Warning System of Medellín and the Aburrá Valley (SIATA)**.

## Methodology
1. **Data Collection**: Integration of pollution and meteorological data.
2. **Preprocessing**:
   - Data cleaning (handling missing values, format unification).
   - Exploratory analysis to identify distributions and outliers.
3. **Statistical Analysis**:
   - Correlation analysis between variables.
   - Identification of seasonal patterns in PM2.5 levels.
4. **Modeling**:
   - Regression models (Linear Regression, Random Forest, XGBoost) to predict PM2.5 concentrations.
   - Classification models to predict the Air Quality Index (AQI).

## Key Results
### 1. Correlations Between Variables
It was observed that:
- **Temperature** has a negative correlation with PM2.5 (higher temperature, lower pollution).
- **Humidity** shows a positive correlation with PM2.5.
- **Wind speed and pressure** have a lower impact on pollutant concentration.

![Correlation Heatmap](img/correlations.png)

### 2. Temporal Analysis
Pollution peaks were identified in the first 12 weeks of the year, suggesting the need for preventive measures during these periods.

![Temporal Analysis](img/weekly_analysis.png)

### 3. Air Quality Index Prediction
Classification models were tested, and the best result was obtained with **Decision Tree**, achieving an **F1-score of 0.89**.

![AQI Prediction](img/aqi_prediction.png)

## Conclusions
- The influence of meteorological variables on air quality was confirmed.
- AQI prediction allows early warnings and improved decision-making.
- These models can be applied in areas without monitoring stations, reducing implementation costs.

## Authors
- Alejandro Henao Echeverri
- Erika Dayana León Quiroga
- Jhonatan Latorre Sierra
- Juan Pablo Muñoz Carmona
- Yerson Alexis Madrid Villada

## References
- SIATA (https://siata.gov.co/)
- Machine Learning and air pollution: https://doi.org/10.1016/j.chemosphere.2022.136353
- XGBoost Documentation: https://xgboost.readthedocs.io/en/stable/


