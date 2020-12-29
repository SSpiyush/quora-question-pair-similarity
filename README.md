﻿# quora-question-pair-similarity

This project basically checks whether the asked quora question is similar to any previously asked questions or not. The aim of the project was to apply various Python tools to visualise the data and to generate various new features to get better understanding of the data and after the preprocessing of the text make it ready to apply Machine Learning Models. This project includes various Machine Learning Models with hyperparameter tuning, like: Logistic Regression, Linear SVM, XGBoost.

#data.csv: Dataset file.

#quora-question-pair-similarity.ipynb: python code for processing.

#How to access the code on google colab

1) First step is to upload the file(quora-question-pair-similarity.ipynb) on google colab.

2) Than upload the data(data.csv) using following command:

from google.colab import files

uploaded = files.upload()
