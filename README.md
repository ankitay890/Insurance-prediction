# Insurance-prediction
Consider the data present in the Insurance dataset file. Following is the attribute related information:
* age: age of primary beneficiary
* sex: insurance contractor gender, female, male.
* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg/m^2) using the ratio of height to weight, ideally 18.5 to 24.9.
* children: Number of children covered by health insurance / Number of dependents.
* smoker: Smoking, yes or no
* region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
* charges: Individual medical costs billed by health insurance

Problem statement: To predict the approximate insurance cost based upon the rest of the features provided for each individual.




It is a Machine Learning project that predicts the approximate insurance cost based upon the features provided for
each individual. It is a Regression problem.
The algorithm used in this peoject is Linear Regression.
Executed the steps like Data preprocessing, Feature selection, Model Building, Evaluation & Tuning. 

The model was build on base linear model, Ridge, LASSO and Elastic Net techniques.
The Ridge technique gave the best results. The Root mean squared error was least in this.
* R-squared: 0.705
* RMSE: 0.487
* Adj R-square: 0.703
