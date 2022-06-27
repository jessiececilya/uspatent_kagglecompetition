
**US PATENT PHRASE TO PHRASE MATCHING**

Kaggle- https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching

**Input**
The input dataset consists of US patent information. It has pair of phrases (an anchor and a target phrase) and the problem statement is to rate how similar they are on an output scale from 0 (not at all similar) to 1 (identical in meaning). 

**Goal**
To build a model to match phrases in order to extract contextual information, thereby helping the patent community connect the dots between millions of patent documents

I evaluated the output with mean square error and mean absolute error using the following  three models 
1) Sentence transformer PatentSBERTA and XGB algorithm
2) Sentence transformer Allmini and XGB algorithm
3) Glove word embeddings and LSTM algorithm 

**Result**
Model 1 which uses PatentSBERTA and XGB algorithm on hyper parameter tuning and feature engineering has shown highest accuracy of 94.97% compared to other two models