# Classification-Model-Project-
In this project, we trained multiple classification models to predict if tweets came from the democratic or republican platform. We then deployed this model onto the twitters of senators and observed the accuracy.


Main Results from this project. 
1. Found that BERT as a classificaiton model was able to get up to 93% accuracy using a 70-30 split of the training and test set.
2. Significant relationship between senator accuracy rate and number of followers, margin of victory, years in office, and average number of tweets per week. 



Appendix for Files
platform_tweets.csv - collection of tweets from @Thedemocracts, @harrisonjaime, @GOP, @GOPchairwoman

tweetcollection_v4.csv - collection of tweets from every senator from the start of the 117th congress

Sen_rate_2.csv - Accuracy rates found for senators from BERT model

Govtrack_final.csv - The accuracy rate from the Gov Track ideology rankings for the 116th congress.

Model_final.csv - This file gives the senator ranks based on most republican to least republican. 

