# Loan Default Prediction 
## Dataset and Description 
Link: https://www.kaggle.com/datasets/larsen0966/sba-loans-case-data-set

The Small Business Administration (SBA) was founded in 1953 to assist small businesses in obtaining loans. Small businesses have been the primary source of employment in the United States. Helping small businesses help with job creation, which reduces unemployment. Small business growth also promotes economic growth. One of the ways the SBA helps small businesses is by guaranteeing bank loans. This guarantee reduces the risk to banks and encourages them to lend to small businesses. If the loan defaults, the SBA covers the amount guaranteed, and the bank suffers a loss for the remaining balance.

The dataset is a subset of the National SBA dataset which is much larger and may be analyzed at a later date. 

## Project Goal 
Given a loan application, determine if it should be accepted or denied by predicting if it will default or be paid in full. Prediction will be done through a ML classifiying model.

## Project Results
Out of four tested classifers, the Gradient Boosting Classifer proved to be the most accurate with a 97.41% rate post hyperparameter tuning. In other words, when given unseen data, it can predict with 97.41% accuracy whether or not the loan will default in the future.

## Future Work
* Test the developed Gradient Boosting model on the larger National SBA dataset and compare its accuracy.
* Explore other classifiers beyond Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
* Seperate the project work into seperate notebooks.
