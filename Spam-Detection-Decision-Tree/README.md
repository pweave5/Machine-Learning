# Spam Email Detection
This project predicts whether an email is spam or not using 57 continuous predictors. Spam detection is a common machine learning task, and in this project, I tackle the problem using a decision tree.

## Methodology
I use a decision tree, implemented via the rpart library, to classify emails as spam or valid. Initially, a simple baseline model was created using only two variables and an if-else statement. Then, a more complex model was developed using all 57 predictors to improve classification performance.

## Dataset
The dataset, available at [Spam Email Dataset](https://github.com/jholland5/COMP4299/blob/main/spamData.csv), contains variables describing several characteristics of the email, such as word frequency, character frequency, and capital letter frequency, along with the classification label (spam or valid).

## Results
The final model achieved:

- Accuracy = 0.905 (90.5% of predictions were correct)
- Sensitivity = 0.888 (88.8% of spam emails were correctly identified)
- Specificity = 0.939 (93.9% of valid emails were correctly identified)

Below is a visualization of the final tree developed.

<div align = 'center'>
  
![Decision Tree](https://github.com/pweave5/Machine-Learning/blob/main/Spam-Detection-Decision-Tree/Email_Decision_Tree.png)

</div>
