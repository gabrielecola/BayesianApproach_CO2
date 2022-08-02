## Bayesian Approach to contrast C02 Emission

## Table of Contents

 - [C02 Emission count prediction using Bayesian Model](#co2-emission-count-prediction-using-bayesian-model)
- [1. Problem Statement](#1-problem-statement)
- [2. Data Description](#2-data-description)
  * [Attribute Information](#attribute-information)
    + [Inputs](#inputs)
    + [Output](#output)
- [3. EDA](#3-eda)
- [4. Modelling Evaluation](#4-modelling-evaluation)
- [5. Results](#5-results)


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
    
    ### 3. EDA

  <img src="https://user-images.githubusercontent.com/103529789/182400978-e70be261-d913-4856-8122-e87aa55efc17.png" width="350"/>
  <img src="https://user-images.githubusercontent.com/103529789/182402913-ff512d3c-f1b0-4f1d-982b-ae00efab2a1d.png" width="350"/> 
  <img src="https://user-images.githubusercontent.com/103529789/182401373-a11aec8c-ade4-4cd5-9bdd-aa580a4b9da1.png" width="350"/>
  <img src="https://user-images.githubusercontent.com/103529789/182402420-ec9ac32a-67f3-4d34-a605-38c9e4af3110.png" width="350"/> 


    ### 4. Modelling Evaluation
    
    - Algorithms used
        - Bayesian Linear Regression (1 Approach)
        - Bayesian Linear Regression (2 Approach
        - Bayesian Poisson Regression
        - Bayesian Poisson Overdispersion Regression
        - Bayesian Hierarchical Poisson model
    - Metrics:  RMSE (Root Mean Squared Error)

    ### 5. Results
    
  <img src="https://user-images.githubusercontent.com/103529789/179559461-ad7fa0e7-6f73-485d-b5b7-d58df658d66d.png" width="650"/>
    
