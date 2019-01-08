Christmas Challenge

Recommender System


The Decimation has taken place. Thanos has snapped his finger and half the universe has been reduced to dust.
People think that it was done at random however, the real story is a bit different. 3 weeks before the snap,
Thanos places the problem of world decimation in front of students from Machine Learning 1 lab at the university
of Hildesheim. He needs a model that can use the information about the scores that people have been getting in their
academic career in order to decide who gets turned to dust. He has successfully gathered the data for most of his
target however, the avengers managed to delete records of certain planets and their people in order to hide them
from Thanos.

The aim here is to provide Thanos with a list of predicted scores for a few people he could not get the academic
records for, thanks to the avengers stealing that data.



Thanos has provided the following.


Four different files:
- Train.data
- Test.data
- submission.txt



== Train.data ==
Contains the train data. The format is

planet,person,score
0,786,5
0,3161,4
0,2058,4
0,1581,4

In this example the planet with id 0 had people with ids 786, 3161, 2058 and 1581.
Their scores are given as 5,4,4,4 respectively


== Test.data ==

Contains the test data, this is the missing data that Thanos needs your help on. The format is

planet,person
0,786
0,3161
0,2058
0,1581

This is the same format as in the train.dat but the score is missing.
The task is to predict this score.


== submission.txt ==

This is an example how the submission should look like.
Each row contains the prediction for the corresponding test instance.
The submission.txt predicts the global average rating for each person. 



Rules of the challenge:

Challenge will run from 25th Dec to 11th Jan
all submissions must be handed in by 11:59 PM on 11th Jan
the metric for comparison will be the RMSE
Lower the RMSE, the Better the model
Anything useful will be less than 1.0 RMSE and a good model 
will be below 0.9

This is a recommender system problem, read up on the literature.

The submission must be made on the test set that is provided.
you are going to provide the scores of the planet,people combinations
as given in the test file. 
Sample of the submission is shown in the submission.txt

The best score will get a 5% boost on the final score, the second place
will get a 2.5%

