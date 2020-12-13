# Scala_Project_CSYE7200

#CSYE_7200_Big_Data_Project_Covid19_Sentiment_Analysis

The purpose of this project is to analyse peoples opinions and their minds
during a pandemic. We have gathered relevant data from Twitter, built a model in NLP 
and then analysed it based on sentiments such as positive or negative.

The value of such a model can be useful for the state officials and companies to 
effectively promote right practices,change public opinion if its based on fake news, which can be helpful in containing the pandemic  
and successfully guide people with correct information.


We have made following files :

7.* Updated_Sentiment_Analysis_using_Bert_Databricks :

1. SA_using_bert_LR_Databricks : We have made an End to End pipeline in Databricks, 
we have first  trained the model using PySpark, then we get the live Twitter data using Twitter API,
we would then clean it, and apply NLP and BERT models and then predict the sentiment using the trained model.

2. SparkProjects : Trained 1.6 million Twitter Data in Scala and Spark (Intellij)

3. SA_BERT_using_TF : Trained 600k data in TensorFlow in Python, applied NLP and BERT, saved the model.

4. Get_tweets : This file stream data in python

5. data_cleaning : This is the data cleaning function which can be used at required places.

6. sample_data_200k : Sample dataset of 200k rows


**7. Updated_Sentiment_Analysis_using_Bert_Databricks : We have updated the file and fixed the error, in the new version, 
we are using the trained model, so we dont have to train model again every time we run it.
