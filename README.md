# Time-Series-Analysis-Forecasting-of-India-s-Quarterly-GDP-R
#OVERVIEW :

The project undertakes an end-to-end time series analysis and forecasting of the India Quarterly GDP (2011-2025) time series using the R programming language. The entire time series analysis pipeline is followed, from data preprocessing and decomposition to stationarity tests and eventually the SARIMA model and forecasting.

#OBJECTIVE :

1) Analyze the trend and seasonal patterns in India's quarterly GDP data
2) Detect significant events such as the effect of COVID-19 in 2020
3) Develop a reliable SARIMA model to forecast GDP for 2025-2027
4) Assess the accuracy of the model using appropriate metrics

#DATA SOURCE :

Ministry of Statistics and Programme Implementation (MOSPI), Government of India
Dataset: Quarterly Estimates of Gross Domestic Product at Constant Prices (Base Year 2011-12)
Period: Q1 2011 to Q2 2025
Frequency: Quarterly
Unit: Rupees Crores

#LIBRARY :

readxl
tidyverse
tseries
forecast
SARIMA 
ggplot2


#KEY FINDINGS :

1) India's quarterly GDP shows a consistent seasonal pattern — Q4 (January–March) always records the highest output due to fiscal year-end government spending
2) Q2 (July–September) consistently records the lowest output due to the monsoon season
3) A clear structural break occurred in 2020 Q1 due to COVID-19 lockdowns — visible as a large negative residual
4) The trend component shows steady long term growth with a slight slowdown during 2019–2020
5) The SARIMA model forecasts continued growth at approximately 1.47% per quarter through 2027
