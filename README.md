# YELP_NLP

The focus of this project was Unsupervised Learning (K-Means Clustering) and Natural Language Processing.
![](https://github.com/METIS-DATA-SCIENCE-PROJECTS/YELP_NLP/blob/main/Images/MLLifecycle.PNG)

**NLP Tools:**

- [spaCy](https://spacy.io/) - This library is far superior to NLTK. In fact, I think it makes NLTK look like a **toaster oven!** I utilized spaCy for tokenization and lemmatization! It is exceptionally fast (library is written in C) and produces fantastic results! 

- [NLTK](http://www.nltk.org/) - This is the traditional go to library for NLP. NLTK is also used almost exclusively in academic contexts. Let me stress, this does **NOT** mean that NLTK is the best NLP library out there. [Here](https://automatedinsights.com/blog/the-python-nlp-ccosystem-a-short-and-very-opinionated-guide) is a good article on NLTK vs. spaCy.

- [TF-IDF Vectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) - This is an excellent vectorizer to use in tandem with K-Means clustering. TF-IDF is often more appropriate than a regular count vectorizer. TF-IDF analysis represents a core component of this project!

- [Gensim](https://radimrehurek.com/gensim/) - A fantastic library to utilize for Latent Dirichlet Allocation - you can learn more about this [here](http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/). I am especially fond of [LDAMulticore](https://rare-technologies.com/multicore-lda-in-python-from-over-night-to-over-lunch/). LDA is a core component of this project!

**Clustering Tools:**

- [K-Means Clustering](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) - The most used unsupervised ML algorithm for clustering!

**Infrastructure Tools:**

- [MongoDB](https://www.mongodb.com/) - For database storage/access on an EC2 instance. I wrote my own custom wrapper around [PyMongo](https://api.mongodb.com/python/current/) - [`mongo.py`](Phases/Phase_1/mongo.py)




# Project Motivation
