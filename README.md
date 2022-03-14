# AIMtask-
This task was about applying ML & DL model on analysing dialects of arabic tweets.we were handed the ids of users & suggested dialects but the text of the tweets would be called through an api.

Here is my approach:

1- Use the id column to send a post request to retrieve the text.

2- Merge the text column with dialects by the id column.

3- Remove the emojis, hashtags, mentions, hyperlinks from tweets so we can get the actual text.

4- Apply TF-IDF vectorizer on the data.

    5-a) Build a machine learning model. I choose LinearSVC after trying another ones.
    
    5-b) Build a machine learning model. I choose ADAM (optimizatied algorithm for stochastic gradient descent for neural networks)
    

I attached three files first for fetching data, second for preprocessing + ML model & third for preprocessing + DL
as there is a slight difference in preprocessing of ML & DL models.
