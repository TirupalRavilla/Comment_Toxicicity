# Comment_Toxicicity
Classification of toxicity in civil comments

Baseline model:
A LSTM model trained on padded sequences of train texts processed using Keras tokenizer.

Model with Glove Embeddings:
A Stacked bidirectional LSTM network, with an additional Hidden layer with ReLu activation, trained on padded sequences train texts with Glove Word Embeddings.

To run the notebooks, change the path for train.csv, glove embeddings file, and test.csv in the code.
