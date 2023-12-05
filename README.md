# Estimating Vaccination Uptake for COVID-19 with a Focus on Interpretability
By Amish Saini and Kartik Narang

<div style="display: flex; justify-content: space-between;">
    <img src="Headshots/kartik.jpeg" alt="Image 1" width="400">
    <img src="Headshots/amish.jpeg" alt="Image 2" width="400">
</div>

## Summary of Project
The COVID-19 pandemic has had a devastating impact worldwide, causing regional disparities in COVID-19 prevalence to emerge. These disparities demonstrate a need for predictive modeling strategies to make the best decisions that reduce the burden on our healthcare system. There were many periods where the vaccination rates in the US were stagnant, despite widespread availability at many points. Understanding the most important factors that impact vaccination uptake using Genetic Programming (GP) and interpretable Tree-Based models can be fruitful to increase vaccination coverage.

Formally, we apply GP and Tree-Based models to forecast COVID-19 vaccination uptake and identify the most important factors that cause stagnant periods of vaccination rates. The goal with this is that public health officials can develop targeted interventions for groupings of populations to promote vaccine uptake.

## Results
### Tree-Based Regressors
We were able to successfully and accurately predict vaccination uptake spikes as shown in the images below.

<img src="Results/table2.png" width="400">

<div style="display: flex; justify-content: space-between;">
    <img src="Results/spike1.jpg" width="400">
    <img src="Results/spike2.jpg" width="400">
    <img src="Results/spike3.jpg" width="400">
</div>

#### Interpretability
Utilizing SHAP, we were able to interpret the model's decisions and understand the features that led to the spikes.
<img src="Results/shap.jpeg" width="800">
<img src="Results/shap2.jpeg" width="800">


## GP
After Running 500 Generations of a population size of 1000, we were not able to reach accurate results as shown in the image below. Due to the computational complexity of genetic programming and the limit computation resources available to us, our results were bottlenecked by runtime.





