# Disaster Tweets Classification

In this social media era, social media has become the most important medium through which information is getting conveyed. When a disaster occurs, it is important to know it immediately. Twitter is one platform which is being relied to provide authentic and genuine information. It is being monitored by Disaster teams as well as other agencies to keep informed on the disaster. There is an important point to be noted. The context. For example,

Keyboard warriors are on fire has a different meaning when compared to the building is on fire.

We leverage machine learning to classify if the tweets are informing disaster or not.

The metric that is being validated is F1 Score

Training Data: 7613 records with 5 columns (id, keyword, location, text and target)

Test Data: 3623 records with 4 columns (id, keyword, location, text)

BERT based models are used for classification. The accuracy of models are around 0.82 in the validation data. 
