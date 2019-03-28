## Innoplexus Hackathon

In this project I am dealing with the medical dataset. I have given a challenge to recognize medical entities in the dataset and here been coded with BIO encoding.


### Github Link

https://github.com/karthiktsaliki/Innoplexus_NLP_Hackathon

### Libraries used

* Numpy: Numpy is free and open-source Python library used for scientific computing and technical computing.

* pandas: Pandas is a software library written for the Python programming language for data manipulation and analysis.

* sklearn: Machine learning library for the Python programming language. It features for classification and regression.

* tensorflow: A library mostly used for training deep learning models.


### Motivation

Entity recognition helps in automating by recognising custom entities without any manual intervention. It can improve the efficiency of throughput time.

### Datasets

Train and test data where each record comprise the label in BIO encoding. Columns Sent id and Doc Id correspond to which sentence or document this word belong to.


### Approach

In this competition I used simple **Naive bayes** as base line model got F1 score around ~58 percent

Then i have improved the score by 1 pp applying cross validation.

I improved modelling by using **sklearn crf suite** and F1 score increased to ~75 and finally **optimized parameters** secured 6 position in-
-private leaderboard with score ~80

### Other Approaches which I had tried:

* TimeDistributed bidirectional LSTM 

* TimeDistributed bidirectional GRU (Due to lack of computational resources I was not able to run more epochs and also I faced difficulty 
in augmenting the dataset as it contains 30 million records)

### Results

I acheived a F1 score ~80 and secured 7th rank in final private leaderboard.


