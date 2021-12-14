# TwitterNLU_NBA_MVP_Predictor
This project explores the impact of media influence on NBA MVP voting with a variety of machine learning algorithms.

First to [collect media sentiment](Scraping_Tweets_with_Twint.ipynb), I used the Twint library to scrape tweets from NBA media accounts that mentioned certain MVP candidates.

Next, Emotion and Sentiment values were [gathered](NLU_Analysis_of_Tweets.ipynb) for each tweet using two open source NLU models.

Using a combination of NBA statistics and NLU features, this project explored both [classification and regression tasks](MVP_Classification_and_Regression_Models.ipynb) for predicting NBA MVPs.

Data containing tweets, NLU data, and nba mvp statistics can be found in the [data](/data) folder.

To view a presentation of relevant results follow this link: https://docs.google.com/presentation/d/124jy-ge_U1KCY4hjtkkAGkcT8vhKSGaVU9AXFm6trqk/edit?usp=sharing
