# credit-risk-classification

**Overview**

The purpose of this analysis is to evaluate the effectiveness of the linear regression model in predicting credit risk before and after oversampling. 

**Results before oversampling:**

**Accuracy**: The accuracy score is 0.99, which means it can accurately predict both healthy loans (0) and high-risk loans (1).
**Precision score**: In the "0" class, the precision is 1.00 which means that a large number of healthy loans were predicted correctly. The precision in the "1" class is 0.86, indicating that a relatively high number of high-risk loans were predicted accurately.  
**Recall**: For the "0" class, the recall value is 1.00, indicating that it identifies almost all healthy loans. The model’s recall for the "1" class is 0.91, which means it detects a significant portion of high-risk loans.

**Results for the oversampled training data:**

**Accuracy**: The accuracy score is 0.99, which means the model successfully predicts both the “0” and “1” classes.   
**Precision score**: The oversampled trained data also produced a precision score of 1.00 for the “0” class, indicating a high percentage of correctly predicted healthy loans, and 0.86 for the “1” class, suggesting a relatively high percentage of correct predictions.  
**Recall**: The recall value is 0.99 for both the “0” and “1” classes, which means that the model identified nearly all healthy loans and high-risk loans.

**Summary**

In the first training data, the logistic regression model accurately predicts both healthy and high-risk loans with an accuracy score of 0.99. It has a perfect precision, recall, and F1-score for healthy loans and above 0.86 for high-risk loans.

The logistic regression model is able to accurately predict both healthy loans ("0") and high-risk loans ("1"), even when oversampled data is used. Like with the initial training data, the model achieves high accuracy, recall, and F1-score values for both labels. This proves that the model is effective in distinguishing between healthy and high-risk loans, even with oversampling.
