# Fake_News_Classifier

## Problem Statement
In the world today, misinformation is a siginficant problem leading indiviudals unsure of what to believe. Especially in the polarizing nature of politics and the growth of internet communication, the structure of a reliable news source can be difficult to identify. Therefore, in this personal project I attempted to develop a machine learning program to identify when an article might be classified as reliable or not.

## Data
[https://www.kaggle.com/c/fake-news/data](https://www.kaggle.com/c/fake-news/data)

## Data Description
The Data contains unique **ids** for each news article, the **author** of each article or a null value if the source contains no author, the **title** of each source, the **text** from each source, and **label** of 0 (unreliable) or 1 (reliable) representing the trust factor of a source.

## Model Technique
The model can be based on accuracy and confusion matrix.
A label encoder is used to convert categorical variables to numerical values. 
A Random Forest Classification model and cross validation test is used to predict the accuracy of each news source presented. 
