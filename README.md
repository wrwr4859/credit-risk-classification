# credit-risk-classification

Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression machine learning model that was trained to predict credit risk. The model was designed to classify loan applicants into two categories: 0 for healthy loans (low risk) and 1 for high-risk loans. The objective is to assess how well the model can predict credit risk and provide insights on its effectiveness for real-world application by the company.

Results

Below are the performance metrics for the logistic regression model:

Accuracy: 99%
The overall accuracy of the model is extremely high, with 99% of the predictions being correct for both healthy and high-risk loans.
Precision:
Label 0 (healthy loans): 1.00
Label 1 (high-risk loans): 0.87
The precision for healthy loans is perfect, meaning the model does not misclassify healthy loans as high-risk. However, for high-risk loans, the model’s precision is 87%, meaning that 87% of the time, when it predicts a loan as high-risk, it is correct.
Recall:
Label 0 (healthy loans): 1.00
Label 1 (high-risk loans): 0.95
The recall for healthy loans is also perfect, meaning the model correctly identifies all healthy loans. For high-risk loans, the model identifies 95% of the true high-risk loans, missing only a small fraction of them.
Summary

The logistic regression model performs exceptionally well in predicting credit risk, especially for healthy loans (0 label), with a perfect precision and recall score of 1.00. This means that the model is highly reliable in identifying loans that are unlikely to default.

For high-risk loans (1 label), the model shows strong performance with a precision of 0.87 and recall of 0.95. Although the model misses a small number of high-risk loans (32 out of 625), it correctly identifies 95% of them and makes accurate predictions most of the time when it flags a loan as high-risk.

Recommendation:
I recommend this model for use by the company, particularly for its ability to accurately identify healthy loans. While there is a slight trade-off in predicting high-risk loans, this model is still highly effective, with minimal false positives and a low number of missed high-risk loans. Its high overall accuracy and strong performance make it a valuable tool for credit risk classification. Further tuning or threshold adjustments could help reduce the few misclassifications for high-risk loans if needed, but the model is suitable for real-world deployment as it stands.
