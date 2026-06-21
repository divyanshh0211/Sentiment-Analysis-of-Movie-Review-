# Sentiment Analysis on IMDB Movie Reviews

## Overview

This project focuses on binary sentiment classification of movie reviews using the IMDB Dataset containing 50,000 reviews. The objective is to classify reviews as Positive or Negative using Natural Language Processing (NLP), Machine Learning, and Deep Learning techniques.

The project starts with a TF-IDF + Logistic Regression baseline model and progresses to a PyTorch-based LSTM network for improved performance.



## Key Features

* Processed and analyzed 50,000 IMDB movie reviews
* Built an end-to-end NLP pipeline
* Implemented TF-IDF and Logistic Regression baseline model
* Developed a 2-Layer LSTM Neural Network using PyTorch
* Applied text preprocessing and feature engineering techniques
* Performed 5-Fold Cross Validation
* Evaluated models using Accuracy, Precision, Recall, and F1 Score



## Results

| Model                        | Accuracy |
| ---------------------------- | -------- |
| TF-IDF + Logistic Regression | 86.2%    |
| 2-Layer LSTM                 | 91.4%    |

### Final Performance

* Accuracy: 91.4%
* F1 Score: 0.913
* Precision: 0.912
* Recall: 0.914

The LSTM model achieved a 5.2% improvement over the baseline Logistic Regression model.



## Technologies Used

### Programming Language

* Python

### Libraries

* PyTorch
* Scikit-Learn
* Pandas
* NumPy
* NLTK
* Matplotlib
* Seaborn

### NLP Techniques

* Tokenization
* Stopword Removal
* Lemmatization
* TF-IDF Vectorization
* Sequence Encoding
* Text Normalization


## Dataset

Dataset: IMDB Movie Reviews Dataset

* Total Reviews: 50,000
* Binary Sentiment Classification
* Balanced Positive and Negative Samples

Note: The original dataset is not included in this repository due to GitHub file size limitations. The dataset can be downloaded from:

https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews


## Methodology

### Data Preprocessing

* Removed punctuation and special characters
* Converted text to lowercase
* Removed stopwords
* Applied lemmatization
* Tokenized review text

### Feature Engineering

* TF-IDF Vectorization
* Vocabulary Construction
* Sequence Encoding for LSTM Model

### Model Development

#### Baseline Model

* TF-IDF Vectorizer
* Logistic Regression

#### Deep Learning Model

* Embedding Layer
* Two LSTM Layers
* Fully Connected Layer
* Sigmoid Activation

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Cross Validation


## Visualizations

The notebook includes:

* Sentiment Distribution Analysis
* Word Frequency Analysis
* Confusion Matrix
* Training and Validation Performance
* Model Comparison
  

## Future Improvements

* BERT and RoBERTa-based models
* Hyperparameter Optimization
* Attention-Based Architectures
* Real-Time Sentiment Prediction
* Multi-Class Sentiment Classification


## Author

Divyansh Rathore

B.Tech Computer Science Engineering

MIT ADT University, Pune

Interests: Artificial Intelligence, Machine Learning, Data Science, Natural Language Processing
