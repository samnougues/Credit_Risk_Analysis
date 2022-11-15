# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The purpose of this analysis was to look at data from LendingClub. With this data, I trained and created models to evaluate whether the loan were risky or not.

## Results:
### Naive Random Oversampling
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture1.png)
- Balanced Accuracy Score: approximately 66.14
- Precision Score: approximately 1% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 72% for high risk loans, approximately 60% for low risk loans

### SMOTE Oversampling
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture2.png)
- Balanced Accuracy Score: approximately 65.81%
- Precision Score: approximately 1% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 62% for high risk loans, and approximately 69% for low risk loans

### Undersampling
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture3.png)
- Balanced Accuracy Score: approximately 54.47%
- Precision Score: approximately 1% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 69% for high risk loans, and approximately 40% for low risk loans

### Combination (Over and Under) Sampling
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture4.png)
- Balanced Accuracy Score: approximately 67.10%
- Precision Score: approximately 1% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 77% for high risk loans, and approximately 57% for low risk loans

### Balanced Random Forest Classifier
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture5.png)
- Balanced Accuracy Score: approximately 78.77%
- Precision Score: approximately 4% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 67% for high risk loans, and approximately 91% for low risk loans

### Easy Ensemble AdaBoost Classifier
![alt text](https://raw.githubusercontent.com/samnougues/Credit_Risk_Analysis/main/Picture6.png)
- Balanced Accuracy Score: approximately 92.54%
- Precision Score: approximately 7% for high risk loans, and approximately 100% for low risk loans
- Recall Score: approximately 91% for high risk loans, and approximately 94% for low risk loans
## Summary:

The Naive Random Oversampling methods had a balanced accuracy of around 66%. The Smote Oversampling method was about 66%. The Undersampling Method had a balanced accuracy of 54.47. The balance accuracy for the combinatory sampling method was about 69%. The Balanced Random Forest had a balanced accuracy of about 79%, and the Easy Ensemble AdaBoost had a balanced accuracy of about 93%. I recommend the Easy Ensemble AdaBoost because it has the highest accuracy with data.
