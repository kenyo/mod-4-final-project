# mod-4-final-project

By Lauren Cunningham and Kenny Oh

## Goal

To create a model that can rate the sentiment of a Tweet based on its content. The sentiment falls into one of the following three categories: positive, negative, and neutral. 

## Data Resource

The data was acquired from twitter and relates to tweets from the sxsw festival from both Google and Apple users.

## EDA

![plot_1](https://github.com/kenyo/mod-4-final-project/blob/master/images/sentiment_by_product.png)

![plot_2](https://github.com/kenyo/mod-4-final-project/blob/master/images/top_words_by_sentiment.png)

## Modeling

We created 3 different classification models: Logistic Regression, Naive Bayes, and Random Forest. Ramdom Forest gave us the best F1 score (0.8407). Logistic Regression was next best with and F1 of 0.8103. Naive Bayes was last with 0.8027. 

## Conclusion

As a result we could use our Random Forest model to predict unseen tweets.