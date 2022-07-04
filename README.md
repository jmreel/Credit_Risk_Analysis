# Credit Risk Analysis

## Overview of the analysis: 
Machine learning can process large amounts of data and it can be used to help determine credit risk. Machine learning will make the process faster and more reliable. In this analysis we will build and evaluate using several machine learning models such as: RandomOverSampler, SMOTE, Undersampling, Combination Under-Over Sampling, BalancedRandomForestClassifer and finally EasyEnsembleClassifier.  By using these models, we will predict credit risk and analyze the performance comparing the six different machine learning models. 

## Results:
### RandomOverSampler
1. Balanced Accuracy: 0.6456130066757718
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans. 
3. Recall: High risk is 0.61 and the Low risk is 0.68. 
<img width="712" alt="RandomOverSampler" src="https://user-images.githubusercontent.com/99099706/177072705-a9ea4e6f-4bc3-44f1-8982-4fb5d7e32bbb.png">

### SMOTE
1. Balanced Accuracy: 0.6234433606890912
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High risk is 0.61 and the Low risk is 0.64.
<img width="882" alt="SMOTE" src="https://user-images.githubusercontent.com/99099706/177072746-00c032c5-2d77-4a95-922b-0070336b2866.png">

### Undersampling
1. Balanced Accuracy: 0.6234433606890912
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High risk is 0.61 and the Low risk is 0.45.
<img width="906" alt="Undersampling" src="https://user-images.githubusercontent.com/99099706/177072785-e08085c0-51b6-4c95-b128-6ba69d33dd5e.png">

### Combination Under-Over Sampling
1. Balanced Accuracy: 0.52939303171092337
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High risk is 0.70 and the Low risk is 0.58.
<img width="903" alt="Comb Under:Over Sampling" src="https://user-images.githubusercontent.com/99099706/177072946-e7087fea-2bcd-446e-b660-c1a10c1d2258.png"> 

5. BalancedRandomForestClassifer
6. EasyEnsembleClassifier

## Summary: 
The models that were used in this analysis showed low precision in determining if credit risk is high. We were unable to run the BalancedRandomForestClassifer and EasyEnsembleClassifier models to determine if those would show a better precision in determining credit risk. A lot of low-risk credits were falsely detected as high risk. By falsely detecting low-risk credit, the bank will miss those business opportunities. 
