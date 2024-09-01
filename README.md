# Mental-Disorder-Detection

> A binary and multiclass classification model using Traditonal Machine Learning and Deep Learning. 


## Table of Contents
* [Technologies Used](#Python, Tensorflow, Pytorch, Neural Networks, Machine Learning)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build an AI model which can accurately detect mental disorders in tweets posted by user. Mental Disorder is a type of disease that can be deadly if not detected early. It accounts for 75% of deaths. A solution that can evaluate mental disorder mentioned in DSM-5 to reduce a lot of manual effort needed in diagnosis.
- The dataset consists two stages of data:
    -First stage includes binary class classication to identify Diagnosed and Control Group.
    -Second stage includes multi-class classification of mental disorder in diagnosed group among nine categories of mental disorder includes ADHD, ANX, AUTS, BIPO, DEPR, EAT, OCD, SCHIZO, PTSD.

## Feature Engineering
- Emoji is included in context to identify symptoms of mental disorder.
- N-Grams- Unigram (U), Bigram (B), Trigram (T) and Unigram-Bigram-Trigram (UBT) is used to extract features from mental disorder dataset.
- High Dimensional Word Embeddings- Word2Vec (300-D), GloVe-(300-D), FASTTEXT (300-D), ELMo (1024-D) and BERT (768-D) is used to extract features from mental disorder dataset.

## Data Balancing Strategies
- Class weights for minority and majority class.
- Generate synthetic data using GPT-4o and GPT-4o-mini using few shot prompting.

## Machine Learning
- Logistic Regression
- Random Forest
- XGBOOST
- Decision Trees
- SVM-Kernel(Radial, Poly, Linear)

## Deep Learning
- LSTM
- CNN-LSTM
- HAN
- GAN-BERT
- BERT
- MentalBERT

## Performance Measures
- Precision
- Recall
- F1 Score
- Accuracy
- AUC
