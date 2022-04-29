# Food Sales Predictions
For this project we employ Machine Learning techniques for Data Visualization using Python, in order to predict the sales of the items of the various Supermarket Outlets depending on the features embeded in the data set for each product, type of store, location and many more. 

By: Diana Valladares


Problem

In order to see the increase of sales, we employ this Kaggle dataset to evaluate and predict the sales of each of the various stores in the data set. I hereby analyzed the varios features, and individual filters to explore how we can predict the sales of company stores in the future. 

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

We can also see the Decision Regression Trees Max depth where our R2 is 0.67 on the train data. 

<img width="555" alt="Screen Shot 2022-04-28 at 9 07 16 PM" src="https://user-images.githubusercontent.com/96541076/165875005-7dc06ac4-b00c-48f9-bfe6-ac3aee1c0813.png">

Reccomendations

I would reccomend using the linear regression model as it is predicitng a bit better than decision trees or Random Forrest Predictions. 

Limitation & Next Steps

Random Forrest Prediciton model is not ready to use - high variance, low bias. 
