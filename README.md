# Human-resources
We have given you two datasets , hr_train.csv and hr_test.csv . You need to use data hr_train to build predictive model for response variable ‘left’. hr_test data contains all other factors except “left”, you need to predict that using the model that you developed and submit your predicted values in a csv files.

You have to submit the probability scores, not the hard classes.

If you are using decision trees or random forest here, probability scores can be calculated as:

score=predict(rf_model,newdata= testdata, type="prob")[,1]

score=predict(tree_model,newdata= testdata, type=‘vector’)[,1]



Evaluation Criterion : auc score on test data. larger auc score, better Model
