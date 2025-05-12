# K-Means Clustering on Gapminder Data
This project uses K-Means Clustering to identify natural groupings of countries based on two health-related indicators: infant mortality and life expectancy. The goal is to explore how countries cluster based on these metrics, providing insights into global health disparities.

## Methodology
The analysis focused on two variables from the Gapminder dataset: infant mortality and life expectancy. Data were scaled before applying K-Means clustering. An elbow plot was generated using the Within-Cluster Sum of Squares (WSS) to determine the optimal number of clusters. Based on the elbow method, three clusters were selected.

<div align = 'center'>
  
![Elbow Plot](https://github.com/pweave5/Machine-Learning/blob/main/Gapminder_K_Means/ElbowPlot.png)

</div>  

## Dataset
The Gapminder dataset, available in the dslabs library, includes health and demographic statistics for countries worldwide. This project used a subset containing the variables infant mortality and life expectancy.


## Results
The final clustering model grouped the countries into three distinct clusters:

- Cluster 1: High infant mortality, low life expectancy

- Cluster 2: Moderate values

- Cluster 3: Low infant mortality, high life expectancy

<div align = 'center'>
  
![Clustering Results](https://github.com/pweave5/Machine-Learning/blob/main/Gapminder_K_Means/InfantMortalityVsLifeExpectancy.png)

</div>  

These clusters highlight global health disparities and become even more insightful when analyzed alongside other metrics such as GDP and continent.


