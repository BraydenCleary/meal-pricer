Using historical data from [Feastly](https://eatfeastly.com/), I built a meal seat price recommender for chefs to maximize the number of seats they can expect to sell. After receiving the data from Feastly, I loaded the data into Redshift and cleaned/exported the tables I wanted to work with. Then, using python and scikit-learn, I built a handful of models to predict the probability of selling an individual seat at a meal, with Random Forest performing the best. Using my predicted probability and the number of seats as inputs to the binomial distribution, I built a web app that allows users to change the price of a seat and obverse the changes in the number of seats they can expect to sell. Check out the live app [here](http://bit.ly/meal-pricer)!
