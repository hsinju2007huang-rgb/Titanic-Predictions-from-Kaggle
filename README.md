# Titanic-Predictions-from-Kaggle
First submission, I did the generic set up, using "Pclass", "Sex", "Age", "SibSp", "Parch", "Fare" as my features. I converted those features into integers.
Afterwards, I set the decision tree to maximum depth 3. (basically controls how many splittings can the tree undergo, in this case it will split 3 times)
The final score was 0.77511

Second submission, I only changed the max depth to 5 and kept everything the same.
The final score was 0.77033, which is slightly lower than the first submission.
Could be due to overfitting, in which there is an over generalisation of the data, causing inaccuracy in predictions.
