# credit-risk-classification
1. The purpose of this analysis is to determine how well a logistic regression can predict a high risk loan vs. a low risk loan.
2. Accuarcy, Precision, and Recall of the ML model:
- The model predicts healthy loans and high risk loans with an accuracy 92.18%. This means that 92% of the time, true positives and true negatives altogether are correct 92% of the time.
- The precision of the data for those that have a healthy credit score are called with 100% precision while those with unhealthy credit are only called with 85% precision. This means that 15% of the time, healthy loans are actually being classified as high risk. Healthy loans were called with 100% precision. This makes sense because those made up most of the dataset(Over 96% of the data)
- The recall score for those who actually classified as risky, scored 91%. This means that 9% of the time, the model is predicting a high risk loan as a low risk loan. 
3. This model appears to be an excellent tool for screening out the already safe loans with high precision and recall (for that purpose I recommend it). However, I believe more data is necessary to accurately call loans that are high risk. after all, only 4% of the data includes high risk customers.
