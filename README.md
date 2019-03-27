# Loan-Prediction-Problem--III
AnalyticsVidhya

Problem Statement
About Company
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.

Problem
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


My Approach to the sloution :

Did some exploratory analysis and found that just one of the variables was responsible for 80% accuracy.

Did binning of numeric variables for bettere usage , used one hot encoding for categorical variables.

For Modelling Used Logistic Regression , Random Forest , ADABoost , XGBoost and tuned the parameters by GridsearchCV . 

best results on leaderboard were obtained by logistic regression !!!
