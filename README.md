# Predictor

## The Libraries used

### The libraries that I use in this project are the following: 
#### To import the share prices
* yfinance
#### To process the data 
* pandas 
* numpy 
* warnings
#### To build the model 
* tensorflow 
* keras
* sklearn

#### To help with visualizations 
* matplotlib
* IPython.display 

## The motivation for the project

This projects represents the final capstone project for the Udacity's Data Scientist nanodegree. <br />
From a personal point of view, this prjoect is a starting point on which I will be able to further build a system that will aid me options trading and in assesing companies for investment

## The Files
* predictor.ipynb - the jupiter notebook where all the code is written 
* predictor_blog_post.pdf - pdf file containing a blog post describing the project
* LICENSE - self explanatory
* README.md - this file

## Summary of the results of the analysis

The framework developed can be reliably used to improve the parameter search for any listed company. 
These parameters are the loockback period, i.e. a year, two years etc. Look back days used to predict the next value, i.e. 3, 13, or 30. 
And the number of epochs that the model uses. 
In this project, MSFT was used as an example. For this particular company the results are satisfacatory. 
For Apple or Pfizer the results are not. Futher improvement is needed. 

## Necessary acknowledgements
The inspiration for the creation of this project is the Udacity Data Scientist course, and the DecisionForest's video on youtube that you can find [here](https://www.youtube.com/watch?v=dKBKNOn3gCE&list=PL7qHbYUK0G0rcO7YX6ZmFq37ahi0uZx9G&index=2)
 
