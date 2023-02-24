# Ensemble-Learning-Project

1. Introduction
2. 
Stacked generalization is a method for combining estimators to reduce their biases.

It harnesses the capabilities of a range of well-performing models on a classification or regression task.


The predictions of each individual estimator are stacked together and used as input to a final estimator to compute the prediction.

The benifit of stacking is that they have better performance than any single model in the ensemble.



Structural Diagram of Ensemble Techniques

<center><img src='https://raw.githubusercontent.com/insaid2018/Term-3/master/Images/16083537046041326.png'></center>

Problem Statement

The US Adult Census dataset is a repository of 48,842 entries extracted from the US Census database.

We aim to predict whether an individual’s income will be greater than $50,000 per year based on several attributes from the census data.

I will be using different ensable learning techniques to check different model accuracy

Target Variable Distribution

![image](https://user-images.githubusercontent.com/106458239/221136851-af3f4f52-6840-48a8-af07-9500a871497c.png)

Age Distribution

![image](https://user-images.githubusercontent.com/106458239/221136940-75e9a6cd-3416-4a6d-92c2-0f48cda5e687.png)
- From the above distributionplot we can see that Mean & Median age is nearest to 40.
- Age column is skewed to right. Having many customer's age in range of 70-90
- For better understanding we will bin the age column in 3 bins **Young**,**Middle_Age** & **Old_Age**

![image](https://user-images.githubusercontent.com/106458239/221137030-0f1ace51-b8d2-40aa-acab-5414ebd7aacd.png)


![image](https://user-images.githubusercontent.com/106458239/221137222-271c313c-7487-4c72-8280-64c0c8f6cbec.png)


**Model Perfromance**

**Conclusion** 

- So far best accuracy achieved by Catboost with Train score 0.8808 And Test score 0.8683
- Stacking results are nearest to our best model 

![image](https://user-images.githubusercontent.com/106458239/221149787-cc4e1234-a3cc-4439-806c-6ad415b5b4f7.png)


**Dashboard created using Tableau tools** 
