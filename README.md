# Chinese word segmentation


Word segmentation is a popular topic in machine learning in China. In Chinese words are not seperated by spaces and word detection inside sentences presents an issue. 

A good review of existing approaches and dataset is given in https://chinesenlp.xyz/docs/word_segmentation.html

Another source of previously applied models is https://paperswithcode.com/task/chinese-word-segmentation

In order to train our own model we use the data presented in https://github.com/hankcs/multi-criteria-cws repository. The following datasets can be downloaded:

![image](https://camo.githubusercontent.com/3bc414c4846f0d6127c2bdbfa0b12d3a1d59dd9fc583820436e2ad885d943366/687474703a2f2f7778332e73696e61696d672e636e2f6c617267652f303036466d6a6d636c7931666d366a74686133746d6a33313872306c343078392e6a7067)

We compare three approaches:

1. Bi-LSTM
2. BERT for Token Classification
3. Bi-LSTM BERT CRF model

The last model has been shown to deliver the best results in CWS and our test support this conclusion.


