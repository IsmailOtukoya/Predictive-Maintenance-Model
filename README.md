# Predictive-Maintenance-Model


# Predictive Maintenance


### Introduction:


The project objective is to enhance the maintenance operations and planning of time-based preventive maintenance by making use of  data science techniques and machine learning algorithms for predicting more accurate maintenance requirements.

### Problem:

Failure prediction is a major topic in predictive maintenance in many industries. Airlines are particularly interested in predicting equipment failures in advance so that they can enhance operations and reduce flight delays. 

Observing engine's health and condition through sensors and telemetry data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF) or Remaining Useful Life (RUL) of in-service equipment. Using aircraft engine's sensors measurements, The project attempt to provide the following predictions:  
-  engine's TTF
-  which engines will fail in the current period or cycle window
-  maintenance plan based on prediction of engines failure per period



### Data:

Text files contain simulated aircraft engine run-to-failure events, operational settings, and 21 sensors measurements are provided by Microsoft. It is assumed that the engine progressing degradation pattern is reflected in its sensor measurements. 




### Approach:

By exploring the aircraft engine’s sensor values over time, the machine learning algorithm can learn the relationship between the sensor values and changes in sensor values to the historical failures in order to predict failures in the future.  

- __Regression Modeling__ algorithms were used to predict the number remaining cycles before engine failure.
- __Binary Classification__ algorithms were used to predict if the engine will fail within specific cycles window or not 
- __Multiclass classification__ algorithms were used predict in which cycles window or period will an engine will fail.


### Project Files:

- #### README

- #### Data Wrangling

- #### Exploratory Data Analysis

- #### Regression Modeling

- #### Binary Classification

- #### Multiclass Classification



