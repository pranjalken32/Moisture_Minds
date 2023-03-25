# Moisture_Minds

Methods
<br>
We took the Two-model approach for this model. As two different datasets were provided which were collected using different sensors, with different set of parameters. Between them some parameters are common and some are different, so we decided to train two different models and first of both datasets respectively and then combine the two models to give one single output for each entry of data.
<br>
First of all, we used various Regressions models such as Linear Regression, Decision Tree Regression, Random Forest Regression and many more to get the initial base of the model. We found out Random Forest Regression works best from all the models with least Root Mean Square Error. Both the models had been trained on Random Forest Regression.
<br>
Then we went for hyperparameter tuning of the Algorithm. “n_estimators” and “random_state” were two hyperparameters that were tuned to maximize the performance of the model and minimize the error.
<br>
