# Bike Sharing Demand prediction leveraging Linear Regression 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

I'm required to model the demand for shared bikes with the available independent variables as part of this assignment. In real scenario it can be used by the company to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Information/Background: This is an Upgrad assignment project related to Linear Regression modelling and prediction using a given dataset of a bike sharing company. The dataset contains the datapoints of year 2018 and 2019 of all the bike rentals and the various variables/features that were recorded and contributed to the bike rental demand. The bike rental demand is captured in a target variable named "cnt" which is the total number/count of bikes rented.
- Business Problem: The objective is to analyze the dataset and find significant variables/predictors for predicting bike sharing/rental demand going forward using Linear Regression Machine Learning modelling.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
**Model evaluation:**
- The train and test R2 scores are quite close which means there is no overfitting/underfitting in the model and it is quite stable
- The error terms were normally distributed so the p-values computed for the predictor variable coefficients are reliable.
- The model is not very complex and the final one contains 9 features shortlisted after Recursive Feature Elimination (RFE) automated process and manual feature selection from 28 features (post dummy variables and scaling)

**Significant Variables:**
 - **Spring Season:** This variable has a coefficient/weightage of -0.8188. The bike demand will significantly fall in spring and the company needs to invest in some marketing strategies to attract more people during spring
 - **Temperature:** This variable has a coefficient/weightage of 0.3510. In general as temperature gets warmer, demand rises This could be also observed as winter season or Light Snow (Weathersit) drives demands down
 - **Year:** This variable has a coefficient/weightage pf 0.9418. Year on year demand is increasing Covid-19 may have temporariliy stiffled demand but as the pandemic is gone now (or is less serious) the demand is expected to rise again. People are also becoming more climate conscious and prefer bikes for shorter transits and for jealth benefits
 - **Weather Conditions:** Weathersit variables like "Light Snow" or "Mist" drives demands down. Summer and Fall drives demands up

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Numpy
- library - Pandas
- library - Matplotlib
- library - Seaborn
- library sklearn model_selection, feature_selection/RFE, linear_model/LinearRegression, preprocessing/StandardScaler, metrics/r2_score etc.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on subjects/topics taught by Upgrad Instructors based on Course 2 -  Machine Learning, Module 1- Linear Regression
- This project is also inspired by examples given and techniques taught by Upgrad Instructors Shivam Garg, Shubham Gupta and IITB professors like Raghuram Bharadwaj
  
## Contact
Created by [@abym-droid] / abhim286@gmail.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
