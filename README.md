# Homework-Classifiers


The assignment requested us to use machine learning tools predict credit risk.

We started with changing some categorical data of a an individual owning, mortgaging or renting their home. It is because it is challenging for machine learning tools to work with categorical compared to logical data.


We started with the simple logistic regression which gave us a balanced accuracy of 0.95432.

Followed with a Naive Random Oversampling which gave us a balanced accuracy score of 0.9947.

Followed up with SMOTE Oversampling which improved  it further gave  us a balanced accuracy score of 0.9948 and then under sampling where the score fell again to 0.982.

We then performed a combined of under and oversampling which gave us a score of 0.9947 similar to the score for Naive Random oversampling.

The next exercise we did was an ensemble of machine learning models. In this exercise we also normalized the data.


The first technique we applied was balanced random forest classifier which gave us a balanced accuracy score of 0.99418. We listed the features on importance and came to the conclusion the key variables were interest rate, borrower income and debt_to_income which is not a surprise.

We also performed an easy ensemble classifier which gave us a balanced accuracy score of 0.9947.






