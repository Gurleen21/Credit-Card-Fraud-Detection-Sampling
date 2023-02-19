# Sampling
Assignment on Sampling for UCS654

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

## Sampling Technique Description and Sampling Size Formula

1. Simple Random Sampling:
 A simple random sample is a subset of a statistical population in which each member of the subset has an equal probability of being chosen.

![image](https://user-images.githubusercontent.com/72306997/219949613-305e70c5-37f5-4e5d-815e-92e1f4d31f5e.png)

>Z = 1.96 (for 95% confidence)
>
>p = 0.5
>
>E = 0.05 (assumed 5%)
>
>n = 385

2. Stratified Sampling: 
 Stratified sampling is a method of sampling that involves the division of a population into smaller subgroups known as strata.

![image](https://user-images.githubusercontent.com/72306997/219949629-2e744eff-ae24-4702-8899-83dba4ec9670.png)

>Z = 1.96 (for 95% confidence)
>
>p = 0.5
>
>E = 0.07 (assumed 7%)
>
>S = 2
>
>n = 784 (392 for each class)

3. Systematic Sampling:
 Systematic sampling is a probability sampling method where we select members of the population at a regular interval.
Samples taken on every 4th interval

4. Cluster Sampling:
 Cluster sampling is a probability sampling method in which we divide a population into clusters and then randomly select some of these clusters as sample.

>Rows per Cluster = 20
>
>Number of Clusters = 23 (sqrt(n/2) where n is the total number of rows)

5. Multi-Stage Sampling:
 In this method a combination of sampling technique, i.e. cluster and simple random is used. The dataset is divided into clusters and then random samples are chosen from those clusters.

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
