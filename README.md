# credit-card-fraud-detection
<b>Credit Card Fraud Detection Using Machine Learning</b>
<br>
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not.
<br>
	The dataset has been picked from Kaggle.
<br>
<b>Main challenges involved in credit card fraud detection are:</b>
<br>
<i>Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.</i>
<br>
<i>Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones</i>
<br>
<i>Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.</i>
<br>
We will start the projct by importing the required libraries. Then we will import out dataset using pandas.
<br>
After visualizing the data I noticed that the data skewed which can lead our machine learning model to overfit or underfit. It maybe the case that, we would be able to achieve good accuracy but our model will not be robust. Since the ratio here is 98 to 2 hence if our model predict all data as not fraud, this way also we can achieve an accuracy of 98%. But this is not what we wanted. We want our model to be robust. So, we will take care of this in preprocessing phase.
<br>
The next step is to split our dataset in to training data and testing data. We will do so by using train_test_split from sklearn.
<br>
Then we need to fit our training dataset into the machine learning model. We will fit into different models and analyse the prediction result to see which model works best for us. 
<br>
I am using RandomForest in this case for the purpose of demonstration and it is giving the descent accuracy of 99 percent.
<br>