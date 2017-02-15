# topic-summarization

**Objective**: Summarize tweets by topics.

This Repository contains piece of the project which can find tweets semantically and contextually similar to each other.
Over 100,000 tweets have been modeled using **Doc2Vec** and **LDA** for a comparitive study. And, **Doc2Vec** wins.

Goto [model_usage.ipynb](https://github.com/adrsh18/topic-summarization/blob/master/model_usage.ipynb) to get the trained Doc2Vec model.

Goto [tweet_topics.ipynb](https://github.com/adrsh18/topic-summarization/blob/master/tweet_topics.ipynb) to see how the model was built.

**Other Files**

data-crawler.py - Crawl tweets for #christmas

process.py - Extract relevant fields from tweets

analyze.py - Starter code

Download processed 100,000 tweets from here: https://drive.google.com/open?id=0BzN3cL-RAt8TQ09pbnhTQ2FQeU0

Summary of Hashtag Counts

![alt tag](https://raw.githubusercontent.com/adrsh18/topic-summarization/master/hashtag_counts.png)

## Status

Run tweet_topic.ipynb

Doc2vec and LDA Models can be built using this code. LDA can be used directly for further tasks and Doc2Vec returns tweets as vectors. These vectors can be used with whatever sklearn models for clustering, SVD etc.,

Models once built using gensim can be saved and loaded. Hence, you don't have to train again.

For accurate results, train for more number of epochs.

Saved models can be found here: https://drive.google.com/open?id=0BzN3cL-RAt8TWF9ERnEwOFp2bDQ

Load them up and have a go.
