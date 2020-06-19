# Thesis_Work
Analysis on Tweets hashtag.

# Requirements
* numpy,
* pandas,
* matplotlib,
* googletrans,
* vaderSentiment,
* emot,
* nltk,
* plotnine


# Preprocessing

* Remove links
* Remove users
* Convert emoticons into words
* Convert emojis into words
* Convert to lower case
* Convert any language into english
* Remove stopwords
* Remove puntuations
* Remove numeric values

# Topics Covered

* Finding number of tweets in a particular class
* Finding total number of users in a particular class
* Finding verified users
* Time Series Plot 
* Topic Modelling on each class seperately
* WordCloud of topic words
* Sentiment Analysis of 3 classes using vader sentiment analysis tool
* Bar graphs
* Chatter plot of 3 classes
* Findinng relation of tweets with deaths and cases under RestInPeace hash only.

# How to Run
* keep the dataset folder in the same as the Jupiter notebook
* run cells sequentially

# Functions and their meaning
* getData(): 
Used for reading datafile and then classify hashtags into 3 classes. Returning count of tweets and verified users. Also a dictionary contating only required data.
* timeSeries():
For plotting tweets in an hour.
* generate_topics():
Take filter_data dictionary as input 
Returns each list storing tweets of a particular class only.
* preprocessing():
For doing preprocessing on data and removing unnecessary details.
Take list as input return a preprocessed list.

* Applied LDA model using generate_vector() and topic_model()
* display_topics():
Return a dataframe of topic words.
* def sentiment_info():
Do sentiment analysis using vader and generate sentiments for a particular class.
* generate_dataframe() 
Used for generating dataframe for chatterplot.






