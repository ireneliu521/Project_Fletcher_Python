## MVP Summary
-----------

### Domain

The two main objectives of this project is to build an article summarizer and apply sentiment analysis on the news articles. Text summarizer is commonly used in helping make dashboards for decision maker and sentiment analysis is also used to scrape off the redundant features. By combining these two, hopefully I can build a model that can help deciders make better strategies. Extra part of this projecy will be using Twitter API to get the tweets during the same period and compare the sentiment analysis of the news articles with the sentiment analysis of the tweets to see if there's relationship between these two.

### Data

BBC News Summary: This dataset contains 417 text files of BBC from 2004 to 2005 and 5 summaries are provided for each article. The dataset is available on [Kaggle.](https://www.kaggle.com/pariza/bbc-news-summary#BBC%20News%20Summary.rar)

Tweets from 2004 to 2005: Twitter API will be used to request tweets which were posted during 2004 to 2005.

### Known Unknowns

Known: Required NLP part will be fulfilled as described in the domain section above but it will be supervised since the provided summaries will be included when building the model. Topic modeling will be performed to meet the requirement of using unsupervised learning. Hopefully I can gain some hidden insight of this dataset from the output of topic modeling.

Unknown: Twitter sets a limited amount of getting tweets per day and the tweets I need are the ones posted in 2004 and 2005, so further research will be needed to get the data I desire.
