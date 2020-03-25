# Air quality index prediction

Data science project to predict air quality index parameter from data of previous years.
This project is bascically build in four phases.
1) Data Gathering
2) Feature Engineering
3) Model Building
4) Model Evaluation

## 1) Data Gathering:

  1) Data is gathering using the techniques of web scraping using Beautifulsoup4. Data is collected from en.tutiempo.net.
  2) Real life PM 2.5 index is collected using a third party API that is paid. So, direct csv files are attached along with this repo.
  
## 2) Feature Engineering:

    Feature engineering techniques are used to get the most significant feature out of all available and use it for futher model building.
    
## 3) Model Bulding:

    Following ML algorithms are used to predict PM 2.5 value.
        -Linear Regression
        -Lasso Regression
        -Decision Tree Regressor
        -KNN Regressor
        -RandomForest Regressor
        -XgBoost Regressor
        -Huperparameter Tuning
        -Artificial neural network
        
## 4) Model Evaluation:

    Model evaluation was done on the basis of Regression Evaluation Metrics
    Here are three common evaluation metrics for regression problems:
    
Here are three common evaluation metrics for regression problems:

**Mean Absolute Error** (MAE) is the mean of the absolute value of the errors:

$$\frac 1n\sum_{i=1}^n|y_i-\hat{y}_i|$$

**Mean Squared Error** (MSE) is the mean of the squared errors:

$$\frac 1n\sum_{i=1}^n(y_i-\hat{y}_i)^2$$

**Root Mean Squared Error** (RMSE) is the square root of the mean of the squared errors:

$$\sqrt{\frac 1n\sum_{i=1}^n(y_i-\hat{y}_i)^2}$$

Comparing these metrics:

- **MAE** is the easiest to understand, because it's the average error.
- **MSE** is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world.
- **RMSE** is even more popular than MSE, because RMSE is interpretable in the "y" units.

All of these are **loss functions**, because we want to minimize them.

## Thanks: KrishNaik for such a wonder tutorial.
