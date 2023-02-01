# Portfolio

Data Science

## Featured Projects

### Ice Retail

[Ice Retail EDA](https://github.com/jodiambra/ICE-Retail/blob/main/ICE%20Retail%20EDA.ipynb)
<img src="ice2.jpeg?raw=true"/>
<img src="ice4.jpeg?raw=true"/>
<img src="ice8.jpeg?raw=true"/>
<img src="ice9.jpeg?raw=true"/>

#### Skills Demonstrated 
    Pandas
    Scipy
    Plotly Express
    Matplotlib
    Plotly
    Cleaninig Data
    EDA
    Filtering
    Misisng Values
    Feature Engineering
    Pivot Tables
    Hypothesis Testing
    T-Test

#### Purpose
We are looking at data from Ice, an online retail store for video games. The data set includes categories based on genre, platform, rating, sales, release year, critic, and user scores.  

The purpose of this project is to collect historical data, and apply insights to determine whether a game will succeed or not in the future. These insights will be used to optimize capital allocation in regards to advertising potentially big winners. We will be determining total sales,  and the distribution  of sales across the different platforms. We will illustrate which platforms lead, and lag in sales. Data analysis will determine the most popular platforms and genres. Investigations will determine if the average user ratings of certain platforms are the same, or if the average ratings of certain genres are the same. 

#### Conclusions
Overall, we can look at our data to make predictions for 2017. First, inferences would need to be made as to the region we are most interested in marketing to. Since the North American region generally leads in sales, and since the European region follows a similar trend, we can maximize our results by focusing on North America. Since the most popular platform is the PS4, we will be looking for a game on that platform. Since the most popular genre in North America is action, we will be looking for the next big action game. Furthermore, we would want a game that could be played on XONE or PC as well, to maximize sales. Since ratings and user scores do not influence sales, we will not care too much about those factors. Yet, a game in the action genre will likely be M for mature. It is highly likely that the next iteration of Call of Duty or GTA will be widely successful. Alternatively, if we want to market to the Japanese region, we will look for a role playing game on the 3DS. However, profits are likely to be higher working with the previous strategy.

#
Run notebook to see interactive visualizations.
#
Open figures to see static visualizations. 

---
### Sure Tomorrow Insurance

[Sure Tomorrow Insurance](https://github.com/jodiambra/Sure-Tomorrow-Insurance/blob/main/Sure%20Tomorrow%20Insurance.ipynb)
<img src="sure1.jpeg?raw=true"/>
<img src="sure2.jpeg?raw=true"/>
<img src="sure3.jpeg?raw=true"/>

#### Skills Demonstrated
    Pandas
    EDA
    Matrices
    Sklearn
    Binarizer
    Data Obfuscation
    F1 score, Accuracy score, AUC-ROC, R2, MSE
    KNeighbors Classifier
    Decision Tree Classifier
    Random Forest Classifier
    Cross Validation
    Plotly Express


#### Purpose
The Sure Tomorrow insurance company wants to solve several tasks with the help of Machine Learning and we are asked to evaluate that possibility.

- Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
- Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a prediction model do better than a dummy model?
- Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without breaking the model from the previous task. It's necessary to develop a data transformation algorithm that would make it hard to recover personal information if the data fell into the wrong hands. This is called data masking, or data obfuscation. But the data should be protected in such a way that the quality of machine learning models doesn't suffer. You don't need to pick the best model, just prove that the algorithm works correctly.

#### Conclusions
We trained a model that would return similar customers for a given one. This model was calculated while scaled and unscaled, using euclidean and manhattan distances. Then, we created a dummy model to test the f1 scores of different probability values. We found the dummy model to be less accurate than the classification model we built, using both original and scaled data. After, a linear regression model was built with matrix operations. The evaluation metrics of RMSE and R2 score were measured, and then compared to a linear regression model on the obfuscated data. We concluded that obfuscation did not alter the accuracy of the model, as the RMSE and R2 metrics were the same before and after obfuscation. Overall, we have provided results that suggest a very accurate prediction as to whether a customer will, or will not receive insurance benefits. This is more accurate than trying to predict the actual number of insurance benefits a customer will receive. Consequently, we suggest Sure Tomorrow use the more accurate classification model over the regression model.  

---
### Sweet Lift Taxi Time Series Forcast
[Sweet Lift Taxi Time Series Forcast](https://github.com/jodiambra/Sweet-Lift-Taxi-Time-Series-Predictions/blob/main/Sweet%20Lift%20Time%20Series%20Predictions.ipynb)
<img src="sweet1.jpeg?raw=true"/>
<img src="sweet2.jpeg?raw=true"/>
<img src="sweet3.jpeg?raw=true"/>

#### Skills Demonstrated
    Pandas
    Visualizations
    Time Series Data
    Seasonal Decompose
    Regression Models
    XGBoost
    CatBoost
    Light GBM

#### Purpose
Sweet Lift Taxi company has collected data on taxi orders at airports. Their aim is to predict the amount of taxi orders for the next hour, in order to allocate more drivers for peak hours. We will build a model with an RMSE lower than 48. 

#### Conclusions
Overall, we succeeded in providing a model for Sweet Lift Taxi to predict the number of orders of the next hour. The target metric for our model was an RMSE score under 48. Our final model was a voting regressor, with a final RMSE of 46.47 with the test data set. Therefore, Sweet Lift can accommodate drivers with a model that accurately predicts future number of orders. 

---

## Other Projects

Beta Bank Churn
[Beta Bank Churn](https://github.com/jodiambra/Beta-Bank-Churn-Predictions/blob/main/Beta%20Bank%20Churn.ipynb)
- Purpose
The purpose of this project is to investigate the churn of Beta Bank customers. The bank has noticed customers are slowly leaving, month over month. The most cost effective solution is to retain existing customers, rather than recruit new customers. The bank needs a model that will predict whether a customer will leave the bank soon. The model will be trained on data from clients' past behavior and termination of contracts with the bank. The goal of the project is to build a model with an F1 score of at least 0.59.
This is a binary classification problem, therefore, we will be focussing on that class of modeling. This is the case because the target is categorical: churn or not. The F1 score is an appropriate indicator of our model, because we care about both precision and recall. We care about precision because we want to capture as many true positive occurrences of churning. Recall is also crucial, as we want to capture as many occurrences of churning as possible.

Rusty Bargain Car Value Predictions
[Rusty Bargain](https://github.com/jodiambra/Rusty-Bargain-Car-Market-Value/blob/main/Rusty%20Bargain.ipynb)
- Purpose
Rusty Bargain is developing an app to attract new customers, and they need to be able to quickly find out the market value of a car. We are given access to historical data: technical specifications, trim, and prices. Rusty Bargain wants a model that will predict the value of the car, while also considering the quality and speed of the prediction, and also the time required for training.
Yandex-Music
First data science project, EDA
[Yandex Music](https://github.com/jodiambra/Yandex-Music/blob/main/Yandex%20Music%20Final.ipynb)

-  Purpose
The purpose of this project is to compare the music preferences in the cities of Springfield and Shelbyville. We will use data provided by Yandex.music to test hypotheses on user behavior.

Instacart-EDA
Instacart Exploratory Data Analysis
[Instacart EDA](https://github.com/jodiambra/Instacart-EDA/blob/main/Instacart%20EDA.ipynb)

-  Purpose
This project analyzes data collected by Instacart, the grocery delivery platform. The purpose of this project is to clean up the data, and use the cleaned data to report insights on shopping habits of Instacart customers. The data  was cleaned by removing duplicate vales, and filling in missing values, all while maintaining the integrity of the dataset. Analyses indicated the number of orders placed, dependent on variables such as time of the day, day of the week, and time since the customer last placed an order. The results demonstrate the distribution of the number of orders customers place, the top 20 products, and the top 20 reordered products. 


Megaline-Plus
[Megaline Plus Revenue](https://github.com/jodiambra/Megaline-Plus/blob/main/Megaline%20EDA.ipynb)

-  Purpose 
The purpose of this project remains to analyze the data provided by the telecom operator Megaline. With an offering of two plans, Surf and Ultimate, the goal of this project is to determine optimal capital allocation. We will determine which plan brings in more revenue. This will result in an adjustment of the advertising budget, as a means to further increase revenue. The dataset provided is a sample of the population of Megaline customers, across different cities in 2018. We will conduct further analysis on the client behavior, as well as look at other important insights found in the data. 

Megaline Plus Recommendations
[Megaline](https://github.com/jodiambra/Megaline-Plan-Recommendations/blob/main/Megaline%20Plan%20Recommendations.ipynb)
- Purpose
The purpose of this project is to aid Megaline, a mobile carrier, in developing a model that will analyze subscribers' behavior. Once the behavior is analyzed, subscribers on a legacy plan can be recommended one of Megaline's newer plans: Smart or Ultra. We are provided with behavior data from subscribers who have already switched to the new plans. A successful model will classify a correct new plan to a legacy plan customer. We will be working with data that we've used previously, so the data will be clean.

Zuber Web Scrapping
[Zuber Web Scrapping](https://github.com/jodiambra/Zuber-Web-Scrapping/blob/main/Zuber%20Ride%20Share.ipynb)
- Purpose
Zuber is a new ride-sharing company that is launching in Chicago. We are tasked to find patterns in the available information. The goal of the project is to understand passenger passenger preferences and the impact of external factors on rides. Working with the database, we will analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.

Oily Giant Profitable Well Prediction
[Oily Giant ](https://github.com/jodiambra/Oily-Giant/blob/main/Oily%20Giant.ipynb)
- Purpose 
The purpose of this project is to find the best location for a our customer, OilyGiant, to place a new well for mining oil. We are given oil well parameters in three distinct regions, upon which we will use to create our linear regression model. The model will predict the volume of reserves in the new wells, and the region with the highest total profit will be chosen for the new well.

Zyfra Gold Recovery Prediction 
[Zyfra Gold](https://github.com/jodiambra/Zyfra-Gold-Mining/blob/main/Zyfra%20Machine%20Learning%20Model.ipynb)
- Purpose
The purpose of this project is to prepare a prototype of a machine learning model for Zyfra, a company that develops efficiency solutions for the heavy industry. The model will aim to predict the amount of gold recovered from gold ore. The features we will use will be data on gold extraction and purification. The goal is to have the model optimize the production and eliminate unprofitable parameters.



---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
