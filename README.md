# ** 🌞 Predictive Analytics for Heatstroke in Pune🌡️**

![Heatstroke](heatstroke_image.jpg)

## Introduction

Climate change is a global challenge impacting billions of lives. Pune has seen an increase in heatwave cases in recent years, impacting the health of citizens. As these heatwaves are increasing, the risk of heat-related illnesses and deaths is also rising. Understanding the heatwave impacts and developing mitigation strategies is crucial for protecting the lives of citizens. However, there is a gap in accurately predicting and reducing the impact of heatwaves on individuals. Current methods fail to do this adequately as the population increases and the risk of heatwaves also rises.

The main goal of this research paper is to create a predictive model for estimating the number of people affected by heatwaves in Pune. We aim to analyze past data on temperature, humidity, and wind speed to identify patterns and trends in heatwave impacts. Key features such as temperature, dew point, humidity, and wind speed were selected for predicting heatstroke cases in Pune. The historic daily weather data for five years (2016-2020) was obtained from the Global Historical Weather and Climate Data Website.

After conducting a literature survey, we identified random forest regressor, XGBoost, and CatBoost as suitable algorithms for our problem statement. These algorithms were implemented, and their accuracies were compared. The research goal was to develop a predictive model that can aid in making better decisions regarding heatwave mitigation strategies.

## Authors

- Aniket Patil (9518aniket@gmail.com)
- Viraj Patil (virajpatil818@gmail.com)
- Sangram Sankpal (sangramsankpal7812@gmail.com)

## Table of Contents

1. [Abstract](#abstract)
2. [Authors](#authors)
3. [Keywords](#keywords)
4. [Introduction](#introduction)
5. [Literature Survey](#literature-survey)
6. [Literature Summary](#literature-summary)
7. [Data Collection](#data-collection)
8. [Data Preprocessing](#data-preprocessing)
9. [Machine Learning Algorithms](#machine-learning-algorithms)
10. [Evaluation Metrics](#evaluation-metrics)
11. [Results and Discussion](#results-and-discussion)
12. [Conclusion](#conclusion)
13. [References](#references)


##Methodology: 

![methodology](https://github.com/Sangram0105/-Predictive-Analytics-for-Heatstroke-in-Pune/assets/115467468/a6eb73ff-0caa-4f6c-a438-44f61f1601a5) 
Fig 1 : Proposed Model Workflow and Architecture 
### Features:
- **Data Collection:** Utilizes historical weather data (2016-2020) and synthetic heatstroke cases.
- **Machine Learning Algorithms:** Implements Random Forest Regression, CatBoost Regressor, and XGBoost Algorithm for prediction.
- **Evaluation Metrics:** Evaluates model performance using RMSE, R-squared score, and accuracy.


## Data Collection

### Dataset Used

- **Period:** 2016-2020
- **Attributes:** Time, Temperature (°C), Dew Point (°C), Humidity (%), Wind Speed (kph), Pressure (hg), Precipitation (mm), Season


## Results and Discussion

![Results](https://github.com/Sangram0105/-Predictive-Analytics-for-Heatstroke-in-Pune/assets/115467468/ca446342-a2f2-4da0-a9b1-6b7f3bb96eb5)



| Algorithm              | RMSE   | R-squared (R^2) | Accuracy |
|------------------------|--------|------------------|----------|
| Random Forest Regression | 0.95 | 0.8259           | 82.60%   |
| CatBoost Regressor       | 0.91 | 0.8373           | 83.73%   |
| XGBoost Algorithm        | 0.99 | 0.8087           | 80.88%   |


### Let's Predict and Protect Against Heatwaves! 🔥👨‍⚕️🌊

