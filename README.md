# mental-health-prediction
# Mental Health Prediction using RNN

This project predicts mental health status from user text using NLP and Deep Learning techniques.

## Project Overview

The model processes text data, cleans it using NLP preprocessing techniques, converts it into numerical vectors using TF-IDF, and predicts mental health status using a Simple RNN model.

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* NLTK
* Scikit-learn

## NLP Preprocessing Steps

* Convert text to lowercase
* Remove special characters
* Remove stopwords
* Lemmatization using WordNetLemmatizer

## Feature Extraction

TF-IDF Vectorizer is used to convert cleaned text into numerical feature vectors.

## Why RNN?

RNN (Recurrent Neural Network) is commonly used for sequential and text-based data because it can learn patterns from word sequences and contextual relationships in text.

Even though TF-IDF creates fixed numerical vectors, the SimpleRNN layer was used to experiment with deep learning approaches for text classification and understand how neural networks process textual patterns.

## Model Architecture

* SimpleRNN Layer

  * Units: 128
  * Activation: ReLU
* Dense Output Layer

  * Softmax Activation

## Training Details

* Loss Function: Categorical Crossentropy
* Optimizer: Adam
* Epochs: 10
* Batch Size: 32

## Prediction

The model accepts user input text and predicts the corresponding mental health status.

## Future Improvements

* Replace TF-IDF with Word Embeddings
* Use LSTM or GRU for better sequence learning
* Improve dataset size and balancing
* Deploy as a web application

## Conclusion

This project demonstrates how NLP and Deep Learning can be combined to build a mental health text classification system.
