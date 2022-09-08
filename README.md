# CSC522_S22_P12

## Dataset

we are using kaggle_enron_email_cleaned.csv as our dataset for the task. We have extracted required data for LSTM model training from kaggle_enron_email_cleaned.csv and created enron_email_lstm.csv which we are using to train LSTM models.

## Execution Instructions

### Baseline_Models_TFIDF_CountVec.ipynb

This file contains baseline approaches (SVM, RandomForest, Multinomial Naive Bayes Classifier). It is an ipynb you can upload it in Google Colab, Jupyter Notebook and execute the file cell by cell.

### Baseline_Models_Stylometric_Features_PCA.ipynb

This file performs Principal Componenet analysis on the stylometirc features and trains baseline models on the principal components.It is an ipynb you can upload it in Google Colab, Jupyter Notebook and execute the file cell by cell. 

### LSTM_ENRON.ipynb

This file contains the Bi-directional LSTM model which is our final classifier model. Also we have saved LSTM model using pickle in the file finalized_model_weights.sav , You can directly load model from this file and predict the test data.

### EnronEmailClassification.ipynb

This file is used to do preprocessing on the original Enron dataset to generate final training CSV files.

### Kaggle_Enron.ipynb

THis file is used to generate kaggle_enron_email_cleaned.csv file which is used to train our baseline models
