# LSTM-PyTorch

This self-explanatory notebook explains the steps to be performed when working with variable sized sequences in PyTorch.

It is commonly known that to properly train a machine/deep learning model, one must input a batch of input samples in order to get a better gradient estimation. Working with batches composed of samples that have different lengths can be tricky, but it isn't if you know a few PyTorch functions. In this notebook, an LSTM model is created to perform a classification task (similar to sentiment analysis from texts, in the sense of multiple inputs-one output). The samples that we are going to classify are drawings extracted from the Google QuickDraw dataset, which contains labeled drawings of daily objects.
