# Stock_Price_Prediction_Linear_Regression
Machine Learning - Stock Price Prediction - Linear Regression
Before Investing into any company an investor should study Historical stock Prices of that company , analyze the Opening-closing and High/Low Prices for better understanding of the performance of that company in share markets. Here we are predicting the Closing Price of PT Astra International Tbk (One Year Span) Shares with the available Independent Features.
Details about the data :

From this Data we can get to know :
1) Which Feature or Features are significant in predicting the close Price.
2) How well those Features describe the Close price of this Company.


Exploratory Data Analysis
Exploring and creating various graphical representations to understand the data better.

![download (1)](https://user-images.githubusercontent.com/106465570/170859835-0544fed2-7aa0-4248-9319-b0f292ddb1c5.png)

OBSERVATIONS

Wednesday , Tuesday and Thursday are the days when maximum Volume takes place.

Usually the stock is at high price on Wednesday , Thursdays and Monday.

In 2021, the stock price was at its low, the line elevated when the price started rising and from then the line went on elevating till 2021 till April 2022

The line has formed a peak at the 10th month in the graph , which means that maximum Volume happens in the month of October.

The line has formed a peak at the 4th month in the graph , which means that maximum High price happens in the month of April. 

We got a Generalized Model By using Multiple Regression with accuracy of 99%.



Conclusion
1) For Simple Linear Regression - After Applying Simple Linear Regression we got 99% accuracy for both training as well as testing set . The R score = 0.99 and MSE = 788.71
<img width="359" alt="Screenshot 2022-05-29 001358 (2)" src="https://user-images.githubusercontent.com/106465570/170859942-c884cdcc-4287-4155-bb45-edfbc7a940a2.png">


3) Multiple Linear Regression. Multiple Regression also gave us 99% accuracy with R score = 0.99 and MSE = 1637.06
<img width="377" alt="Screenshot 2022-05-29 001300 (2)" src="https://user-images.githubusercontent.com/106465570/170859912-04026638-0ddc-4f25-9ff1-0c1de57cb8c4.png">


We can Conlclude that both the algorithms are perfect for predicting the Close Price

