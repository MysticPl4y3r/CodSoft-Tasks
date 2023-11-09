# CodSoft-Tasks

The tasks that has to be completed to finish the internship CodSoft offered:
The Machine Learning tasks that we chose to complete are :
1. Movie Genre Classification
2. Credit Card Fraud Detection
3. Customer Churn Rate Prediction

# Movie Genre Classification
In this task, the dataset provided to us contains the movie name with its genre containing summary of the movie. Based on its summary we have to classify what genre the movie belongs to. In order to proceed with this, we used Naive Bayes Classifier to predict the genre based on the words in the summary. Summary is ridden with unnessessary data like stopwords, punctuations and we need to remove them. Next we used TF-IDF to vectorize each word and assign support value to each word so that it is easy for Naive Bayes to classify the genre based on the support value of each word. This vectorized data is then used to train the data and finally predict the output.

# Credit Card Fraud Detection
The objective of this task is straight forward. To find whether a particular credit card transaction reeks of malpractice of any sort. The dataset provided contains typical transaction details such as date, name, location, etc. Our first step lies in choosing which attributes is most useful in predicting the fraud. Hence we used correlation analysis and some domain knowledge to determine which attributes is important and seperated for training it. The model that we used for this is Random Forest Classifier. We did a textbook training and testing and finally predicting the results. The accuracy of our model comes close to 99%.

# Customer Churn Rate Prediction
In commerce sectors, to obtain consistent profits, it is necessary that sufficient measures and metrics should be implemented for customer retention and new customer attraction. One of the metrics to check for this is churn rate. It signifies how many customers stop using the service after certain amount of days. To do this we employ XGBoost to find the customer churn.
