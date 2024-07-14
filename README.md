# Spam_Emails_Detection_Using_Naive_Bayes
 Detecting Spam emails using Naive Bayes algorithm
 # Spam Email Detection Using Naive Bayes
## Overview
This project demonstrates how to build a spam email detector using the Naive Bayes algorithm. The model is trained on a dataset of labeled email messages and can classify new emails as either spam or not spam.

## Introduction
Spam detection is a common application of text classification where the goal is to identify whether an email is spam or not. This project uses the Multinomial Naive Bayes algorithm, a variant of Naive Bayes typically used for discrete features like word counts.

## Dataset
The dataset used for this project is a CSV file containing email messages labeled as "spam" or "ham" (not spam). The file includes two columns: Category and Message.

Link to dataset https://www.kaggle.com/code/ahmedraafatmohamed/spam-emails-detection-using-naive-bayes-99/input)

   
## Libraries used

1. pandas
2. seaborn
3. numpy
4. scikit-learn


## Result
The model achieved an accuracy of 99% on the test set, indicating it can effectively distinguish between spam and non-spam emails.

## Conclusion

This project demonstrates a basic implementation of a spam email detector using the Naive Bayes algorithm. While the model performs well on the provided dataset, further improvements could be made by experimenting with different feature extraction techniques, model parameters, and larger datasets.

