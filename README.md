# 📊 Bitcoin on Twitter 🔢
<h2>A project for the BLOCKCHAIN AND CRYPTOCURRENCIES course part of the Master Degree in Computer Science at the University of Bologna.</h2>
<br>Evaluation of the sentiments expressed in tweets about Bitcoin, a word cloud analysis to identify the most relevant keywords in the Bitcoin context, an exploration of the most used hashtags and finally a geolocation analysis to understand the geographical regions most active in the Bitcoin discourse.

<br>Main dataset used: "Bitcoin Tweets"
<br>Link: https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets
<br>In the above link there are 2 datasets, we downloaded the first one 'Bitcoin_tweets.csv'.
This is the starting dataset on which we based our entire analysis.

<br><h3>🎯 Objectives:</h3>
The work carried out aims to attribute a correlation between the Bitcoin price trend and the tweets related to it in a certain time interval, by means of sentiment analysis while, by means of word cloud and hashtag analysis we try to give a real example to the analysed sentiment. Geolocation, although with some inherent limitations, will serve to define the countries of greatest activity of tweets related to this topic.

<br><h3>📕​ Instructions for use:</h3>
Through the notebooks it is possible to consult the results of our analysis, which are described and contextualised in the pdf report.

<br>For reasons of space, we have not uploaded the datasets we used, but you only need to download the dataset at the previous link to create them</br>
<br>- Starting from the first notebook 'tweets_sentiment', it is possible to export the dataframe 'df_sentiment' to csv at line in[100] by renaming the file 'tweets_sentimentAnalysis.csv', which will be used by both the notebook 'tweets_wordcloud' and 'tweets_hashtag'.
<br>- For the 'tweet_geo' notebook, you can always use the dataset exported in the previous point, because we need the sentiment and location.
<br>- in the 'tweet_geo' notebook, the dataset 'tweet_isLoc.csv' is used at line in[3], which is none other than the dataframe 'spacy_df'. We have done it this way in order not to have to recalculate the isLoc column at each execution.

<br>If you have any questions, please do not hesitate to contact us.
