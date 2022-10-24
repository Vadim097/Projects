# Determining the cost of cars. Gradient boosting. 

**Project description:**

To attract customers, a hotel chain has added the ability to book a room without prepayment on its website. However, if the client canceled the booking, then the company suffered losses.
It is necessary to develop a system that predicts the rejection of the reservation. If the model shows that the booking will be cancelled, then the client is asked to make a deposit. The deposit is 80% of the cost of the room for one day and the cost of one-time cleaning. The money will be debited from the client's account if he still cancels the reservation.

**Project target:** 

Develop a model, the result of which is maximizing profit.

**Project results:**

In the course of this study, a model was created to predict customer cancellations. Were considered several popular ML algorithms: Logistic Regression, Decision tree, Random forest and Support vector machines. The best hyperparameters of all 4 models were selected using cross-validation. The best model was trained on test data with subsequent evaluation by quality metrics. Quality metrics are f1-measure, Matthews correlation coefficient (MCC) and area under the rock curve (AUC-ROC).

**Stack:**

- Python 
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib
- Numpy

**Project status:** Project completed.
