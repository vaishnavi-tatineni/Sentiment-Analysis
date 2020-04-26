# Sentiment-Analysis
Sentiment analysis of IMDB dataset using hybrid deep neural network (CNN-BiLSTM).

## DATASET:  
Sentiment analysis was implemented on IMDB dataset. The dataset can be downloaded from https://www.kaggle.com/columbine/imdb-dataset-sentiment-analysis-in-csv-format.

## LIBRARIES USED:  
1.numpy  
2.pandas  
3.sklearn  
4.NLTK  
5.gensim  
6.matplotlib  
7.Keras  
8.Tensorflow  

## PREPROCESSING:  
There are different steps in preprocessing:  
1.Tokenization  
2.Stop Word Removal  
3.Lemmatization / Stemming  
4.Labelling  

## EMBEDDING:  
Once the text is preprocessed, Word2Vec algorithm is used for word embedding’s and it converts the word into a encoded vector which is further used for feature extraction.

## FEATURE EXTRACTION:  
We have proposed the traditional TFIDF algorithm in addition to Word2Vec embedding in order to extract the features of the word to create a weighted word vectors. 

## MODELS:  
1.Convolution Neural Network (CNN)  
2.Bi-directional Long Short Term Memory (Bi-LSTM)    

## IMPLEMENTATION:  
Sentiment analysis is implemented using Keras(Tensorflow as backend)
The Sentiment analysis.ipynb file is intended to use on google collab. You can run it offline using Jupiter Notebook.

## PERFORMANCE:
The accuracy of the training data is 84.11% and the test accuracy is 88%.  
