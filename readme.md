## My Approach

In this competition I used simple **Naive bayes** as base line model got F1 score around ~58 percent

Then i have improved the score by 1 pp applying cross validation.

I improved modelling by using **sklearn crf suite** and F1 score increased to ~75 and finally **optimized parameters** secured 6 position in-
-private leaderboard with score ~80

### Other Approaches which I had tried:

* TimeDistributed bidirectional LSTM 

* TimeDistributed bidirectional GRU (Due to lack of computational resources I was not able to run more epochs and also I faced difficulty 
in augmenting the dataset as it contains 30 million records)


