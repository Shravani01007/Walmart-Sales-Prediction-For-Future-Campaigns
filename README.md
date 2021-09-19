# Walmart-Sales-Prediction-For-Future-Campaigns

Walmart is one of the largest retailers in the world and it is very important for them to have accurate forecasts for their sales in various departments. Since there can be many factors that can affect the sales for every department, it becomes imperative that we identify the key factors that play a part in driving the sales and use them to develop a model that can help in forecasting the sales with some accuracy.

This project was developed in order to learn how to use different ML algorithms to predict the sales of a Walmart and compare them. For this project, we have used the dataset available from ‘Walmart Store Sales Forecasting’ project that was available on Kaggle. In this dataset, we have weekly sales data for 45 stores and 99 departments for a period of 3 years. In addition, we had store and geography specific information such as store size, unemployment rate, temperature, promotional markdowns etc. Using these factors, we needed to develop a regression model that can forecast the sales and is also computationally efficient and scalable.

The codes are separated in three jupyter notebooks where we first explore the data and decided which characteristics of the dataset will be used for the models.The three different datasets were were merged in one dataset . Then, we cleaned the dataset removing the columns with more than 40% of missing values and applied one hot encoding to categorical values(initial and cleaned both datasets provided in zip file).Finally, we built the machine learning algorithms and calculated their accuracy.

Different Algorithms used for prediction are as follows:
1)	Linear Regression
2)	KNN Regressor
3)	Decision Tree Regressor
4)	Random Forest Regressor

The jupyter notebooks are listed below:
1)	
2)	

<h2>Conclusion</h2>

In conclusion, we predicted the weekly sales using different algorithms which can be used by Walmart to forecast its future sales. This project dealt with the 
implementation of four algorithms namely, Linear Regression,KNN Regressor, Decision Tree Regressor, Random Forest Regressor on the Walmart dataset and a comparative analysis was carried out to determine the best algorithm. Decision Tree Regressor showed very good accuracy for the best implementations. These algorithms could possibly produce
even better results if they are provided with better hardware electronics like Graphics Processing Units (GPUs), and their use would be beneficial in providing valuable insight,thus leading to better decision-making.

## Requirements
Python 3.6 or higher

## Installation
To use in a python3 virtual environment, create the environment, activate it and run:

    $ pip3 install -r requirements.txt

## Usage
To run the jupyter-notebooks open the terminal and run:

    $ jupyter-notebooks

Then open the files in order and run each cell of the notebooks.

<h3>Team Members:</h3>

Sneha Sable:Github(https://github.com/Snehasable23) LinkedIn(http://www.linkedin.com/in/snehasable)

Shravani Dhuri:Github(https://github.com/Shravani01007) LinkedIn(www.linkedin.com/in/shravanidhuri)

Hrutik Naik:Github(https://github.com/hrutiknaik11) LinkedIn(https://www.linkedin.com/in/hrutik-naik-b409551a1)

Shrumi Dedhia:Github(https://github.com/shrumidedhia03) LinkedIn(https://www.linkedin.com/in/shrumi-dedhia-17b038203/)

Vikram Rao:Github(https://github.com/Vik13Rao) LinkedIn(http://www.linkedin.com/in/vikram-rao13)

