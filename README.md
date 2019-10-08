# bank-transactions-categoriser
A script that categorises automatically according to historical transaction categories. Result is loaded onto the plotly dash app and used to run simple logistic regressions with count vectorizer.

## Background
I discovered a service gap by my bank when I downloaded 6 months of bank transactions data from my online banking platform. There isn't a automatic categoriser of all the bank transactions according to 'genres' such as food, transport etc. Furthermore, the raw data was messy and contained a mishmash of text and numbers. 

This categoriser is to:
+ sort according to historical labellings
+ display results on an interactive dashboard using the plotly dash app
+ conduct simple machine learning analysis with count vectoriser and logistic regression

This function has been developed into an app by Seedly here: 

<a href="https://www.youtube.com/watch?v=q3KqGgZ7TEc" target="_blank"><img src="http://img.youtube.com/vi/q3KqGgZ7TEc/0.jpg" alt="Watch" width="240" height="180" border="10" /></a>

## Note
Unlike Seedly's app, this script does not parse transaction data automatically from the online ibanking platform.

Due to data constraints, the dataset contains only 100+ samples and from only one banking provider
