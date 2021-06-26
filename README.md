# Credit_Risk_Analysis

# PURPOSE: 
## The purpose of this project is to implement different models to unbalanced classes to tackle the unbalanced classification problem during credit risk evaluation. The 

Following Credit Risk Resampling Techniques have been used:
- `RandomOverSampler`
- `SMOTE`
- `SMOTEEN`
- `ClusterCentroids`

Ensemble Learners used:
- `alancedRandomForestClassifier`
- `syEnsembleClassifier`

### Dataset used for this project is from [LendingClub](https://www.lendingclub.com/) whose vision is to expand financial opportunities for all Americans through responsible innovation.

# RESULTS:

## Credit Risk Resampling Techniques

### Sample dataset is as below and can also be found [here](https://github.com/MamidalaV/Credit_Risk_Analysis/blob/main/Challenge/LoanStats_2019Q1.csv) 

![df](https://user-images.githubusercontent.com/74985818/123527446-aae8c580-d6ad-11eb-8934-4cb1208cfed8.png)

### Naive Random Oversampling Results (Using `RandomOverSampler`)
 
![naive](https://user-images.githubusercontent.com/74985818/123528017-42e8ae00-d6b2-11eb-8f6a-1ca1519a18b6.png)

### SMOTE Oversampling Results (Using `SMOTE`)

![SMOTE](https://user-images.githubusercontent.com/74985818/123528027-5dbb2280-d6b2-11eb-8bc6-522d2694b894.png)

### Undersampling (Using `ClusterCentroids`)

![clusterCentroids](https://user-images.githubusercontent.com/74985818/123528126-2f8a1280-d6b3-11eb-8184-74831eb97139.png)

### Combination (Over and Under) Sampling (Using `SMOTEENN`)

![SMOTEEN](https://user-images.githubusercontent.com/74985818/123528133-387ae400-d6b3-11eb-9232-0036b4517467.png)


## Ensemble Learners

### Balanced Random Forest Classifier (Using `BalancedRandomForestClassifier`)

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/74985818/123528221-d1a9fa80-d6b3-11eb-8a6f-10a05b93b6ce.png)

### Easy Ensemble AdaBoost Classifier (Using `EasyEnsembleClassifier`)


# SUMMARY:


