# Reuters-newswire-classification_RNN


Dataset: from keras
This is a dataset of 11,228 newswires from Reuters, labeled over 46 topics.
Each newswire is encoded as a list of word indexes (integers). For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.
Description:
Used sequential model using different layers to compare the accuracy and performance.
Used simple RNN model, simple RNN with LSTM,conv1D and conv1D with LSTM .
Result:
Model showed best performance when adding a middle layer of LSTM to simple RNN and conv1D.



