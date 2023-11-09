# ARSG
This project implements ARSG(Attention based Recurrent Sequence Generator). 

The project is based on a notebook [NLP From Scratch: Translation with a Sequence to Sequence Network and Attention](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html). The notebook preprocesses a Franch-English translation dataset and builds and trains a content based ARSG to translate from French to English. I modify it to add essential features and solve exercises after the tutorial. 

I have added several features, including:
 - Train model with longer, more complex and more sentences.
 - Consider location(or position) information in attention mechanism.
 - Try with more layers, more hidden units. Compare the training time and results.
 - Replace the embeddings with pretrained word embeddings such as word2vec or GloVe

Features to be constructed include:
 - Build an automatic evaluation function, and evaluate the model's performance
 - Try another dataset to build an autoencoder.
 - Try another dataset to build a conversational model.
