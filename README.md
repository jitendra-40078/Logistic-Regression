# Logistic-Regression
Creating a logistic regression model using python on a bank data, to find out if the customer have subscribed to a specific plan or not.

# Problem Statement:
The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

In this project, you need to build a model for deciding whether a campaign will be successful in getting a client to sign up for the term deposits.

Dataset:

https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

# Data Description:
Bank client data

1) age (numeric)
2) job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self- employed','services','student','technician','unemployed','unknown')
3) marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4) education: (categorical "unknown","secondary","primary","tertiary")
5) default: has credit in default? (binary: "yes","no")
6) balance: average yearly balance, in euros (numeric)
7) housing: has housing loan? (binary: "yes","no")
8) loan: has personal loan? (binary: "yes","no")

Data related to the last contact of the current campaign:

contact: contact communication type (categorical: "unknown","telephone","cellular")
day: last contact day of the month (numeric)
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
duration: last contact duration, in seconds (numeric)

Other attributes:

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

Output variable (desired target):

y: has the client subscribed a term deposit? (binary: "yes","no")

# Objectives:

You are required to prepare a well-commented an interactive python notebook as your solution to this problem statement. The notebook must meet the following objectives

Clean the data and drop useless columns.
Make an EDA report, i.e., perform a univariate and bivariate analysis. Also, derive new features based on the given features, remove outliers and correlated variables if necessary.
Visualize the distributions of various features and correlations between them.
Perform feature engineering to extract the correct features for the model.
Build a logistic regression model
Evaluate the model used.

# Model Evaluation:

This model give 75% accuracy.


