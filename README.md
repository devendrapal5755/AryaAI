File structure:

THe above notebook consist of feature exploration and analysis and model developemnt process
prediction_test.csv containig the result of test data.
xgb_model is the saved model

conclusion:
The data was skwed data towards 0 having no linear corelation wrt to target
The data was wasn't having any high corelation no big corelation wrt to target or with each other(features)
The XGB probabilty based model was choose for such data because of XGBoost capability of forming boosting trees supporiting weak leraners
The propabilty scores were having clear sepration with 0.5 as threshold betweeen 1 and 0
The F1 score for the validation data set was 90 and 91 from training data
