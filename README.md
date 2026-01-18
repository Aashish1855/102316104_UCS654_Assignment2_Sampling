# 102316104_UCS654_Assignment2_Sampling
## Introduction
This Repo is for the course predictive analytics using stats (UCS654) and topic of this assignment was sampling in which we used 5 sampling technique and 5 models were trained and accuracy score was obtained
## Dataset
The Dataset used for this is Creditcard_data.csv
## Imbalance
Imbalance was 0:763 and 1:9 so we used RandomUnderSampler to make 0:9 1:9 
## Samplers 
1. RandomUnderSampler
2. RandomOverSampler
3. SMOTE
4. NearMiss
5. SMOTEENN
## Models
1. LogisticRegression
2. DecisionTreeClassifier
3. RandomForestClassifier
4. KNN
5. SVM
## Results
  | Model | Sampling Technique | Accuracy (%) |
|------|-------------------|--------------|
| M1 | Sampling1 (RandomUnderSampler) | 0.00 |
| M2 | Sampling1 (RandomUnderSampler) | 50.00 |
| M3 | Sampling1 (RandomUnderSampler) | 16.67 |
| M4 | Sampling1 (RandomUnderSampler) | 16.67 |
| M5 | Sampling1 (RandomUnderSampler) | 16.67 |
| M1 | Sampling2 (RandomOverSampler) | 66.67 |
| M2 | Sampling2 (RandomOverSampler) | 66.67 |
| M3 | Sampling2 (RandomOverSampler) | 66.67 |
| M4 | Sampling2 (RandomOverSampler) | 16.67 |
| M5 | Sampling2 (RandomOverSampler) | 16.67 |
| M1 | Sampling3 (SMOTE) | 66.67 |
| M2 | Sampling3 (SMOTE) | 66.67 |
| M3 | Sampling3 (SMOTE) | 16.67 |
| M4 | Sampling3 (SMOTE) | 16.67 |
| M5 | Sampling3 (SMOTE) | 16.67 |
| M1 | Sampling4 (NearMiss) | 0.00 |
| M2 | Sampling4 (NearMiss) | 83.33 |
| M3 | Sampling4 (NearMiss) | 16.67 |
| M4 | Sampling4 (NearMiss) | 16.67 |
| M5 | Sampling4 (NearMiss) | 16.67 |
