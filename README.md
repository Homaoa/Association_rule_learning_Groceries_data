# Association_rule_learning_Groceries_data

An association rule learning model is developed for a groceries dataset. Each row of this dataset is a transaction that happened in a store. There is 32 items in this dataset. Data preparation and model building are done on the data. Apriori model is used in order to obtain rules for these items.

After obtaining the rules, I have put them in a data frame, so the results can be observed better.

Lift is used as a metric to compare the strength of different rules. The results are sorted based on lift to make finding the strongest rules easier.

Also, the model is designed to look for rules with two items. Of course, the model can be used to find rules for an many as items that is needed. 

At the end, the result is saved as a csv file.

Data source : http://www.sci.csueastbay.edu/~esuess/classes/Statistics_6620/Presentations/ml13/groceries.csv

