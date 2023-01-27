# Social_Media_Analysis

The dataset contains tweets that mention virus and the virusShell vulnerability, involving arbitrary code execution.

The data has been gathered through the Twitter API and contains tweets from December 9, 2021 through December 24, 2021.

Its purpose was to study the evolution of the interest in the virus vulnerability.

The elements of the dataset (“dataset.csv”) are detailed as follows:

-status_id refers to the tweet status id (Valid, Mismatched, Missing, Other)
-status_date indicates the date the tweet was tweeted
text contains the text of the tweet
favourite_count indicates the number of times the tweet was liked
retweet_count refers to the number of times the tweet was retweeted
user_name is the ID of the user who posted the tweet
screen_name indicates the user Twitter handle (@name)
user_follower_count is the number of follower of the user  who posted the tweet
user_friends_count is the number of users the poster follows (friends)  who posted the tweet
user_created_date refers to the date the user account was created
user_location indicates the user location
source is the source of tweet (Web App, Android, iPhone, etc.)


The goal is to provide us with an exploratory analysis of the dataset and meaningful insights about the experimentation. 

I did Analysis using below Research Questions:

-	RQ1: How is the correlation between retweets and favorites? Was this expected? Is this related to this dataset?
-	RQ2: Can we observe different clusters of users based on their characteristics and/or sharing activities? 
-	RQ3: Can we use machine learning approaches to predict the number of likes/retweets/followers based on users characteristics and shared content? Be creative both in the machine learning pipeline and, in particular, in the feature extraction (HINT: you can use NLP, network science, statistical techniques, etc

