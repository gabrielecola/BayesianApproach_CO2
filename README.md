## Bayesian Approach to contrast C02 Emission

## Table of Contents

 - [C02 Emission count prediction using Bayesian Model](#co2-emission-count-prediction-using-bayesian-model)
- [1. Problem Statement](#1-problem-statement)
- [2. Data Description](#2-data-description)
  * [Attribute Information](#attribute-information)
    + [Inputs](#inputs)
    + [Output](#output)
- [3. Modelling Evaluation](#3-modelling-evaluation)
- [4. Results](#4-results)


### C02 Emission count prediction using Bayesian Model
This dataset captures the details of how CO2 emissions by a vehicle can vary with the different features. The dataset has been taken from Canada Government official open data website.This contains data over a period of 7 years. 
Thus, using Bayesian model to predict the count of C02 emission could be useful in solve this dangerous problem

### 1. Problem Statement
Predicting the count of C02 emission given some qualitative and quantitative attribute.

### 2. Data Description
Data is obtained from Kaggle.
https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles

- Number of instances - 7385
- Number of attributes - 12

    #### Attribute Information
    ##### Inputs
    - make 
    - model
    - vehicle_class
    - engine_size_l
    - cylinders 
    - transmission 
    - fuel_type  
    - fuel_consumption_city_l_100_km
    - fuel_consumption_hwy_l_100_km
    - fuel_consumption_comb_l_100_km
    - fuel_consumption_comb_mpg  
    - co2_emissions_g_km 
    
    ##### Output
    - co2_emissions_g_km 

    ### 3. Modelling Evaluation
    
    - Algorithms used
        - Bayesian Linear Regression
        - Bayesian Poisson Regression
        - Bayesian Poisson Hierarchical model
    - Metrics:  RMSE (Root Mean Squared Error)

    ### 4. Results
    
    <p float="left">
  <img src="https://user-images.githubusercontent.com/103529789/177041218-70db5e89-d15e-46be-861d-0565fc51c03a.png" width="350"/>
  <img src="https://user-images.githubusercontent.com/103529789/177041253-e2a02a1b-c0d5-414a-bc99-f3e03c75a1b3.png" width="350" /> 
  <img src="https://user-images.githubusercontent.com/103529789/177041256-74d2ad9c-5a9e-4037-8ad0-751a58dc9c91.png" width="350"/>
  <img src="https://user-images.githubusercontent.com/103529789/177041257-4d39716f-1a4e-4d05-a093-e55d386d776f.png" width="350" /> 
</p>
    
