**Sentiment Analysis on IMDB Movie Reviews**

This project demonstrates sentiment analysis on a dataset of 50,000 IMDB movie reviews using machine learning techniques. The goal of this project is to classify movie reviews as either positive or negative based on the text, achieving an accuracy of 89%.

**Introduction**

Sentiment analysis, also known as opinion mining, involves determining the emotional tone of a piece of text. In this project, we perform sentiment analysis on a dataset of movie reviews to classify them as either positive or negative.
The IMDB dataset consists of 50,000 movie reviews, which are evenly split between positive and negative reviews. The main goal is to preprocess the data, train a machine learning model, and evaluate its performance. The project achieved an accuracy of 89% on the test set, indicating a successful application of sentiment analysis to movie reviews.

**Dataset**

The dataset used in this project is the IMDB Movie Reviews dataset, which is publicly available and consists of 50,000 reviews. These reviews are pre-labeled as either positive or negative.

**Key features:**

Reviews: Text data containing movie reviews.
Labels: Binary classification labels indicating positive or negative sentiment (1 for positive, 0 for negative).
You can access the dataset directly from the IMDB website or use the Keras dataset API, which conveniently provides the IMDB dataset in a pre-processed format.


**Model Architecture**

This sentiment analysis model is built using a deep learning architecture with the following components:

Data Preprocessing: Tokenization and padding of the text data to create input sequences suitable for deep learning models.

Embedding Layer: An embedding layer to convert words into dense vectors of fixed size.

LSTM (Long Short-Term Memory): A type of recurrent neural network (RNN) used to capture sequential dependencies in the review text.

Dense Layer: A fully connected layer for classification.

Activation: A sigmoid activation function to output binary predictions.

Optimizer: Adam optimizer used for training.

**Results**

The model was trained on the IMDB dataset and achieved an accuracy of 89% on the test data, indicating that the sentiment analysis approach is effective.

_Accuracy:_

Training Accuracy: 90.3%

Test Accuracy: 89%


_Loss:_
Training Loss: 0.327

Test Loss: 0.351

The model shows promising results and could be further improved by tuning hyperparameters, exploring different architectures, or using pre-trained embeddings like GloVe.
