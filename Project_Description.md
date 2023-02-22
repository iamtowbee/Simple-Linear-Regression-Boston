# Project: Predicting Boston Housing Prices

A simple linear regression model, taken from GLearning's [video](https://youtu.be/zrzXN_gib3A). \
This project kicks off my foray into applied machine learning and data science. I'd been studying lots of material over the course of two weeks, and I finally feel ready to start executing in the field.

## Project Overview

In this project, I applied basic machine learning concepts on data collected for housing prices in the Boston area to predict the selling price of a new home. I will first explore the data to address discrepancies, then I properly split the data into testing and training subsets (a 70%-30% split).

I learned how to use Pandas `iloc()` method to select specific subsets of a Pandas `DataFrame`.Next, I chose a LinearRegression learning and prediction algorithm, fitting the training data into the model.

Then, I ran a prediction on the test data and evaluated the model's performance using the mean-squared error. Although in this case, the mean error was not squared.

In all, the model achieved an error margin of `5.540490745781327`

## Software and Libraries

This project uses the following software and Python libraries:

- [Python 3.11](https://www.python.org/downloads/release/python-3112//)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
