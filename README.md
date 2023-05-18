# Assignment17

### Notebook
https://github.com/kapch1980/Assignment17/blob/main/prompt_III.ipynb

### Objective
To build a predictive model for determining if a client will subscribe to a term deposit.

### Training data set
Data is collected from May 2008 to November 2010 - for 43 marketing campaigns.
Data has 16 variables with labeled output result. Output result is whether the customer subscribed the term deposit or not.

### Steps to follow
Following steps were followed -
1. Defined a base model and all other models including (LogisticRegression, DecisionTreeClassifier, SVC, KNeighborsClassifier)
2. Use GridSearchCV for performing hyperparameter tuning. It allows us to define a grid of hyperparameters and automatically searches for the best combination using cross-validation.

### Top observations
SVC seems to take max time.
