# Breast Cancer Test
## 360-420-DW  00001
## Jarred Weinberger

## Distributions of Model Accuracy

K = 5

Total Average score after 1000 runs: 95.033%

Standard Deviation = 2.353%



Average Precision = 95.87%

Standard Deviation = 7.589%



Average Recall = 92.82%

Standard Deviation = 14.29%

## Analysis of different error types
 - What is a False Positive?
 
 When something is diagnosed as true when it is truly false. In our case, it is diagnosing a benign tumor as malignant.



- What is a False Negative?
 
 When something is diagnosed as false when it is truly true. In our case, it is diagnosing a malignant tumor as benign.



- What makes these two measures different?

The tumor's do not have a 50/50 chance of being bening or malignant. Therefore, the diagnosis for each will have a different probability, and different margin of error.






- What is a sensible baseline against which we should compare our model's performance?
 
Against what an acerage score would be if we were to guess the diagnosis of a tumor in this study.


