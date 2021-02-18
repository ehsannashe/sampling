# sampling
Some of methods for sampling from a huge dataset.

An ATM transactions dataset with 1,250,000 records. It has 33 features with both discrete and categorical type.

The data is available at the following address: https://www.kaggle.com/sparnord/danish-atm-transactions

The problem is: a 10% sampling so that the distribution and pattern in the data is maintained, and then reduce the number of samples so that the marginal error does not exceed 5%.

There is 4 methods:

1-Stratified sampling.

2-Mini Batch k-means.

3-Genetic algorithm.

4-Mini Batch k-means with intersection approach.


Items 1 and 4 are powerful methods but are not suitable for our case study.

For our case study, the best methods are items 2 and 3.

Execution time of items 1 and 3 is long, but the other two methods are relatively fast.

The item 3 offers us many options to achieve the desired sampling.

