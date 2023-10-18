# LSTM

Long Short Term Memory is a kind of recurrent neural network. In RNN output from the last step is fed as input in the current step. LSTM was designed by Hochreiter & Schmidhuber. It tackled the problem of long-term dependencies of RNN in which the RNN cannot predict the word stored in the long-term memory but can give more accurate predictions from the recent information. As the gap length increases RNN does not give an efficient performance. LSTM can by default retain the information for a long period of time. It is used for processing, predicting, and classifying on the basis of time-series data. 

To use an LSTM for next word prediction, we first need to train the model on a dataset of text. The dataset should be large enough to contain a variety of different word sequences, so that the model can learn the different patterns that can occur in language.

Once the model is trained, we can use it to predict the next word in a sentence by passing it the previous words in the sentence as input. The model will then output a probability distribution over all possible next words, and we can choose the word with the highest probability.
