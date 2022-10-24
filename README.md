# English To French Machine Translation with Seq2Seq ML model

English To French Machine Translation with Seq2seq ML model

## Introduction

This project consists to create a model for machine translation english to french on a dataset available on kaggle [English to french translation](https://www.kaggle.com/code/harishreddy18/english-to-french-translation/data). The dataset contains sentences in english and the corresponding traduction in french. 137860 samples are contained in the dataset.

The Seq2Seq (sequence to sequence) with RNN is used for this task as an improvement for the standard word2word architecture.   

## Predictive models

The RNN architecture choosen for the model is the sequence to sequence architecture

![Many-to-One](/data/many-to-one.jpg)


### Single LSTM Neural Network

![Single Model Image 1](/data/tweets_single_1.JPG)
![Single Model Image 2](/data/tweets_single_2.JPG)

### Bidirectional LSTM Neural Network

![Bidirect Model Image 1](/data/tweets_bidirect_1.JPG)
![Bidirect Model Image 2](/data/tweets_bidirect_2.JPG)

## Results

| dataset      | accuracy(single LSTM) | accuracy(bidirectional LSTM) |
| -------------| ----------------------|------------------------------|
| train        | 77.68%                |78.28%                        |
| validation   | 76.55%                |76.54%                        |
| test         | 76.30%                |76.21%                        |

## Conclusion

The single LSTM neural network works slightly better than the bidirectional LSTM NN. The final model (single LSTM) generalizes good as the accuracy on train set is around 77.7% and the accurace on test set is around 76.3%. There is no overfitting. However this score is not very high. An improvement could be achieved using attention model.


