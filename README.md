# TCD-ML-IncomePrediction-KaggleCompetition2
Data Analysis and Visualization:
-> Plotted every feature against the target variable to understand the correlation between them. For example, High correlation between     'Housing Situation and 'Yearly Income'
-> Plotted Heatmap to gain deeper insights of the same.
-> Plotted the frequency of each Feature

Data Pruning and Preprocessing:
-> After visually analysing the data we decided to drop the 'Crime' feature as it had little to known impact on the target coumn.
-> Handelled all the null and missing values in the data set by imputing from the inferences drawn from the data visualization and frequency of the features.
-> Encoded all the categorical features by their frequency.
-> Perform min_max normalization on the dataset.

Model Training:
-> Trained the data on LightGBM using K-fold cross validation and on XGBoost using K-Fold cross validation.
-> Tuned the Hyper parameters using Trial and error.

Final Prediction:
-> Took the average of both XGB and LGBM predictions for the final Submission.
