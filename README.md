# supervised-Learning-Challenge
This model uses two datasets prepared externally showing credit risk. The model is used to predict whether an individual presents a risk.
The model is trained using data from 2019, with data from the first quarter of 2020 used to test the model's predictions.

Steps used were:

Generate the data using an established technique
Import data into Jupyter/Pandas
Categorise data using get_dummies
Add required additional columns for consistency between datasets
Fit models
Predict classes and check model performance
Scale the datasets
Fit models
Predict classes and check model peformance
Models used are:

Logistic Regression
Random Forest Classifier
Random Forest Regressor
The work showed that none of the models were particularly good at predicting credit risk in the 2020 data. This suggests that there are additional factors changing credit risk in 2020 which are not covered in the dataset for 2019.
The logistic regression model never converges, with or without scaling. Such a model must not be trusted in real use-cases unless the model converges (i.e. stabilises so to speak)
Also the RF model has an optimal training score. Please also remember that this is suspicious and most probably it is an indication of overfitting, or high variance, in the model (as you saw in the class). Such a model is also better not to be used in real situations without treatments.

