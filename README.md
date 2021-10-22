# twitter-sentiment-analysis

Built a PostgreSQL database in order to store tweets about 'Avengers' streamed from Twitter API.
Analysed the word co-ocurrence with the term 'Avengers'.
Developed a neural network to perform a sentiment analysis.
Built a network to visualize interactions between users tweeting about 'Avengers'.


DatabaseStoreStreaming.ipybn answers to the goal #1. Connects to a database, creates tables and store tweets in them, overload tweepy class to listen and capture realtime tweets.
Cleaning DB.ipybn cleans the database by removing any duplicated tweet that was collected.
Analysis of Twitter.ipybnanswer to goals #2 and #3. Retrieve tweets stored in the previous step and handle them in a pandas DataFrame, preprocess the tweet text, visualize the data and build a neural network to analyse the sentiment.
Interaction Network.ipybn answers to goal #4. Gets interaction (retweets, replies and mentions) between Twitter users who have tweet about Avengers and generates a Graph to visualize those interactions.
