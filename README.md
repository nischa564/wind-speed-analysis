# Wind Speed Analysis

Disclaimer: This repository is created for a user study.

## The Dataset

A company comes to you in order to improve their wind speed prediction. Currently they use a simple ARIMA model to do their wind speed predition and they reach a MAE of 3.0 knots on the given [dataset](./data/raw/wind_dataset.csv). Find out how you can improve the prediction of the company. 

### Context
High precision and reliable wind speed forecasting is a challenge for meteorologists. Severe wind due to convective storms, causes considerable damages (large scale forest damage, outage, buildings/houses damage, etc.). Convective events such as thunderstorms, tornadoes as well as large hail, strong winds, are natural hazards that have the potential to disrupt daily life, especially over complex terrain favoring the initiation of convection. Even ordinary convective events produce severe winds which causes fatal and costly damages. Therefore, wind speed prediction is an important task to get advanced severe weather warning. This dataset contains the responses of a weather sensor that collected different weather variables such as temperatures and precipitation.

### Attributes
- WIND: Average wind speed (knots)
- IND: First indicator
- RAIN: Precipitation amount (mm)
- IND.1 : Second indicator
- T.MAX: Max temperature (°C)
- IND.2: Third indicator
- T.MIN: Min temperature (°C)
- T.MIN.G: Min grass temperature (°C)

## Notebooks
Here are a template notebooks for the analysis. Modify the notebooks as you need!

| Notebook               | Colab Link    | 
| ---------------------- | -------------:|
| 1. Data Exploration    |  [Colab](https://colab.research.google.com/gist/nischa564/56a79b5402a5a2575b7142bf4f42ff7e/1-data_exploration.ipynb)    |
| 2. Data Preprocessing  |  [Colab](https://colab.research.google.com/gist/nischa564/05322a335f442cfbdd9e72539a769ad8/2-data_preprocessing.ipynb)  |
| 3. Data Transformation |  [Colab](https://colab.research.google.com/gist/nischa564/0fc4e882aeeb5e584498c680209d979b/3-data_transformation.ipynb) |
| 4. Data Analysis       |  [Colab](https://colab.research.google.com/gist/nischa564/f59d96f86ca1243c663eb6ae759d201a/4-data_analysis.ipynb)       |
