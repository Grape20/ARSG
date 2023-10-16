# ARSG
This project implements ARSG(Attention based Recurrent Sequence Generator). 

The project is based on a notebook [NLP From Scratch: Translation with a Sequence to Sequence Network and Attention](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html). The notebook preprocesses a Franch-English translation dataset and builds and trains a content based ARSG to translate from French to English. I modify it to add essential features and solve exercises after the tutorial. 

I have added several features, including: 

Features to be constructed include: 
 - Train model with long and complex sentences 
 - an evaluation function, evaluating the model's performance 
 - Consider location information in attention mechanism. 
 - Try with more layers, more hidden units, and more sentences. Compare the training time and results.
 - Replace the embeddings with pretrained word embeddings such as word2vec or GloVe
 - try to build an autoencoder 
 - a conversational model
