# Recommendation-system-without-apache-spark

# Introduction
The Decimation has taken place. Thanos has snapped his finger and half the universe has been reduced to dust.
People think that it was done at random however, the real story is a bit different.Some weeks before the snap,
Thanos places the problem of world decimation in front me. He needs a model that can use the information about the scores that people have been getting in their academic career in order to decide who gets turned to dust. He has successfully gathered the data for most of his
target however, the avengers managed to delete records of certain planets and their people in order to hide them from Thanos.

# Aim
The aim here is to provide Thanos with a list of predicted scores for a few people he could not get the academic records for, thanks to the avengers stealing that data.

# Datasets 
- Train.data
- Test.data

### Train.data
Contains the train data. The format is

planet,person,score
0,786,5
0,3161,4
0,2058,4
0,1581,4
In this example the planet with id 0 had people with ids 786, 3161, 2058 and 1581.
Their scores are given as 5,4,4,4 respectively

### Test.data 

Contains the test data, this is the missing data that Thanos needs your help on. The format is

planet,person
0,786
0,3161
0,2058
0,1581

This is the same format as in the train.dat but the score is missing. The task is to predict this score.
