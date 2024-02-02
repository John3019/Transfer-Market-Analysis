# Transfer-Market-Analysis

This is a semester long project for BA 476 where we asked to find a database to use for a machine learning model. The data chosen was that of soccer players statistics in order to predict their transfer market values. Below you will find a description of the data and the code

# The Data

https://www.kaggle.com/datasets/kriegsmaschine/soccer-players-values-and-their-statistics/data

The data was taken from the above kaggle link, where statistics from several seasons of soccer are visible. The website itself provides some description about what each statistic means, but to briefly describe it we had either numerical stats or descriptive.

Most statistics were numerical, such as goals scored or saves made. Descriptive ones included the team or nation a player played for. In our code we chose a few desrciptive statistics and transformed them to be numerical so we could the effect they had on a players value

# The Code

The google colab file includes all the srcipts ran when doing our analyis. The modles ran were

- Linear Regression
- Naive
- Ridge and lasso Regression
- K - NN
- Decision Trees
- Random Forests
- Boosting Model

To run the modles, make sure all training and testing data is located in the same folder so that when the colab files look for them the path matches

There is also a presentation attatched to this repo that was presented for it
