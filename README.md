# Sentiment Analysis of Amazon Kindle Store Reviews

## Overview
This project predicts the sentiment (**positive** or **negative**) of Amazon Kindle Store reviews using **Gaussian Naive Bayes**.  

## Dataset Used
- **Source**: [Julian McAuley, UCSD](http://jmcauley.ucsd.edu/data/amazon/)  
- **Key Features**:
  - `reviewText`: Content of the review.  
  - `overall`: Product rating (used for sentiment labeling).  

## Technologies Used
- **Libraries**: `NLTK`, `pandas`, `scikit-learn`,`BeautifulSoup`.  
- **Techniques**:
  - Text preprocessing: lower casing, spacial character removal, urls removal, html tags removal, extra space removal, Stopword removal, tokenization, lemmatization.  
  - Vectorization: `CountVectorizer`, `TF-IDF Vectorizer`.
  - Model: `GaussianNB`.


