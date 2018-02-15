# The Happy Citizen

## Goal:

Classify the satisfaction of citizens with their lives based on their answers to certain survey questions. Raw data was collected from the 2014 PEW Global Survey results.

## Summary of conclusions:

Based on the survey, the biggest factors correlated with citizen happiness in their personal lives were:
 - Their perception of the country's economic climate
 - Their satisfaction with the general state of the country
 - How much they valued the role of education in upwards mobility
 - How much they believed luck was a factor in upwards mobility
 - How important they believed belonging to a wealthy family was for mobility
 - The age of the participants also had an impact on their satisfaction

## Visualizations:

This project was an opportunity for me to really explore the power of customization on matplotlib. I have some nice colorful bar charts that show model effectiveness in perspective such as this one (The Old and New values show difference in accuracies of the predictions without adjusting hyperparameters, and with adjusting hypermarameters):

![Accuracy of Different Models Comparison Graph](/images/model_accuracy_comparison.png "Accuracy of Different Models Comparison")

This chart shows the best model (Random Forest) versus the baseline:

![Random Forest vs Baseline Accuracy Graph](/images/randomforest_vs_baseline_accuracy.png "Random Forest vs Baseline Accuracy")

The image below is a choropleth map visualizing the "Happiness" of citizens by Country. It was generated using plotly's python module.

![Happiness by Country Graph](/images/2014_satisfaction_by_country_source_pew.png "Happiness by Country")

## Model Evaluation:

Here is a Visualization of the ROC Curve comparing true positive and false positive rates at different decision boundary thresholds of the Random Forest Model.

![ROC Curve for Random Forest image](/images/roc_curve.png "ROC Curve for Random Forest")