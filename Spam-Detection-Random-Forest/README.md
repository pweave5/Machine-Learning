# Spam Email Detection
This project predicts whether an email is spam or not using 57 continuous predictors. Spam detection is a common machine learning task, and in this project, I tackle the problem using a Random Forest model.

## Methodology
A Random Forest classifier, implemented using the caret library in R, was used to classify emails as spam or valid. Initially, a K-Nearest Neighbors (KNN) model was developed for comparison. Then, a Random Forest model was built and evaluated against a baseline decision tree model from a previous project to assess improvements in classification performance.

## Dataset
The dataset, available at [Spam Email Dataset](https://github.com/jholland5/COMP4299/blob/main/spamData.csv), contains variables describing several characteristics of the email, such as word frequency, character frequency, and capital letter frequency, along with the classification label (spam or valid).

## Results
The final model achieved:

- Accuracy = 92.8%
- Sensitivity = 96.2% (spam emails were correctly identified)
- Specificity = 87.6%  (valid emails were correctly identified)
- F1 Score = 0.942
