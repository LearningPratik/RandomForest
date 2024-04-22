# RandomForest
Random forest working and how it performs slightly different from bagging and bettern than single decision trees 

It can be used to both classification and regression problem
It does not much tuning with default values, it can work properly

Why the name Random Forest ?<br>
--------------------------------
Forest - multiple Decision trees are trained so, a group a trees.<br>
Random - It's a bagging technique so, it selects data randomly.


Difference between bagging and Random forest:<br>
-------------------------------------------------
1] Bagging can be of any algorithm --> SVM, Decision tree but random forest is used with Decision trees<br>
2] When column sampling, bagging takes lets say 2 columns and splits the data only on this column but in random forest, whenever a node is about to be created, it random sample and take random columns.<br>
Because of this more randomness compared to bagging, in some cases Random forest performs well. 
