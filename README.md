# credit-risk-classification

OVERVIEW OF THE ANALYSIS:
Explain the purpose of the analysis:
•	In this challenge, we aimed to build a machine learning model to identify the creditworthiness of borrowers using historical lending data from a peer-to-peer lending services company. We calculated and predict good loans (0) and bad loans (1) to issue a loan



Explain what financial information the data was on, and what you needed to predict:
•	Financial information included loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and loan status (good or bad).
•	We needed to split the data into Training and Testing Sets and create a Logistic Regression model to predict weather a loan would be classified as good (0) or bad (1).

Provide basic information about the variables you were trying to predict:
•	We used logistic regression to predict loan status.
•	Loan status distribution: good loans (0) and bad loans (1).

Describe the stages of the machine learning process:
•	Data preprocessing: read the CSV file into a Pandas DataFrame, separated data into labels and features.
•	Data splitting: split the data into training and testing datasets.
•	Data scaling: scaled the data.
•	Model training: trained a logistic regression model.
•	Prediction: made predictions using the test data.
•	Evaluation: generated a confusion matrix and printed the classification report.

Briefly touch on any methods used:
•	Logistic regression was the only method used for training the model and it was successful at predicting good and bad loans at high accuracy.

RESULTS:
Machine Learning Model 1: Logistic Regression
•	Classification report shows 99% accuracy score.
•	Precision: 100% for predicting good loans (0) and 84% for predicting bad loans (1).
•	Recall: 99% for predicting both good loans (0) and bad loans (1).

SUMMARY:
•	Regression model performed well for the given data.
•	Precision score was very high, indicating accurate prediction of both good (0) and bad (1) loans.
•	It is more important to predict bad loans (1) accurately.
•	Recommendation: Logistic Regression, due to its high precision scores and successful prediction of both true positives and true negatives.
![image](https://github.com/NesAtar/credit-risk-classification/assets/148135912/45eb8204-cf2c-45f8-aaf0-bf0805e4af24)


