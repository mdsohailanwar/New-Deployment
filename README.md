# News-Classification-Deployment

##### With the existence of a number of sources on the internet generating immense amount of daily news, there is a necessity to classify the news articles to make the information available to users quickly and effectively. So the task of news classification starts by collecting real time news articles from news websites through web scraping and then automatically classifying it using various classification algorithms. Thus news classification is a way to identify topics of untracked news as well as make Individual suggestions based on the user’s prior interest.

##### We’ll use a dataset which was provided by the Board Infinity comprised of 2225 articles, each labeled under one of 5 categories: business, entertainment, politics, sport or tech. The dataset is broken into 1700 records for training and 426 for testing. The goal will be to build a system that can accurately classify previously unseen news articles into the right category. The model is evaluated using Accuracy as a metric.

##### I have done some machine learning models using NLP techniques such as countvectorizer, TF-IDF vectorizer, TF-IDF vectorizer pipline and Word Embedding Layers for Deep Learning

##### In above models, we have use algorithms such as Logistic Regression, Multinomial Naïve Bayes, Random Forest Classifier, XGBoost Classifier. Found that Logistic Regression gives best results among all others with 97.65% Accuracy. Further, I built a flask API and deployed the model in the Heroku environment.


##### Here is the link for Heroku cloud deployment of News Classification: https://newsclassificationexp.herokuapp.com/



![image](https://user-images.githubusercontent.com/79276064/119238518-5c9d4f80-bb60-11eb-888f-5b5b901779c5.png)




