# Cough-sound-analysis
Sound analysis using librosa 
Author: Saltanat Khalyk


The MFCC, rmse, spectral bandwidth, spectral centroid and other sound features were extracted using librosa libraries. 
Then mean values of that features were taken and saved in csv file. Those features were loaded using pandas dataframe and 
then split to train, test sets and trained on machine learning models: Random Forest, SVM,Logistic Regression, XGboost, Catboost and knn.
Random Forest has the 88% accuracy. others show poor results.

This code was modified slightly but the original source is from guys who studied at Toronto university and did sound analysis by gender: female and male sounds classification. 
I dont remember exact names. 
