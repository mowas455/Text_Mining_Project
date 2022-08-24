# Identification of Spoiler in IMDB movie review

### Abstract
---
This paper presents the NLP (Natural Language Processing) approach to detecting spoilers
in the IMDB review. Generally, these reviews reveal some information associated with the
plot of a movie. An automated approach, filtering out such spoilers, would be ideal as
manual labeling is impossible due to a large amount of content. To identify those reviews,
we propose supervised machine learning models. So, we explored Bi-LSTM, XGBoost, Naive
Bayes, and pre-trained GloVe to improve the accuracy in text classification. In addition to
this, we used the Bag Of Words (BOW), cosine similarity, and Term-Frequency and Inverse
Document Frequency (TF-IDF) method to process the text vectors. The results shown from
our models are satisfactory. Quantitative and qualitative results demonstrate the proposed
method substantially outperforms the baseline model.

### Project
---
- ['IMDB-NB & XGBoost .ipynb'](https://github.com/mowas455/Text_Mining_Project/blob/main/IMDB-NB%20%26%20XGBoost%20.ipynb) Implement the feature engineering and modelling of naive bayes, XGboost and sematic similarity method.
- ['IMDB-word2vec-Bi-lstm.ipynb'](https://github.com/mowas455/Text_Mining_Project/blob/main/imdb-review-4.ipynb) Implement the Pretrained Word2vec embedding with Bi-LSTM model.
- ['IMDB-GloVe-Random Forest.ipynb'](https://github.com/mowas455/Text_Mining_Project/blob/main/imdb-random-forest-glove.ipynb) Implement the  Pretrained Glove embedding to convert sentence to vectors and predicted by Random Forest method.
- ['IMDB-GloVe-Bi-LSTM.ipynb'](https://github.com/mowas455/Text_Mining_Project/blob/main/IMDB-GloVe-Bi-LSTM.ipynb) Implement the Pretrained Glove embedding with Bi-LSTM model.

### Datasets
---
- [imdb-spoiler-dataset](https://www.kaggle.com/datasets/rmisra/imdb-spoiler-dataset) Dataset obtained from kaggle by RISHABH MISRA

### Report
---
