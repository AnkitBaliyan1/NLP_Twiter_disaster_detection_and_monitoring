# Twiter_disaster_detection_and_monitoring

The project was part of the kaggle competition assignment to predict the disaster or no disaster based on text language processing. 

The data consist of several column, including 
  keyword = consist of a single keyword
  location = city, state of tweet
  text = consist of all the tweets
  target = 0 for no disaster and 1 for disaster 

Model was build and trained on the dataset provided with over 7500 observations. This was than tested on over 2500 observations. 

Before finalising the model, multiple models were tested. 

Models tested: 
  1. Logistic Regression
  2. Decision Tree Classifier
  3. Random Forest Classifier
  4. Support Vector Machine from Naivee Bayes
  5. MultinomialBL

The final model (Logistic Regression) able to achieve the f-score of over 0.79.
