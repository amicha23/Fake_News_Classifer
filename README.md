# Fake_News_Classifier

## Problem Statement
In the world today, misinformation is a siginficant problem leading indiviudals unsure what to believe. Especially in polarizing nature of politics, the structure of a reliable news source can be difficult to identify. Therefore, in this personal project I attempted to develop a machine learning program to identify when an article might classified as reliable or not.

## Data
[https://www.kaggle.com/c/fake-news/data](https://www.kaggle.com/c/fake-news/data)

## Data Description
The Data contains unique **ids** for each news article, the **author** of each article or a null value if the source contains no author, the **title** of each source, the **text** from each source, and **label** of 0 (unreliable) or 1 (reliable) representing the trust factor of a source.

## Technique
The model can be based on accuracy and mean absolute error.

accuracy = correct predictions / (correct predictions + incorrect predictions)
 
The accuracy metric measures false positives and false negatives equally.

error=|actual−predicted|

With the MAE metric, I take the absolute value of each error.  I take the average of those absolute errors to measure model quality.

## Model
A label encoder is used to convert categorical variables to numerical values. A random forest regressor and cross validation test is used to predict the accuracy of each news source presented. 
