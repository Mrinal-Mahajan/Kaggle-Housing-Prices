# Kaggle-Housing-Prices
This project covers complete data preparation and some advanced modeling techniques along with the reason codes for 
regression problems. The data used here is provided in kaggle housing prices competition.
Some of the key unique features this project contains are(in sequential order):-
1. A replication of sas edd macro.
2. Transformation technique to be used for predictors.
3. Use of binary encoded dummy variables for categorical predictors.
4. Art of class outlier treatment and variable imputation technique.
5. A modified technique as an attempt to replicate proc varclus variable reduction technique in python.
6. Variance inflation factor and Backward Selection technique for variable reduction.
7. Reason codes for both kind of models(inferential and predictive using PCA). This is an important one since as far as
I remember no one whom I had interacted with in past(including some very senior executives) have ever mentined PCA to be used
in case the predictions need to explained to their clients. This is my attempt for case where we don't want to compromise on
our precise prediction and still explain to clients how the machine made the predictions.

Finally, obviously there is going to be some very elite codes to automate the process to the closest limit.

My intention with this project however is to get some feedback on further scope of improvement as well as any other 
opportunities that might come along. Moreover I am planning to have a similiar sort of techniques on prediction of
share prices on stock exchange, so I will really appreciate if someone from finance and stock markets can give some 
feedback on scalability of these techniques. As far as size of data is concerned it's not a big deal as similiar technique
can be replicated in spark.

With that long(if you get till here) info i guess I leave you with the project. Have a look and et me know your thoughts.

Regards
Mrinal
