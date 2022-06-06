# Stock-Price-Prediction
## Project Overview : 
A stock market is a public market where you can buy and sell shares in publicly traded companies. The stocks, also known as equities, represent the ownership of the company. The stock exchange acts as a go-between for stock buyers and sellers. The stock market's significance stems from the fact that it helps businesses raise capital and aids in the creation of personal wealth. It is also a popular way for people to invest in businesses with high growth potential, so it can be used to assess the state of the economy.  
Is it possible to use machine learning to forecast future stock market prices?  
Investors make educated guesses based on data analysis. They will research the company's history, industry trends, and other data points before making a prediction. According to popular belief, stock prices are completely random and unpredictable, which begs the question of why top firms hire quantitative analysts to develop predictive models. We imagine the trading floor to be filled with adrenaline-fueled men in loose ties running around yelling something into a phone. However, we are more likely to see rows of machine learning experts sitting quietly in front of computer screens these days. Software now places roughly 70% of all orders on Wall Street.  
In this notebook, I attempted to analyze Tesla stock market data using EDA techniques such as data cleaning, organization, and visualization to better understand the problem at hand, as well as adding extra features to the data to aid in the training process.  
Following that, a variety of Machine Learning models were fitted to data that was split into training and test sets in their baseline configuration and evaluated using the R2 (coefficient of determination) metric. Other steps included hyperparameter tuning, evaluation using six different metrics, and feature importance visualizations for the top two models. 
## Problem Highlights :
The goal of this project is to accurately predict the future closing value of a given stock over a specified time period in the future. For this project, I used a variety of ML models to determine which one learned the most from the data.  
***Achievements:*** 
* Built several models and properly trained them on well-prepared data.
* Achieved a coefficient of determination (R^2 score) of 0.96459 and an MSLE of 0.00014 for the best model which was in our case the RandomForestRegressor.  
  
***Things I have learnt by completing this project:***
* How to apply different Machine learning techniques by training and test them on the data.
* How to collect and preprocess given data and visualize its contents on several types of plots.
* How to analyze model's performance using several evaluation metrics. 
## Software and Libraries:
* Python 3.8
* NumPy
* pandas
* Keras
* Scikit-learn
* Jupyter Notebook
## Models used:
* RandomForest
* KNN 
* LinearRegression
* SVMRegressor
* ADABOOST
* XGBoost
* CatBoost
* BayesianRidge
## Results:
![alt text](https://github.com/Sanazorgui/Stock-Price-Prediction/blob/main/Models%20comparaison.png?raw=true)

|  | CatBoost | RandomForestRegressor |
|:--------------:|:-------------:|:--------------:|
| ***MAE*** | 4.601509929442768 | 2.9516314094190514 |
| ***RMSLE*** | 0.018382158220525576 | 0.012031133547167132 |
| ***MSE*** | 30.985590635305122 | 13.700921152699925 |
| ***R^2*** | 0.9199182124313414 | 0.9645901777326359 |
| ***RMSE*** | 5.566470213277452 | 3.701475537228353 |
| ***MSLE*** | 0.00033790374084443606 | 0.00014474817442977037 |



