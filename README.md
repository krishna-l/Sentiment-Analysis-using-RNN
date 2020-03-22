# Sentiment-Analysis-using-RNN
Since we are using a time series data we are going to implement sentiment analysis using Recurrent Neural Network.
In this we are going to use IMDb dataset to perform sentiment analysis on the movie reviews and predict the likelihood of the user liking or disliking the movie. Since RNN is highly resource intensive we are limiting the unique words used in reviews to 50000 and use only the first 150 words of a review. Even with all this limitations placed each epoch was of 258 sec ~ 5 mins. We will be having a LSTM of 128 neurons and train the model with 15 epochs.
Train accuracy: ~83.5% and test accuracy: ~83%
