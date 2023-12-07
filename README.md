# Congressional-Tweet-Prediction
## Description
Working with a Congressional Twitter Dataset. The dataset is a collection of tweets posted by Congressional politicians on Twitter [excluding tweets with no hashtags.].

The training dataset includes tweets posted, and a few features associated with tweets including the partisanship information of the politician who posted the tweet. The test dataset has the same features excluding the partisanship id [for convenience, the party classification has been set to 'D' in the test dataset].

The task will be to correctly predict the partisanship of the politician who posted the tweet(s) by analyzing tweet-specific information.

## Dataset Description
Files
congressional_tweet_training_data.csv - the training set
congressional_tweet_test_data.csv - the test set

## Descriptive information about the features included in the dataset:

Id : id number associated with the tweet_
favorite _ count : number of times the tweet was favorited_
full _ text : full text of the tweet_
hashtags : list of hashtags included in the tweet_
retweet _ count : number of times the tweet has been retweeted_
year : year of the tweet_
party : partisanship of the owner of the tweet [D = 'Democrat', R = 'Republican']_

Evaluation
Will be evaluated based on the '***accuracy***' of the prediction. For the definition of accuracy, please check: https://developers.google.com/machine-learning/crash-course/classification/accuracy



