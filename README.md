## IS450 Student Project

### Introduction
Original project consists of three phases. This repo contains the second phase of the project. Summarization methods used are textrank provided by gensim as well as two other extractive summarization methods with manual implmentations using vector space models (bag of words models).


### Data
The input data is from phase 1 of the project which require topic modelling to extract aspects from each summary. The initial data is provided from this [link](https://www.kaggle.com/snap/amazon-fine-food-reviews "Kaggle Amazon Kernel"). 
Topic modelling was done using gensim implementation of LDA with topic number set at 4. The input data which is named *LDA.csv* contains the output of the topic modelling. Each record is one comment from the original corpus and each comment has features such as **category**, **topic**, **original comment**

*Input data available on the local repo

### Output Data
Output data is given in each sub directory.


### Future work
Evaluation of each summarization model. Possible use an ensemble of each method to produce better summaries. 


