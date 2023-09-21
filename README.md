# Python-Data-Analyst-Statistical-Learning-Project
Insights and Predictive Modelling

Within the Jupyter file, my motivations for the project will be demonstrated and explained. 

The project can be split into 3 components

1) EDA
The objective of this project is to generate insight as to the London Bike Sharing patterns in London. Here are some queries or insights that we can look into before starting on the project: 

- Does the Weather affect the number of bikes being shared?

- How does the sharing of bikes vary from time of the day?

- Were there more bikes being shared as the months progressed?

- How does holidays affect the amount of bike shared

- In what season do most people ride bikes/share the bikes 

- How does wind speed affect riding behaviour (based on weather etc)

I added some plots to visualise and debunk the impact of these questions 

2) Tableau Project/Dashboard

I wanted to beautify the visualisations and allow for users to view concised data about the historic moving average, given the weather, humidity and temperature in London. My Tableau skills are still a work in progress, but I'm proud of this!


3) Stat Learning and Machine Learning Predicitve Model


**#Statistical Model for Prediction of Count** 

I have decided to do a Lasso and Best Reg Subset Selection for the prediction of count.  For these models, we will be trying to compare the MSE to ensure fair comparison of predictive power. The MSE can provide deeper insight into the bias-variance tradeoff. There will also be a exploratory section where I will utilise PCA+Lasso to predict count. The MSE for the PCA+Lasso is the worse out of all models. Our Best Reg Subset Selection model has the lowest MSE and hence best linear prediction model. Observations and Comments about each technique are added at the bottom of each kernal to document possible faults in model. 


# prediction of Weekend using SVM and Random Forest 
I have decided to predict if the 'weekend' variable has being predicted correctly as we would want our model to be able to predict riding behaviour on a weekend or weekday. I have decided to use a Random Forest, SVM and KNN model to predict if our test cases are on a weekend or not. We will be mainly using Classification reports and Confusion Matrixes as comparison. 

Our Random Forests model stood out as the best model. Observations and omments about each technique are added at the bottom of each kernal to document possible faults in model. 


   
