# DIABETES-INDICATOR

Diabetes Health Indicators
The Diabetes Health Indicators Dataset contains survey responses about individuals and their diabetes status. It includes survey responses related to health and lifestyle factors. It used to explore the risk factors associated with diabetes and provide accurate predictions of whether an individual has diabetes


#### This report summarizes the model training and testing process for predicting diabetes using the Diabetes Health Indicators dataset.

The Target variable, the Features selected and
Split into 80% training, 20% testing using.

Two models were chosen:
- Random Forest Classifier
- K-Nearest Neighbors Classifier
and models were trained using the training dataset.

Predictions were made on the testing data using each model.

Evaluation metrics:
Confusion matrix
Classification report (including precision, recall, F1-score, and accuracy)




# OUTPUT SUMMARY

Confusion Matrix:

True Negatives (TN): 36079

False Positives (FP): 2098

False Negatives (FN): 5275

True Positives (TP): 1316


F1-score: This is a balanced measure of precision and recall.
0.0 (No Diabetes): 0.91
1.0 (Diabetes): 0.26

Accuracy: Overall accuracy of the model (0.84)
Macro Avg: Average of precision, recall, and F1-score, not considering class imbalance.


The model has high accuracy and precision for the "No Diabetes" class, indicating good performance in identifying individuals without diabetes.However, it has low precision and recall for the "Diabetes" class.



