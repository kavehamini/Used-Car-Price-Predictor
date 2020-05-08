# Used Car Price Predictor


### Introduction

In this project the data including the make, model, model year and mileage of used cars are scraped and different machine learning models are used to perform predictions on used car prices.


### The Data

The data used in this project was scraped from Autotrader website https://www.autotrader.ca/.


### Tools Used

splinter and chromedriver.exe have been used for scraping. Python and its modules such as pandas, numpy, matplotlib, seaborn, etc have been used for analysis of the data. Also sklearn module of python has been used to create Linear regression, Decision Tree and Random Forest machine learning models.

### Data Analysis and Visualization

Here some visualiztions are illustrated as sample. For all visualizations and analysis results please refer to the jupyter notebooks.

The figure below illustrates the distribution of the numeric variables in the dataset which indicates they are relatively normally distributed.

<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/1.png">

Figure below illustrates the number of each car make (Car Type) in the dataset.
<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/2.png">

The number of each car make by year (model year) in the dataset has been depicted in the figure below.
<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/3.png">

The graph below shows the prices of each car make (car type) in the dataset.
<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/4.png">

Plotting Price versus the Milage and also versus the Model Year shows the correlation between the numerical data. 
<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/6.png">

<img src="https://github.com/kavehamini/Used-Car-Price-Predictor/blob/master/7.png">


### Conclusion


Linear regression, Decision Tree and Random Forest ML models were used to perform predictions on used car prices and although all three models had acceptable performance, Random Forest had better scores and lower standard deviation.




### Author

This project has been inspired by many similar projects on GitHub.com and has been performed by Kaveh Amini (kvhmni@gmail.com).
