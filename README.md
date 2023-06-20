# Credit Card Fraud Detection | Sampling
Assignment on Sampling for UCS654(Predictive Analysis using Statistics)

## Description
This assignment focuses on a Credit Card Dataset that requires binary classification.
However, Since the dataset was highly imbalanced in nature,So random oversampling technique(SMOTE) and random undersampling technique(imblearn.underSampler) was applied to rectify the situation. 
After balancing the dataset, five unique models were employed and subjected to different sampling techniques to gauge their accuracy on the testing set. 

## Methodology
1. Balancing Dataset
2. Creating different types of samples
3. Training different machine learning models
4. Testing the models
5. Analysing the Result obtained

## Sampling Technique 

1. Simple Random Sampling
2. Stratified Sampling
3. Systematic Sampling:
4. Cluster Sampling:
5. Multi-Stage Sampling:


## Machine Learning Classification Models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. KNN
5. Naive Bayes

## Final Result Table
<img width="640" alt="image" src="https://user-images.githubusercontent.com/79686365/219976331-b464f84a-e59f-442e-8d3c-5d6a56a19d84.png">

## Discussion
From the final Accuracy table, we can conclude that Maximum Accuracy is achieved when we apply Random Forest Algorithm upon taking samples using the Cluster Sampling technique. We get an accuracy of 99.73%.

## License
© 2023 Gurleen Kaur
This repository is licensed under the MIT license. See LICENSE for details.
[MIT](https://choosealicense.com/licenses/mit/)
