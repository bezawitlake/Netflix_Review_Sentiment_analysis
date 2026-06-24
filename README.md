# Netflix Review Sentiment Analysis Using Classical Machine Learning, Deep Learning, and Transformer Models

## Project Overview

Understanding customer sentiment is essential for streaming platforms seeking to improve user experience, customer retention, and product quality. This project develops a complete Natural Language Processing (NLP) pipeline to analyze Netflix user reviews and classify customer sentiment.

The project compares multiple text representation techniques and machine learning approaches, ranging from traditional NLP methods to deep learning architectures and transformer-based language models. The objective is to evaluate how different approaches perform in sentiment classification while uncovering customer opinions expressed in review data.

---

## Business Problem

Netflix receives large volumes of customer reviews containing valuable feedback about content quality, application performance, subscription pricing, and user experience.

Manually analyzing thousands of reviews is time-consuming and inefficient. Automated sentiment analysis enables organizations to:

* Monitor customer satisfaction
* Detect emerging issues
* Analyze customer feedback at scale
* Support data-driven product improvement decisions

This project builds predictive models capable of automatically classifying customer sentiment from textual reviews.

---

## Dataset

The dataset consists of customer reviews collected from Netflix users.

### Features

* Review Content
* Rating Information
* User Metadata

### Target Variable

Sentiment Categories:

* Positive
* Neutral
* Negative

Sentiment labels were generated using VADER sentiment scoring.

---

## NLP Pipeline

### Text Preprocessing

The following preprocessing techniques were applied:

* Lowercasing
* HTML removal
* Punctuation removal
* Number removal
* Emoji removal
* Tokenization
* Stopword removal
* Stemming
* Lemmatization

### Exploratory Analysis

Text exploration included:

* Sentiment distribution analysis
* Word frequency analysis
* Word cloud visualization

---

## Feature Engineering

Several text representation techniques were explored:

### Traditional NLP

* Bag of Words (CountVectorizer)
* TF-IDF

### Word Embeddings

* CBOW Word2Vec
* Skip-Gram Word2Vec

These techniques transformed unstructured text into machine-learning-ready numerical features.

---

## Machine Learning Models

### Traditional Machine Learning

* Support Vector Machine (SVM)
* Random Forest Classifier

### Deep Learning

* Simple Recurrent Neural Network (RNN)
* Bidirectional Long Short-Term Memory (Bi-LSTM)

### Transformer-Based NLP

* BERT (Bidirectional Encoder Representations from Transformers)

This progression enables comparison between classical machine learning, neural networks, and modern transformer architectures.

---

## Key Contributions

* Built an end-to-end NLP workflow from raw text preprocessing to advanced sentiment classification.
* Compared multiple feature engineering strategies including TF-IDF and Word2Vec embeddings.
* Implemented and evaluated traditional machine learning algorithms and deep learning architectures.
* Fine-tuned a pre-trained BERT transformer model for sentiment classification.
* Demonstrated practical application of modern NLP techniques for customer feedback analytics.

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TensorFlow / Keras
* Hugging Face Transformers
* Matplotlib
* Seaborn
* WordCloud

---

## Future Improvements

* Hyperparameter optimization
* Explainable NLP using SHAP
* Aspect-based sentiment analysis
* Topic modeling
* Deployment as a real-time sentiment monitoring dashboard
