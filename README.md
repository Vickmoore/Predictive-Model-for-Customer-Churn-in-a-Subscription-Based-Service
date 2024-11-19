1. Model Evaluation Report
   Summary of Model Performance
   The Customer Churn Prediction Model has been evaluated using several classification metrics to assess its predictive power and performance. Below are the results from the evaluation:

- Accuracy:
  The model’s accuracy is 0.68, meaning that the model correctly predicted churn or non-churn for 68% of the test samples.

- Precision:
  The precision score is 0.31, which means that when the model predicted a customer would churn, 31% of those predictions were correct. A relatively low precision indicates that the model may be making a large number of false positive predictions.

- Recall:
  The recall score is 0.05, which indicates that the model correctly identified only 5% of the actual churn cases. This suggests that the model is not performing well in capturing the customers who are actually likely to churn.

- F1-Score:
  The F1 score, which is the harmonic mean of precision and recall, is 0.08, indicating poor performance in balancing precision and recall. The low F1 score further reflects the model's inability to effectively capture churn predictions.

- AUC-ROC:
  The AUC-ROC score is 0.50, which suggests that the model's ability to distinguish between churn and non-churn customers is no better than random chance. This score indicates the need for further model improvement.

- Confusion Matrix:
  The confusion matrix shows the number of true positives, true negatives, false positives, and false negatives. It is useful in visualizing the model's performance and can be plotted using:

2. Feature Importance Report
   The feature importance report explains which features played the most significant roles in predicting customer churn. Feature importance is evaluated based on how much each feature contributes to reducing uncertainty or improving the predictive power of the model. Random Forest, the algorithm used in this model, assigns an importance score to each feature based on how well it splits the data.

Explanation of Key Features:

- Tenure: The length of time a customer has been subscribed to the service. This feature is critical in determining churn likelihood, with longer-tenured customers less likely to churn.

- Usage Frequency: The frequency with which a customer interacts with the service. Higher usage indicates a lower likelihood of churn.

- Customer Service Interactions: Features related to complaints, responses, or service calls can indicate dissatisfaction. Customers with more service interactions, especially negative ones, are more likely to churn.

- Subscription Type: The type of subscription the customer holds. Certain subscription plans might have higher churn rates than others, depending on pricing, features, etc.
  These features have the highest importance in predicting whether a customer is likely to cancel their subscription.
