# Sentiment-Analysis-of-movie-reviews
Analysis of the sentiments of movie reviews using lstm and convolutions on the imdb dataset

-------------------------------------------
### Dataset:
Load the imdb dataset from keras datsets using the library keras.datasets.imdb and load them as (X_train, y_train), (X_test, y_test)

--------------------------------------------
Using an embedding layer we create a vector embedding of the sequences (reviews) and then feed it to a convolutional1D layer followed by max pooling and then to an LSTM layer to keep better track of the history and neighbourhood. The output is classified as 0 or 1 i.e bad or good

----------------------------------------------
### To run
execute the file LSTM-SentimentDetection.ipynb