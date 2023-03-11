# NLP-Sentiment-Analysis-Canadian-Election

Analyzing Public Opinion on the Canadian Political Landscape Through Sentiment Analysis of 2021 Election Tweets.

The goal of this project is to perform sentiment analysis on Canadian election tweets and answer the research question: "What can public opinion on Twitter tell us about the Canadian political landscape in 2021?". 

The dataset is comprised of tweets about the 2021 Canadian election from the announcement to the day before the election. 
The provided notebook includes the code for this project and consists of four main steps: data cleaning, exploratory data analysis, model implementation and tuning, and testing.

Step 1, I developed a pipeline to clean the Canadian Elections tweet dataset. This included removing emojis, URLs, stop words, punctuation, and lemmatizing the text.


Step 2 of my project, I explored the dataset by creating various plots and functions to better understand the tweets and their relationship with the political parties. I designed a procedure to determine the political party of a given tweet based on the hashtags and mentions within the tweet. Later on, I created bar plots to visualize the split between positive and negative tweets for each political party in the dataset. Additionally, I plotted the distribution of the tweets based on their affiliation with each party. To gain further insight into the most commonly used words in the tweets, I created word cloud figures to display the words with the highest frequency in the dataset.


Step 3, I used TF-IDF and Bag of Words to prepare data for training and tuning seven classification algorithms (logistic regression, k-NN, Naive Bayes, SVM, decision trees, Random Forest, and XGBoost). The best performing model was selected.


Step 4, I tested the model on a separate dataset to determine its overall performance on unseen data.
