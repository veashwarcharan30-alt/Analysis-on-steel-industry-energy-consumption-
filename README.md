# steel industry energy consumption prediction regression 

Project Overview – Predicting Energy Usage in the Steel Industry
Objective

To design a machine learning model for predicting energy consumption (Usage_kWh) in the steel industry, enabling eco-friendly and sustainable production methods.

Dataset

Records: 35,040

Features: 11 (4 categorical, 7 continuous)

Target: Usage_kWh (energy usage in kWh)

Key Features:

date (timestamp)

Day_of_week, WeekStatus, Load_Type (categorical → one-hot encoded)

Lagging_Current_Reactive.Power_kVarh, Leading_Current_Reactive_Power_kVarh

Lagging_Current_Power_Factor, Leading_Current_Power_Factor

CO2(tCO2) (carbon emissions)

NSM (time of day in seconds)

Methodology

Data Preprocessing – Categorical encoding (weekday/weekend, one-hot for day/load type), outlier removal using IQR, scaling.

EDA – Heatmaps, histograms, scatterplots, and time series analysis.

Usage strongly correlates with CO₂ and reactive power.

Demand spikes observed in time series.

Models Tested

Linear Regression, KNN, SVR, Decision Tree, Random Forest, Bagging, AdaBoost, Gradient Boost, XGBoost, ANN.

Evaluation – Train-test splits (60-40, 70-30, 75-25, 80-20) with metrics like R², MAE, MAPE.

Results

Best Model: XGBoost (80:20 split) → R² = 0.9911

Other strong models: Gradient Boost, Random Forest, ANN.

Simpler models (e.g., Linear Regression, SVR) performed poorly compared to ensemble/deep models.

Conclusion

Advanced ML models (especially XGBoost) capture complex, non-linear energy consumption patterns better than traditional regression.

ML can provide accurate insights for sustainable energy management in steel manufacturing.

Future Scope

Incorporating external factors (weather, market demand, energy prices).

Deploying models in real-time monitoring systems.

Exploring deep learning architectures for further improvement.
