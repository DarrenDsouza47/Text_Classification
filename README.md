# Text_Classification

Text Classification of Emails
The code of this notebook performs a simple text classification of emails based on labelled dataset ,we use bert to produce sentence embeddings and tensorflow keras for developing our model

Data:
Data Sources:https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/rules 
Data Preprocessing: downsampling “Ham” category values,convert category to integers
Data Splits: 70-30% training and test data split

Model Architecture:
Neural Network Architecture: functional model used;Input layer,Dropout layer,Dense layer
Hyperparameters: X_train,y_train,epochs=5
Training Procedure: optimizer-Adam,loss-binary_crossentropy,metrics-precision,recall,accuracy

Results:
Accuracy score:89% on test dataset
Confusion matrix scores for accuracy of predictions
inference:Model able to predict mostly spam and ham emails properly


