# YELP_NLP

The focus of this project was Sentiment Analysis using Wordcloud and Natural Language Processing with Supervised Learning Models.
![](https://github.com/METIS-DATA-SCIENCE-PROJECTS/YELP_NLP/blob/main/Images/MLLifecycle.PNG)

**NLP Tools:**

- [NLTK](http://www.nltk.org/) - This is the traditional go to library for NLP. NLTK is also used almost exclusively in academic contexts. Let me stress, this does **NOT** mean that NLTK is the best NLP library out there. [Here](https://automatedinsights.com/blog/the-python-nlp-ccosystem-a-short-and-very-opinionated-guide) is a good article on NLTK vs. spaCy.

- [TF-IDF Vectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) - This is an excellent vectorizer to use in tandem with K-Means clustering. TF-IDF is often more appropriate than a regular count vectorizer. TF-IDF analysis represents a core component of this project!
- [CountVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html ) - implements both tokenization and occurrence counting in a single class.


**Infrastructure Tools:**

- [MongoDB](https://www.mongodb.com/) - For database storage/access on an EC2 instance. I wrote my own custom wrapper around [PyMongo](https://api.mongodb.com/python/current/) - [`mongo.py`](Phases/Phase_1/mongo.py)




# Project Motivation
