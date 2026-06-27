# Amazon Book Reviews — Text Mining & NLP

End-to-end Natural Language Processing analysis of 50,000 Amazon book reviews, built in R.
The project explores customer sentiment, hidden topics, and semantic relationships between
words using a full text-mining pipeline.

**[📊 View the full interactive report](https://mkaszycki.github.io/amazon-reviews-text-mining/Raport_Amazon_Text_Mining.html)**

## Overview

The goal of the project was to turn unstructured review text into structured insight -
identifying what readers care about, how language differs between positive and negative
reviews, and which themes dominate the corpus.

## Methods

- **Text preprocessing** - corpus cleaning, stopword removal, lemmatization, tokenization
- **Frequency analysis** - most common words, sentiment-split frequencies, trends over time
- **Sentiment analysis** - Bing and NRC lexicons; correlation between sentiment and star ratings
- **TF-IDF & representations** - term weighting and binary document-term matrices
- **Word associations & bigram networks** - mapping contextual relationships between words
- **Topic modeling (LDA)** - unsupervised discovery of latent themes across reviews
- **Hierarchical clustering** - grouping key terms by TF-IDF distance
- **Word embeddings (Word2Vec, Skip-Gram)** - 50-dimensional dense vectors capturing
  semantic similarity between words

## Tech Stack

R, tidytext, tm, topicmodels, word2vec, textstem, ggplot2, wordcloud, igraph

## Data

Sample of 50,000 book reviews from the Amazon Books Reviews dataset.

## Files

- `Raport_Amazon_Text_Mining.Rmd` — source code (R Markdown)
- `Raport_Amazon_Text_Mining.html` — rendered report with all visualizations
