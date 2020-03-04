# DNN-from-scratch-for-credit-card-fraud-detection
This project is about identifying credit card fraudulent activities using deep neural network. The dataset was taken from https://www.kaggle.com/mlg-ulb/creditcardfraud
and consisted of imbalanced distribution f target variable. There were approximately 284,000 records out of which only 492 were marked as fraudulent activities. Due to the nature of the distribution of target variable, SMOTE was performed on the dataset as otherwise, the model could not capture the minority event.

The dataset had the values in the columns named V1, V2, V3,...... V28 etc. These were the variables created after PCA. 

To create a 4-layered neural network from scratch, matrix vectorization was used for faster computation. The image below summarizes the algorithm used.

![image](https://user-images.githubusercontent.com/54930611/75917020-fcb56e80-5e1e-11ea-8da5-428555c4f39a.png)


To evaluate the model's performance, accuracy and sensitivity were checked.
