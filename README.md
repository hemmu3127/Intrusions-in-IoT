# Intrusions-in-IoT
In this dataset we have different intrusions happening in network. With this Data we can build a predictive model which can predict an intrusive attacks. In this I have used Tree based methods like Decision Trees and Random Forests, with that Boosting methods like XgBoost, AdaBoost and CatBoost is used, with this Logistic Regression and KNN is used

At First the dataset is read and we have checked the number of rows and columns. With this we have found there are 47 columns, in that 25 columns are Float and 21 columns are Integer type, only one column is of string type and we have used label encoder to encode the string data. 

There are no null values in the dataset and duplciated values are checked and removed. The data is splitted to 70% train data and 30% test data.

Algorithms like Random Forest, Decision Tree, XgBoost and CatBoost gave accuracy of 99%.
