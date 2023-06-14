# Twiter_disaster_detection_and_monitoring

The project was part of the kaggle competition assignment to predict the disaster or no disaster based on text language processing. 

The data consist of several column, including 
  keyword = consist of a single keyword
  location = city, state of tweet
  text = consist of all the tweets
  target = 0 for no disaster and 1 for disaster 


  <img width="544" alt="Screenshot 2023-06-14 at 12 04 10 PM" src="https://github.com/AnkitBaliyan1/NLP_Twiter_disaster_detection_and_monitoring/assets/86275544/a311bedc-38e9-4b92-a7d1-cc6ec35b5c82">


Model was build and trained on the dataset provided with over 7500 observations. This was than tested on over 2500 observations. 

Extensive data cleaning and pre-processing was performed including stop words removal, special character and numbers removal, lemmatization and stemming, etc. before model building and training. 

Before finalising the model, multiple models were tested. 

Models tested: 
  1. Logistic Regression,
  2. Decision Tree Classifier,
  3. Random Forest Classifier,
  4. Support Vector Machine from Naivee Bayes,
  5. MultinomialBL

Not only multiple models were tested, but multiple freature extraction and feature reduction techniques were also considere. 

Feature extraction techniques:
  1. CountVectorizer,
  2. TfidfVectorizer

Feature Reduction techniques:
  1. PCA or Principal component analysis,
  2. SVD or Singular Value Decomposition

The final model (Logistic Regression) able to achieve the f-score of over o.81 over validation dataset and over 0.79 over unknown dataset. 



  Classification Report over validation dataset:
  
<img width="540" alt="Screenshot 2023-06-14 at 12 00 18 PM" src="https://github.com/AnkitBaliyan1/NLP_Twiter_disaster_detection_and_monitoring/assets/86275544/0b722a07-b045-476c-9dcd-ba944bdb96cd">
