# Walmart-Analysis-Project-

Problem Statement 

A retail store that has multiple outlets across the country are 
facing issues in managing the inventory - to match the demand 
with respect to supply. So, to manage and come up with useful 
insights using the data so that each store can use it to improve 
in various area and make prediction models to forecast the sales 
for next 12 weeks for each store.

Project Objective 

As we have to give insights for each store and to predict their 
sales and have to forecast for next 12 weeks, we will do these 
tasks for overall store as well as for some specific stores store 
no.8,15,27 and 30.

Data Description :

 Dataset Information: 

 The walmart.csv contains 6435 rows and 8 columns. 
Some more information of the data. 

For Given data there are 6435 records and 7 features and these 7 features are 
recorded for each week as follow: 

1. Store: In the given data of retail store there are 45 outlets are present. We can 
observe each stored has 143 entries of: 

a. Date of record (weekly), 

b. Total sales record for the week, 

c. Holiday flag for the week (1 or 0), 

d. Temperature: average temperature recorded during the 
week, 

e. Fuel Price: average fuel price for the week 

f. CPI: average Consumer Price Index for the week 

g. Unemployment: rate of unemployment for the week of 
record 

The evaluation report suggests the following: 

1. From the time series: 

After all forecast we can see that it is not perfectly fitting for all time 
series model but the forecast for next 12 weeks is following historical 
pattern or seasonality not identically as historical but similar kind. 

2. From the Regression models: 
 
 For the store 8,15,27,38 models are giving very less R2 is 
0.48,0.59,0.26 and 0.57 respectively. Maybe, because for each store we 
have only 143 records and with that the model not train well. 
 
 For entire data with both the model we get very good R2 score 0.976 
 And 0.929. and made good predictions that we can see in the plots 
 Also. Similarly, For the Data without the outliers R2 score is 0.95 
which is good performance. 
Moreover, outlook is imacting the weekly sales for all stores in 
different ways. how??? and more about conclusion and all, You can refer the dataset and report file in this repository.
