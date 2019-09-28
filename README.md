# SarcasmDetection
A DNN-based model sarcasm detection in product reviews

The aim of this study is to develop a DNN-based model of sarcasm detection in product reviews based on sentiment value of each sentences (Drover 2015). As dataset, 'Sarcasm Corpus' (a collection of Amazon product reviews) was used. The dataset includes 437 sarcastic reviews and 817 non-sarcastic product reviews.

Text normalization and sarcasm score calculation of each sentence in reviews were done in RStudio.

As input, sentiment score per sentence of reviews were used for 
      a. CNN,
      b. LSTM,
      c. BiLSTM,
      d. CNN + BiLSTM

neural networks.
The highest accuracy in the validation dataset was achieved with BiLSTM model: 71%

REFERENCES
Drover, Dylan. 2015. Sarcasm Detection in Product Reviews using Sentence Scale Sentiment Change with Recurrent Neural Networks. Manuscript. Stanford University.
Filatova, E. 2012. Irony and Sarcasm: Corpus Generation and Analysis Using Crowd-sourcing. In Proceedings of Eighth International Conference on Language Resources and Evaluation, (pp. 392-398).
