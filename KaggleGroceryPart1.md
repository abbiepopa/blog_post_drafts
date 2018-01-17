# What I learned from Kaggle's Grocery Prediction Competition

I recently predicted grocery sales for a [kaggle competition](https://www.kaggle.com/c/favorita-grocery-sales-forecasting).
In this competition, we were responsible for using data from six tables to predict how many units of different items
would sell on future dates. This competitions presented several challenges, including merging multiple tables, working with
a data frame that was larger than RAM, and working with categorical variables that had many classes. I will discuss how I dealt
with the large data frame in part 1 of this two part blog series. I will discuss my handling of categorical variables in
part 2, which can be found [here](my cool url that hasn't been made yet).

If you want to see my work, my notebooks can be found [here](https://github.com/abbiepopa/kaggle_grocery/tree/master/scripts).

## Part 1: Dealing with data larger than RAM and Dask!