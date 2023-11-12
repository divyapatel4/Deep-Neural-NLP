# Deep Neural NLP Course

Welcome to the repository for the Deep Neural NLP Course, instructed by Prof. Sourish Dasgupta. This repository contains all the assignments and related files for the course.

## Assignments

### Assignment 1: Word2Vec

The first assignment focuses on implementing the Word2Vec model. The notebook for this assignment is hosted on Kaggle and can be accessed [here](https://www.kaggle.com/code/divyapatel4/word2vec). The model was trained using a P100 GPU provided by Kaggle. 

### Assignment 2: Transformer from Scratch

The second assignment involves implementing and training a Transformer model from scratch. There are two notebooks associated with this assignment:

1. **Notebook 1**: This notebook trains a Transformer model on a small dataset consisting of 135,842 pairs of English and French sentences. The training was performed on 2 T4 GPUs using PyTorch. The length of sentences in this dataset was smaller compared to the second dataset training given below and hence gave good results withing short training time. You can access the notebook [Click here](https://www.kaggle.com/divyapatel4/transformer-implementation-training).

2. **Notebook 2**: This notebook trains a Transformer model on a 1% sample of the [English-French Translation Dataset](https://www.kaggle.com/datasets/dhruvildave/en-fr-translation-dataset/versions/2). This dataset contains 22.5 million translations of English and French sentences. Despite the sentences in this dataset being quite long and requiring more time for proper training, the results are quite impressive using just 1% of the dataset. You can access the notebook [Click here](https://www.kaggle.com/code/divyapatel4/transformer-implementation-training-on-t4x2).
