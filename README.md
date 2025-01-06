# Road Traffic Crash Prediction for Akwa Ibom State

This project aims to predict total road crashes in Akwa Ibom State using historical data spanning from the last quarter of 2020 (Q4 2020) to the first quarter of 2024 (Q1 2024). The analysis identifies patterns in crash data and highlights contributing factors, providing insights to mitigate future accidents.

## Dataset

The <a href = "https://github.com/Etini2000/Akwa_Ibom_road_crashes_project/blob/main/Nigerian_Road_Traffic_Crashes_2020_2024.csv">Dataset</a> used in this project includes the following features:
1. Total_Crashes: Total road crashes recorded.
2. Num_Injured: Number of people injured.
3. Num_Killed: Number of fatalities.
4. Total_Vehicles_Involved: Number of vehicles involved in crashes.
5. SPV (Speed Violation): Incidents caused by speeding.
6. DAD (Drunk Driving): Crashes caused by drunk driving.
7. PWR (Weather Condition): Impact of weather conditions on crashes.
8. FTQ (Fatigue): Incidents caused by driver fatigue.
9. Other Factors: Other contributory factors.
10. Quarter: The quarter in which the crashes occurred(Q4 2020 to Q1 2024).

## Exploratory Data Analysis (EDA)

Three key visualizations were created during the EDA phase:

-Trend of Total Road Crashes (Q4 2020 - Q1 2024): A line chart showing the overall trend of total road crashes over the analyzed period.

-Trend of Total Crashes Based on Quarters: A bar chart comparing crash counts across different quarters.

-Contributing Factors to Total Crashes: A bar chart ranking factors (SPV, DAD, PWR, FTQ, etc.) by their contribution to crashes.

## Model Building
Algorithm: 
**Random Forest Regressor**

### Objective: 
Predict total crashes using the dataset features.

### Model Evaluation Metrics:
_**Mean Squared Error (MSE): 8.088**

_**R-squared Score: 0.817**

The model demonstrated strong performance, with an R-squared score of 0.817, indicating that it explained 81.7% of the variance in total crashes.
<a href = "https://github.com/Etini2000/Akwa_Ibom_road_crashes_project/blob/main/Aks_crashes_model.ipynb"></a>

## Deployment

The predictive model was deployed using <a href = "https://github.com/Etini2000/Akwa_Ibom_road_crashes_project/blob/main/Aks_crashes_ml_model.joblib">**FlaskAPI**</a>, making it accessible as a web service for querying crash predictions in realtime.
