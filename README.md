# LSTM_Classifier_mnist_tensorflow
This project applies Long SHort term Memory networks to recognize handwritten digits from 0 to 9.
It basically classifies the images into 10 classes labelled from 0 to 9.
MNIST dataset has been used to train the coded LSTM model.Tensorflow's contrib module has been used implement LSTM model.
Each image has a dimension of 28x28. Instead of squashing this 2-D matrix into 1-D array of 784 pixels and feeding them directly to a Dense neural network.
I have considered them as 28 sequences (equivalent to 28 time-steps) of 28 pixels (equivalent to word) each.
LSTM models being made to process sequential data, can perform much better than simple Dense neural networks for sequences. 
