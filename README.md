# SpamSMSFilter
A small project to build a spam-filter using supervised machine learning algorithms.

The dataset was taken from UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). It contained plain text of SMS and thier original label. 

Steps involved in building the spam-filter included:
1. Lowering the case, handing punctuations, lemmatizing and tokenizing each text
2. Removing the words that do not appear frequently in the texts and the stop-words (which appear quite freqently)
3. Generating TF-IDF vector of the texts
4. Modelling using Naives Bayes, Logisitic Regression, and Support Vector Machine (Linear Kernel) and comparing performance to a default model which classifies according to frequency of labels.
5. Using k-fold cross-validation to ensure that the models do not overfit
