# Predicting Heart Disease

This project predicts the presence of heart disease using nine predictor variables. Early detection of heart disease is critical for timely intervention and improving patient outcomes.

## Methodology
I use a Logistic Regression model with backwards elimination to select significant predictors while maintaining strong performance metrics. The model was evaluated using accuracy, sensitivity, and specificity.

## Dataset
The dataset, available at [Heart Disease Data](https://raw.githubusercontent.com/jholland5/COMP4299/blob/main/heartData.csv), includes patient data and whether or not they have heart disease.

## Results
The final model achieved:
- **Accuracy** = 0.805 (80.5% of predictions were correct)
- **Sensitivity** = 0.757 (75.7% of heart disease cases were correctly identified)
- **Specificity** = 0.845 (84.5% of non-heart disease cases were correctly identified)
