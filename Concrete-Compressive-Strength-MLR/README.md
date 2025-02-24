# Predicting Compressive Strength of Concrete

This project predicts the compressive strength of concrete samples using eight predictor variables: the seven ingredient proportions and the curing time. Accurately predicting compressive strength is crucial in construction, as it helps ensure material reliability and safety.

## Methodology
I use a Multiple Linear Regression (MLR) model and apply logarithmic transformations to some predictor variables to improve model performance. Additionally, backwards elimination was utilized to discover the most statistically significant predictors, ensuring a more interpretable and efficient model.

## Dataset
The dataset, available at [Concrete Sample Data](https://raw.githubusercontent.com/jholland5/COMP4299/main/Concrete_Data.csv), includes the composition of concrete samples along with their measured compressive strengths.

## Results
The final model achieved:
- R² = 0.822 (indicating that 82.2% of the variance in compressive strength is explained by the model)
- RMSE = 6.90 (suggesting an average prediction error of $\pm6.90$ MPa)

Below is a visualization of actual vs. predicted values for the test set:

<p align = 'center'>
  
![Actual vs Predicted](https://github.com/pweave5/Machine-Learning/blob/main/Concrete-Compressive-Strength-MLR/Concrete_Strength_Test_Set_Predictions.png)

</p>  

