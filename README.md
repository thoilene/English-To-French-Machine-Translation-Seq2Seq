# English To French Machine Translation with Seq2Seq ML model

English To French Machine Translation with Seq2seq ML model

## Introduction

This project consists to create a model for machine translation english to french on a dataset available on kaggle [English to french translation](https://www.kaggle.com/code/harishreddy18/english-to-french-translation/data). The dataset contains sentences in english and the corresponding traduction in french. 137860 samples are contained in the dataset.

The Seq2Seq (sequence to sequence) with RNN is used for this task as an improvement for the standard word2word architecture.   

## Predictive models

The RNN architecture choosen for the model is the sequence to sequence architecture

![Seq2seq](/data/RNN_seq2seq.jpg)


### Seq2seq LSTM Neural Network

![Seq2seq Model](/data/seq2seq_model.JPG)
![Seq2seq Model 2](/data/seq2seq_model_2.JPG)


## Results

| dataset      | accuracy(Seq2Seq LSTM)| 
| -------------| ----------------------|
| train        | 99.23%                |
| validation   | 99.02%                |


## Conclusion

Sequence to sequence archtecture with LSTM is the right choice for the current dataset. 99% accuracy is achieved with only 50 epochs and no model tuning. It is possible to achieve 100% accuracy, highly stable and quite perfect amodel.


