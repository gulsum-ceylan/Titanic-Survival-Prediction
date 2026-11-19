# Titanic Survival Prediction

Predicting which passengers survived the Titanic disaster. This project was submitted to the Kaggle "Titanic – Machine Learning from Disaster" competition.

## Dataset
Kaggle Titanic dataset: passenger information such as class, sex, age, family members on board, ticket fare and port of embarkation.

## What I did
1. **Data cleaning:**
   - Filled missing fare values with the mean.
   - Filled missing ports of embarkation with the most common value (mode).
2. **Feature engineering:**
   - Extracted each passenger's title (Mr, Mrs, Miss, Master…) from their name.
   - Filled missing ages with the average age for each title group.
   - Created a family size feature: siblings/spouses + parents/children + the passenger.
3. **Modelling:** trained several classification models and created a Kaggle submission file for each one.

## Models compared
Gaussian Naive Bayes, Bernoulli Naive Bayes, K-Nearest Neighbors, Logistic Regression, Decision Tree, Random Forest and Gradient Boosting.

## Tools
Python, Pandas, Seaborn, scikit-learn, Jupyter Notebook
