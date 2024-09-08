# Emotion Detection – Artificial Neural Networks Performance Comparison

## Classifying emotions using GoEmotions Dataset

ANNs performance on GoEmotions:

○ LSTM - 62.29% (on Pos/Neg/Neutral)

○ Bilateral LSTM - 66.19% (on Pos/Neg/Neutral)

○ Pretrained BERT - 96.21% (on 28 different emotions)

## Notbooks:

Notebooks for IMDB:

https://drive.google.com/drive/folders/1-7guEDuPGgccpVdIxFzlkkqSlfvV-FjA?usp=sharing

Notebooks for GoEmotions:

https://drive.google.com/drive/folders/1dTE9zbd05k_ezkHI_mznggYQXQHUhN-U?usp=sharing

## Overall conclusions:

● In our process, we followed the evolution of Artificial Networks for NLP tasks.

● The theoretical advantages of the newer bi-directional transformer architectures over the sequential
processing of the LSTM network architectures were empirically established through a set of comparative
experiments.

● biLSTM showed somewhat better results compared to LSTM model. This is due to its ability to derive
bi-directional context (from sentence beginning to end, and from sentence end to beginning).

● Data size – we saw that LSTM and biLSTM require massive amount of training data to provide accurate
classification. BERT, on the other hand, achieved superior results with far less training data. This is probably
due to both factors – multi attention architecture as well as the use of pre-trained models for our experiments.

● There is a big variety of open source pre-trained models for various NLP tasks freely available online. One of
our key observations is how significant Transfer Learning is to the process: whether it is in the short training
time, or the small amount of data that is required to train a pre-trained model.

● We have managed to produce a model with slightly better classification accuracy: distilBERT + dense layer + tanh
activation layer showed 96.22% compared to our benchmark model (BERT + dense layer + sigmoid) that produced
96.20%
