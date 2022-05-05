# Food Sales Predictions
For this project we employ Machine Learning techniques for Data Visualization using Python, in order to predict the sales of the items of the various Supermarket Outlets depending on the features embeded in the data set for each product, type of store, location and many more. 

By: Diana Valladares


Problem

In order to see the increase of sales, we employ this Kaggle dataset to evaluate and predict the sales of each of the various stores in the data set. I hereby analyzed the varios features and attributes given to explore how we can predict the sales of company stores in the future. 

Data

The data included within my repository containes, Item sales per outlet, the otems description like weight, visibility, fat content, the type of item and other varibles like the size of the supermarket, the type and the ordinal levels to each supermarket depending on their size. 

Results

Some of our results include: 
A slight correlation between the Item MRP and Item Outlet Sales.
A standard average for sales throughtout the years, with the exception of the first year and the year 1997, where we can see a dip. 
The linear regression equation returned a correlation coefficient of 0.67 - semistrong correlation. 
The RandomForrest Regression model returns a correlation coeficient or an R-value of 0.94 on the training but 0.24 on the test.  

<img width="390" alt="Screen Shot 2022-04-28 at 8 47 05 PM" src="https://user-images.githubusercontent.com/96541076/165874708-0645cb3e-a23a-44df-b5d2-d9253503ddde.png">

Slight correlation for Item_Outlet Sales and Item_MRP

<img width="429" alt="Screen Shot 2022-04-28 at 9 05 39 PM" src="https://user-images.githubusercontent.com/96541076/165874884-90ade1d6-85d6-4e48-a2f8-d81f1c8a83a9.png">

Random Forest Regression was the prefered model occupied for this dataset. Forest Regression is a supervised learning model in machine learning. Random forest combines Bootstrapped Data and Decision Trees to form precitions in order to provide better results. If the data is large it can be quite slow. 
Between all the models, rf, Random Forest Regression model presented itself to be the most compatible with this dataset. It had established a .94 R2 correlation for the training data, along with a 0.55 R2 for the Testing data after tunning the model. We found the following results: 

<img width="819" alt="Screen Shot 2022-05-05 at 12 32 43 PM" src="https://user-images.githubusercontent.com/96541076/166992787-08454940-0180-4f56-a168-95bd71ba2dcb.png">

MAE is the mean absolute value of the errors or the average error. The average error in this case is 298.00 which means tha this value is the difference between the training and testing data extracted by the averaged absolue difference over the data set. 

MSE is the mean squared error, useful for optimization. This value is basically the value squared of the RMSE (RMSE is easier to understand). 

R^2 is the coefficient of determination of correlation coeficient as we call it in behavioral science reseach tells us how accurate our model has established calculations. 

RMSE is the square root of the mean sqaured errors (MSE) and it usually has to lie within the range of the targeted data. In this case our RMSE is 1'113.13  for the testing and 431.00 for the training which lies within the range of the "Item_Outlet_Sales" values. 

Reccomendations & Limitations

I would reccomend using Forest Regression Model for this data set as it fits better on both Training and predicitons, Testing data

Next Steps

Random Forrest Prediciton model is not ready to use - high variance, low bias. 
