%# Credit_Risk_Analysis

## Overview 

Several supervised machine learning models were evaluated to determine which one predicted credit risk the best. Imbalanced-learn and scikit-learn libraries were used to build the models and evaluate them. 

## Results

### Naive Random OverSampling Model

![RandomOS](https://user-images.githubusercontent.com/101427781/194423284-91f5c1c7-e345-4168-9556-6a0b1691d9c5.png)

The balanced accuracy score is 64%. The precision value is 99% and the recall is 65%.

### SMOTE (OverSampling) Model

![SMOTEOS](https://user-images.githubusercontent.com/101427781/194423592-bfa55108-898d-470b-9276-6e2b86d03b83.png)

The balanced accuracy score is 63%. The precision value is 99% and the recall is 64%.

### ClusteredCentroid (UnderSampling) Model

![UNCC](https://user-images.githubusercontent.com/101427781/194423833-13dc76c0-1282-47ac-ae37-f23daeed1323.png)

The balance accuracy score is low at 51%, with a precision value of 99%, and the recall is 44%.

### SMOTEENN (Over and UnderSampling) Model

![Combo](https://user-images.githubusercontent.com/101427781/194424167-32711822-d8df-40a0-9140-9d4566511014.png)

The balance accuracy score is 62%, with a precision value of 99%, and the recall is 54%. 

### BalancedRandomForestClassifier Model

![BFF](https://user-images.githubusercontent.com/101427781/194424387-b6622d4f-e6ea-4719-84ca-27778375c83b.png)

The balance accuracy score is 79%, with a precision of 99%, and the recall is 91%.

### EasyEnsembleClassifier Model

![Imbalanced](https://user-images.githubusercontent.com/101427781/194427685-fca380d9-c495-42e2-819c-64d1447703e0.png)

The balance accuracy score is 93%, with a precision of 99%, and the recall is 94%. 

## Summary

All of the models had a very high overall precision score, however the precision scores for all of the models high risk catergories were very low. In addition, the first four models have relatively low balance accuracy scores compared to the ensemble classifier models. Based on the data, I would recommend the Easy Ensembler Classifier Model because it had the highest accuracy, precision, and recall scores.
