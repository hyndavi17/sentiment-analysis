# sentiment-analysis
 sentiment analysis or opinion mining is classifying the given text at document/sentence or feature level. It is the computational study of opinions, sentiments and emotions expressed in text  .Whether the opinion in the text is positive ,negative or neutral .  For messages conveying both a positive and negative sentiment, whichever is the stronger sentiment should be chosen . This helps in predicting the real life outcome
 


IMPLEMENTATION
Data Access:
Registering an application:
 The first and foremost step is to register as a user and then create an app. Twitter requires users to create an app to use its APIs. It uses Open Authentication or OAuth to grant access to its APIs and data under certain terms and conditions. An app can be easily created by following these steps:
1. Log in to the app management console at http://apps.twitter.com.
 2. Once logged in, click on the Create New App button. Fill up the required fields, you may provide the callback    URL .
 3. Click on Create Your Twitter Application to complete the process. Once done, you'll be redirected to the app details page which will contain the required details for connecting to it. 
4.Our application is ready to use.We ger secret tokens and access tokens that are used to connect with twitter.
Connecting with twitter
We then connect with twitter using ROAuth package with giving consumer secret and token . Once authentication is completed. Connection is successful.
Extracting sample Tweets :
Now that we are connected to Twitter using R, the logical next step is to start using the APIs. In this section we will try to extract some sample tweets for any user. We will also see what attributes a tweet contains like favourite count,number of retweets etc.
  Data processing and normalization:
The tweets extracted are not directly used to analysis.Rather the tweets are preprocessed .For preprocess in R we have  packages like tm,  lubridate ,data.table etc.
After preprocess  data takes the form a table which is ready to use for analysis.
  Data Analysis:

Sentiment analysis: 
Twitter timelines are the new battlegrounds for brands,s and organizations to fight it out and present a winner. Twitter is also a place where users usually rant about their disappointments or share their happiness. The dynamics of human interaction and our urge to share opinionated views on wide ranging topics, from cat pictures to wars and everything in between, have reached an altogether different level.


