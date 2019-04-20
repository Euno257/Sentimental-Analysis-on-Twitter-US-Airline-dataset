# Sentimental-Analysis-on-Twitter-US-Airline-dataset
As we can see, the accuracy of classifier is about 86%, this result depends on the few numbers of tweets used for the training. I used only 2000 tweets because the positive tweets, for this dataset are only about 2400. The numbers of negative tweets are higher but I can’t use all of those tweets. Is necessary train the classifier with the same number of positive and negative tweets to not introduce a bias.

The last step of this work is use the negative tweets to train a classifier for the reason of the negative tweets. The steps to define the classifier are the same of the first classifier, but now the subset, is only the negative tweets.

In this work I try to classify only the first two cause of negative tweets because the others don’t have enough amount of data. All the others tweets are classified as others.

For this classifier, the accuracy reached is 69%, not so good. But the number of tweets used is only 1000 and 400 to verify the classifier.

#Conclusion
The first classifier, with accuracy of 86% is acceptable because the human accuracy is about 80%. But the accuracy of the second is not acceptable because is too low.

If we consider the combined accuracy (classification between negative and positive and on the negative tweets the clssification on the reasons of negative tweets) it goes down to 59%.

The principal reason of these results is because the dataset has few positive tweets and few tweets for each cause of bad flight.
