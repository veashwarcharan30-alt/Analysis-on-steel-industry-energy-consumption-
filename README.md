# Analysis-on-steel-industry-energy-consumption-prediction 

Regression Project

Overview: This project focuses on predicting energy usage (kWh) in the steel industry using regression techniques. The dataset includes operational and environmental factors that influence power consumption.

Objective:

To analyze the factors affecting energy consumption.
To build a predictive model for Usage_kWh (Target Variable).
Data: Total records - 35040, variables - 11 Attributes(Features)

Attribute	Description
date	Timestamp of the record
Day_of_week	Day of the week (categorical, later one-hot encoded)
WeekStatus	Whether the day is a weekday (1) or weekend (0)
Load_Type	Type of load (categorical, later encoded into dummy variables)
Usage_kWh	 Target Variable – Power usage in kilowatt-hours
Lagging_Current_Reactive.Power_kVarh	Lagging current reactive power consumption (kVarh)
Leading_Current_Reactive_Power_kVarh	Leading current reactive power consumption (kVarh)
Lagging_Current_Power_Factor	Lagging power factor
Leading_Current_Power_Factor	Leading power factor
CO2(tCO2)	Carbon dioxide emissions in tonnes of CO2
NSM	Number of seconds from midnight (time indicator)
