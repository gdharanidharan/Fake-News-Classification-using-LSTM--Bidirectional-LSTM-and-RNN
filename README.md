Fake or Real!!!

Dataset: https://www.kaggle.com/c/fake-news/data#

![image](https://user-images.githubusercontent.com/61073862/193447233-332b6bb1-19e5-459b-aedc-77e069454785.png)

What does it mean by Fake News??
Many people have been using the term fake news for the last few years, but do they actually know what it looks like? The term has been used so amorphously that it begs a more direct examination. Sensationalist fake news is often used to generate clicks onto a webpage to improve ad revenue. It has also been used to influence public thought.

The concepts used to predict whether the news is fake or not:

### LONG SHORT- TERM MEMORY (LSTM)
LSTM is a recurrent neural network (RNN) architecture that REMEMBERS values over arbitrary intervals. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration. Relative insensitivity to gap length gives an advantage to LSTM over alternative RNNs, hidden Markov models and other sequence learning methods.

![image](https://user-images.githubusercontent.com/61073862/193447256-a9249c50-b8d1-4e66-aaa7-c1077c1670f9.png)


### Bi-directional LSTM

![image](https://user-images.githubusercontent.com/61073862/193447262-75fefda3-c9c4-451b-91df-a5e1470274b8.png)

Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems. In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence. This can provide additional context to the network and result in faster and even fuller learning on the problem.
