# Boston House Prices Regression Task
Explore and predict housing prices using the Boston Housing dataset, comparing the performance of neural networks with traditional models like linear regression and random forests to understand the best predictors of housing values.

## Project Overview
This project focuses on the analysis and predictive modeling of the Boston Housing dataset, which contains data collected by the U.S. Census Service regarding housing in Boston, Massachusetts. The primary goal is to predict the median value of owner-occupied homes using various predictive modeling techniques. 
The project also aims to compare the predictive performance of traditional machine learning models and a neural network model, and to also identify and understand the best predictors of housing values.
The analysis will involve several key phases, including exploratory data analysis (EDA), data preprocessing, modeling, and evaluation. 

## Goals
1. **Exploratory Data Analysis (EDA)**: To perform a thorough analysis of the dataset to understand the distribution of data, identify patterns, and detect anomalies.
2. **Outlier Detection and Removal**: To improve model performance by identifying and removing outliers from the dataset, based on the Interquartile Range (IQR) method.
3. **Data Normalization/Scaling**: To transform the data so that it fits within a specific scale. This step is important because many machine learning algorithms, especially neural networks, perform better if the features are on the same scale. 
4. **Model Implementation and Comparison**: To establish baseline performance with the traditional regression model, implement and optimize more complex models like decision trees and random forests, and develop a Sequential neural network model, comparing their effectiveness using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
5. **Evaluation and Analysis**: To evaluate the models based on their predictive accuracy and computational efficiency and to analyze the models' performance to understand the advantages and limitations of each approach in the context of housing price prediction.

## Data Description

1. **CRIM**: Per capita crime rate by town. This represents the level of crime in each town, calculated on a per capita basis.
2. **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft. This feature represents the percentage of land in the town zoned for large residential properties.
3. **INDUS**: Proportion of non-retail business acres per town. It indicates the percentage of the town's land used for non-retail business purposes.
4. **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise). This is a binary variable indicating whether the tract is adjacent to the Charles River.
5. **NOX**: Nitric oxides concentration (parts per 10 million). This measures the level of nitric oxides in the air, which is a by-product of industrial processes and combustion vehicles.
6. **RM**: Average number of rooms per dwelling. This indicates the average number of rooms in residential buildings in the town.
7. **AGE**: Proportion of owner-occupied units built prior to 1940. It represents the percentage of units that are owner-occupied and were constructed before 1940.
8. **DIS**: Weighted distances to five Boston employment centres. This metric calculates the distance from residential areas to major employment centers in Boston, weighted by some undisclosed factors.
9. **RAD**: Index of accessibility to radial highways. This index measures the accessibility of radial highways from the town, which can influence commuting times and property values.
10. **TAX**: Full-value property-tax rate per $10,000. This is the rate of property tax applied to the full value of residential properties.
11. **PTRATIO**: Pupil-teacher ratio by town. This indicates the average number of pupils per teacher in schools in the town, reflecting on the educational resources available.
12. **B**: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents. This formula calculates a value based on the proportion of black residents in the town, where 0.63 is apparently an average or baseline proportion.
13. **LSTAT**: Percentage of lower status of the population. This represents the percentage of the lower socioeconomic status population in the town.
14. **MEDV**: Median value of owner-occupied homes in $1000s. This is the target variable and represents the median value of homes that are owner-occupied, expressed in thousands of dollars.

   
