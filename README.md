# Student Depression Datasets

## Introduction

|Meet the team!|
|----|
|Jhon Paul Espiritu|
|Zanett Davila Gutierrez|
|Evans Berrocal|
|Ariel Zolton|

This project was motivated by depression being a serious issue, and one that is not uncommon to find in students. We were interested in this topic because it relates more to us, as college students ourselves, so we wanted to figure out what the most prominent features were in either contributing to or preventing the presence of depression. As this is such an important topic, we hope that it can be used to identify students potentially at risk of depression, as well as habits they can possibly work on.

## Lessons

Over the course of this project, we learned multiple lessons. First off, that not all datasets are best for all research questions. We had to switch datasets because the first one didn't provide enough insight in answer to our questions. It is important to remember, as well, that correlation does not always equate to causation, so we cannot say for absolute certainty that our resulting factors will prevent depression, just that they have a high likelihood of helping in this task. For example, having a string social support system, or increasing and improving sleep will have positive impact on one's mental health.

## Technologies

In this project, we used the Python language and multiple Python libraries to analyze our data. We also used Synthetic Minority Over-sampling Technique (SMOTE) to balance our data. Even so, our models still seemed to overfit slightly, in looking at the difference between the testing accuracy and training accuracy, so we would like to work more on that in the future. 

## Outcomes

We are pleased to note that our Logistic Regression, Decision Tree, and Support Vector Machine (SVM) all showed F1 scores higher than 0.85, which correlates to higher efficacy and reduction in unnecessary interventions. This means that less students miss out on needed help. Additionally, our SVM model showed 0 false positives as displayed on the confusion matrix, which means that students would not be falsely identified and as having depression and, consequently, would not be given unnecessary treatment; this is good because medicine can have unintended side effects, especially when the patient lacks the deficits that the drug is meant to treat. Overall, we are pleased in our project and hope that you are able to learn from and use it as well.

## Linktree

Here is our Linktree for this project: https://linktr.ee/StudentDepressionData

## Citations
|Citation|Link|
|----|----|
|Syeed, Mahbubul; Rahman, Ashifur; Akter, Laila; Fatema, Kaniz; Khan, Razib Hayat; Rajual Karim, Md.; et al. (2024). MHP (Anxiety, Stress, Depression) Dataset of University Students. figshare. Dataset. https://doi.org/10.6084/m9.figshare.25771164.v1|https://figshare.com/articles/dataset/MHP_Anxiety_Stress_Depression_Dataset_of_University_Students/25771164/1|
|Chhabii. (2024, June). Student Stress Factors: A Comprehensive Analysis, Version 1. Retrieved February 10, 2025 from https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis|https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis|

## File Guide
|File|Description|
|----|----|
|Dataset_1_Models.ipynb|"Dataset 2", the file has just not been renamed. Initial collab that "Dataset 3" is based off of. |
|Dataset_2_Sampled.ipynb|"Dataset 3", the file has just not been renamed. The collab itself is not cleaned from headers from above, but it has all models finished and oversampled.|
