Project. Customer churn.

Customers began to leave Beta-Bank. Every month.
It is necessary to predict whether a client will leave the bank in the near future or not based on historical data on customer behavior and termination of agreements with the bank.
The goal of the project: to build 2 classification models, train them on historical data (features), choose the best one and bring its quality metrics to the maximum possible.

The project implemented 2 models: a logistic regression model and a random forest model. The random forest model showed itself to be the best, both in the selection of parameters,
as well as on the test set. The main quality metrics of a random forest model on a test set:

Accuracy of the best model: 0.863 - the proportion of correct answers predicted by the model
F1 of the best model: 0.636 - harmonic mean (positive class forecast quality)
Auc_roc was 0.868 - the proportion of correct answers of the model (or the area under the curve)

The graph of the ROC curve clearly shows how much the curve of the implemented model rises above the "curve" of the random model.
The difference between their areas is 0.86-0.5= 0.36, i.e., the implemented model is 36% more efficient than the random one and in 86% of cases gives the correct result.
