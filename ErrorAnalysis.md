# Breast Cancer Test
## 360-420-DW  00001
## Jarred Weinberger

## Distributions of Model Accuracy

K = 5

Total Average score after 1000 runs: 95.033%
Standard Deviation = 2.353%

Average Precision = 95.87%
Standard Deviation - 7.589%

Average Recall = 92.82%
Standard Deviation = 14.29%

## Analysis of different error types

 - What is a sensible baseline against which we should compare our model's performance?
 Against the labels given in the test data.
 
 - What is a False Positive?
 When something is diagnosed as true when it is truly false. In our case, it is diagnosing a benign tumor as malignant.

- What is a False Negative?
 When something is diagnosed as false when it is truly true. In our case, it is diagnosing a malignant tumor as benign.