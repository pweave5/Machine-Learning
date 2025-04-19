# Principal Component Analysis

This project uses Principal Component Analysis (PCA) and machine learning to classify bean varieties based on 16 numerical features. Accurate classification is valuable in agricultural quality control and automation processes.

## Methodology
PCA was applied to reduce the 16 numerical predictors into three principal components, which captured approximately 90% of the variance in the original dataset. These components improved class separation, as shown in the visualization below. Two classification models were tested: K-Nearest Neighbors (KNN) and Random Forest.
<br>

<div align = 'center'>
  
![Actual vs Predicted](https://github.com/pweave5/Machine-Learning/blob/main/Beans-PCA/PCA_beans.png)

</div>  

## Dataset
The dataset, available at [Beans Data](https://raw.githubusercontent.com/jholland5/COMP4299/main/beans.csv), contains 16 numerical features extracted from images of dried beans, along with labels for seven bean types.

## Results
The final model achieved:
- KNN = 88.3% Overall Accuracy
- Random Forest = 88.0% Overall Accuracy



