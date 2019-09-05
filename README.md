# Natural Language Processing

This repository contains a Python file with the Python code to do the differents Natural Language Processing.

We use the programming language Python.

Python libraries that we are using:
* pyLDAvis
* Gensim
* WordCloud
* Live Loss Plot
* TextBlob
* GraphViz
* Spacy
* NLTK
* stop-words
* matplotlib
* seaborn
* scikit-learn
* Keras

This repository has the following files:
  1. data/
  2. pictures/
  3. NLP_KC.ipynb
  4. README.md
 
I worked in Google Colaboratory because you need GPUs to process the text.

## 1. data/

This file contains the data of politicians tweets: Obama and Donald Trump.

  1. BarackObama.json
  2. dataset2.json
  3. train_sentiment_utf8.csv


## 2. pictures/

The file pictures/ contains the pictures to draw the mask of the word cloud.

The pictures in the pictures/ file are:
  1. 03-bannon-trump-split.w700.h700.jpg
  2. obama_mask1.png


## 3. NLP_KC.ipynb

This Python file is divided into three parts:
  1. Tweets sentiment Analysis
     > a. Implementation of a Sentiment Analysis model with a Classic Machine Learning algorithm.
    
     > b. Implementation of a Sentiment Analysis model with a Deep Learning architecture.
    
     > c. Results comparison
  2. Sentiment analysis of politicians tweets
  3. Tweet generation (we use Obama's tweets)