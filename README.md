# Heart Disease Prediction Using Supervised Machine Learning
Created a model with machine learning that predicts the likelihood of a person having heart disease based on the features provided.

The objective of our project is simple: develop a machine-learning model that can forecast the chance of a person developing heart disease based on a variety of crucial factors. The appropriate and precise data can save lives, and we are determined to make a difference.

Let's dive into the key features of our dataset:

1.  Age: Age in years.
2.  Sex: Gender (1 = male, 0 = female).
3.  Chest Pain Type: A crucial indicator of heart health.
4.  Blood Pressure: Measured on admission to the hospital.
5.  Cholesterol Level: An important serum marker.
6.  Fasting Blood Sugar: >120 mg/dL (1 = true, 0 = false).
7.  ECG Results: Providing insights into cardiac health.
8.  Max Heart Rate: A significant parameter.
9.  Exercise-Induced Angina: A yes/no indicator(1=yes; 0 = no)
10.  ST Depression: Relative to rest.
11.  ST Slope: A critical indicator during exercise.
12.  Number of Major Vessels: An important diagnostic measure.
13.  Thalassemia Type: Diverse types provide valuable insights.
14.  Target: The presence of heart disease (1 = yes, 0 = no).

Data-driven decisions in healthcare are pivotal, and this project represents the epitome of leveraging data for the greater good. This ia predictive model that assist healthcare professionals in making timely and accurate decisions.

# Model Selection and Evaluation
for this project, 8 distinct Machine learning Algorithm (XGB Classifier, Random Forest, K-Nearest Neighbours, SGD Classifier, SVC, Naive Bayes, Decision tree, Logistic Regression) will be applied to the dataset,in order to select the best fitted model for the prediction.

The accuracy, precision, recall, and ROC scores are the four main metrics that may be used to evaluate the machine learning models' performance in a supervised learning project on heart disease prediction. Every one of these measures offers insightful information about how well the model is working. After analyzing and explaining the outcomes for every model, let's decide which one worked best and offer a suggestion.

# Accuracy Score:
- Accuracy Score measures the overall correctness of predictions made by a model. It's the ratio of correctly predicted instances to the total instances in the dataset. A higher accuracy score is generally desirable.
- The Random Forest and Naive Bayes model achieved the highest accuracy score of 86.89%, closely followed by the Decision Tree 82.25%.
- The best-performing models in terms of accuracy are Random Forest, Naive Bayes, and  Decision Tree.

# Precision Score:
- Precision Score evaluates the model's ability to make correct positive predictions. It is the ratio of true positives to the sum of true positives and false positives. Higher precision indicates fewer false positive 
  predictions.
- The Decision Tree model achieved the highest precision score of 92.59%, followed by Naive Bayes at 90.0% and XGB Classifier at 87.88%.
- The best-performing model in terms of precision is the Decision Tree model.

# Recall:
- Recall, also known as sensitivity or true positive rate, measures the model's ability to correctly identify all positive instances. It is the ratio of true positives to the sum of true positives and false negatives. 
  Higher recall indicates fewer false negatives.
- SGD Classifier achieved the highest recall of 96.88%, followed by Random Forest and Naive Bayes 90.62%, 84.38% respectively.
- The best-performing model in terms of recall is the SGD Classifier.

# ROC Score:
- The Receiver Operating Characteristic (ROC) score measures the trade-off between the true positive rate and the false positive rate for different classification thresholds. A higher ROC score indicates better 
  discrimination performance.
- The Naive bayes achieved the highest ROC score of 87.02%, followed by Random Forest at 86.69% and Decision Tree at 83.57%.
- The best-performing model in terms of ROC score is the Naive bayes.

# Summary:
Based on the analysis of these metrics, the Random Forest consistently performed well across Precision, Recall, and ROC Score. It achieved the highest Accuracy Score. Therefore, the Random Forest appears to be the best-performing model for this heart disease prediction task.

# Recommendations:
Considering the Random Forest's balanced performance across multiple metrics, it is recommended to use the Random Forest as the final model for heart disease prediction in this project. However, hyperparameter tuning and further evaluation using cross-validation techniques may help optimize the model's performance further.


