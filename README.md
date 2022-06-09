# NLP-Python-project
Natural Language Processing project in Python
Our goal is to look at transcripts of various comedians and note their similarities and differences while delivering, the common words said by them, frequency of words used by them. 
Specifically, one can know if Ali Wong's comedy style is different than other comedians.

We have 5 stages of text processing -
1. Data Cleaning -
Getting the data - in this case, we'll be scraping data from a website
Cleaning the data - we will walk through popular text pre-processing techniques
Organizing the data - we will organize the cleaned data into a way that is easy to input into other algorithms

2.Exploratory data analysis
Most common words - find these and create word clouds
Size of vocabulary - look number of unique words and also how quickly someone speaks
Amount of profanity - most common terms

3.Sentiment Analysis
TextBlob Module: Linguistic researchers have labeled the sentiment of words based on their domain expertise. Sentiment of words can vary based on where it is in a sentence. The TextBlob module allows us to take advantage of these labels.
Sentiment Labels: Each word in a corpus is labeled in terms of polarity and subjectivity (there are more labels as well, but we're going to ignore them for now). A corpus' sentiment is the average of these.
Polarity: How positive or negative a word is. -1 is very negative. +1 is very positive.
Subjectivity: How subjective, or opinionated a word is. 0 is fact. +1 is very much an opinion.

4.Topic Modelling
We will be covering the steps on how to do Latent Dirichlet Allocation (LDA), which is one of many topic modeling techniques. It was specifically designed for text data.

5.Text Generation
Markov chains can be used for very basic text generation. Think about every word in a corpus as a state. We can make a simple assumption that the next word is only dependent on the previous word - which is the basic assumption of a Markov chain.
