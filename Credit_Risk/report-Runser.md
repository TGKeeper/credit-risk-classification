# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this predictive model is to sort different loans into either "healthy" or "high_risk" categories.  

* To do this, I used the train_test_split function, which as the name implies, splits the data into 2 random groups: one group serves as training for the model to evaluate and the second group is used to test how well the model can predict outcomes after training by finding the difference between the actual outcomes in the data (the classification of high risk or healthy) and the model's predicted outcome.  

* I employed the Logistic Regression algorithm, which is pretty standard when you have outcomes set up as binaries: yes/no, healthy/high_risk, red/green, etc.

* The model came up with 19,238 correct predictions to only 146 false positive or negative predictions, less than 1%.  Afterwards, I used a confusion matrix to see how well the model performed and it

## Results

### Healthy Class (True Negatives):

* Precision: The precision for the “healthy” class is 1.00. This means that when the model predicts an instance as “healthy,” it is almost always correct.

* Recall (Sensitivity): The recall for the “healthy” class is 0.99. This indicates that the model correctly identifies 99% of actual healthy instances.

* F1-score: The F1-score for the “healthy” class is 1.00, which is a harmonic mean of precision and recall.

### High-Risk Class (True Positives):

* Precision: The precision for the “high_risk” class is 0.84. This means that when the model predicts an instance as “high_risk,” it is correct 84% of the time.
  
* Recall (Sensitivity): The recall for the “high_risk” class is 0.94. This indicates that the model correctly identifies 94% of actual high-risk instances.

* F1-score: The F1-score for the “high_risk” class is 0.89.
  
OVERALL:
Accuracy: The overall accuracy of the model is 0.99, which means it correctly predicts 99% of instances.
Macro Avg: The macro average F1-score is 0.94, considering both classes equally.
Weighted Avg: The weighted average F1-score is 0.99, considering class support (number of instances) in the calculation.
        
## Summary

In summary, the model performs exceptionally well in identifying healthy instances, with high precision and recall. However, for the high-risk class, there is room for improvement in precision. Overall, the model demonstrates strong performance, but further analysis and potential adjustments can be made based on specific use cases or business requirements.



