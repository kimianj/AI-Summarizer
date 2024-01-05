# AI-Summarizer
This project addresses the challenge of information overload in the digital age, where individuals are bombarded
with vast quantities of data but have limited time to process it. Specifically, we have built multiple different machine learning
models using TD-IDF, K-Means, and BERT, to efficiently and accurately generate summaries of news articles ranging
in topics from news to sports and entertainment. It is important to increase accessibility to news as the world increases
in connectivity through technology. Our results showed that the K-means algorithm had the highest performance for our
model as measured by ROUGE scores. While our summaries were effective at shortening the required reading length by a
user, future work may want to investigate the level of detail between NLP generated and human-generated summaries. We
implemented hyperparameter tunings, post processing, and unfreezing more layers in order to improve the accuracy and
performance of our model.

We used the CNN-DailyMail News Text Summarization data
set from Kaggle, which was released and updated in 2021.1
The data set contains around 289,000 news articles from CNN
and DailyMail and their summaries.
https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail/code

