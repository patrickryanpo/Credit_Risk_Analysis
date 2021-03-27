## Credit_Risk_Analysis
ML - imabalanced-learn and scikit-learn

# Overview of the Analysis

This analysis was created to apply machine learning to the credit card dataset from Lending Club. The analysis uses different machine learning algorithms, such as, oversampling, undersampling, Smote, Smoteenn, balanced random forest classifier, and easy ensenble adaboost classifier. Through these algorithms, we are able to see credit risk predictions based on each method. 

# Results

### Oversampling
![Oversampling](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/Random_Oversampling.png)

- Accuracy Score: 63.84%
- Recall: 61%

### Undersampling
![Undersampling](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

- Accuracy Score: 54.43%
- Recall: 40%

### SMOTE Oversampling
![Smote](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling.png)

- Accuracy Score: 65.89%
- Recall: 69%

### SMOTEENN
![Smoteenn](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)

- Accuracy Score: 64.85%
- Recall: 58%

### Balanced Random Forest Classifier
![BRF](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/BRF_ClassReport.png)

- Accuracy Score: 79.21%
- Recall: 88%

### Easy Ensemble AdaBoost Classifier
![EEC](https://github.com/patrickryanpo/Credit_Risk_Analysis/blob/main/Resources/EEC_ClassReport.png)

- Accuracy Score: 93.22%
- Recall: 94%

# Summary 

- As shown in the results, the Enseble Classifiers have shown to be more accurate than the ranom oversampling and undersampling techniques. They have also performed generally better in the recall score. 

- It is recommended to use the Easy Ensemble AdaBoost Classifier, given that it scored the highest in both accuracy (93.22%) and recall (94%). More accurate predictions will allow the users and decision makers to make better decisions. 