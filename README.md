# energy_regression

## Overview
The aim of this project was to predict a developing nations energy consumption for the year based on other developing nations socio-econmic indicators. The goal
was to indentify which socio-econmic indicators were the strongest indicators of energy consumption. 

## Features
A total of 13 socio-economic indicators were chosen. The features used were: fertility_rate; foreign_direct_investment; gdp_per_capita; gdp_per_capita_growth; gni_per_capita; gross_capital_formation_p_of_gdp; inflation; life_expectancy_at_birth; population_density; population_growth; urban_population_growth; access_to_electricity_total; access_to_electricity_urban

## Algorithms
The algorithms used were random forrest regressor and a decision tree regressor for comparison

## Results
After hyper parameter fine tuning the random forest regressor far out performed the baseline random forest and decision tree. Hyper parameter fine tuning improved on the baseline tests performance by 86.32%. The mean absolute error of the tuned forest model was 295970.08 degrees. When considering the huge spread and size of the numbers we are dealing with when talking about a countries yearly energy consumption the MAE is a strong result (the max consumer is ~9,000,000 and the min is ~39,590).

### Feature Importance
In order of importance:
1. Population density
2. GDP per capita
3. Fertility rate
4. GNI per capita
5. Life expectancy at birth


## Usage
Packages Required:
python 3>
pandas
numpy
scipy
scikit-learn
seaborn
matplotlib

## Instructions
Simply download the Jupyter Notebook "footy_pred.ipynb" and the accompanying "E(n).csv"'s and run it in any IDE.

