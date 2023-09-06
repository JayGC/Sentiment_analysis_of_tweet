# Sentiment_analysis_of_tweet

## Overview
Sentiment analysis is a crucial task in natural language processing, allowing us to gauge the sentiment or emotional tone expressed in text data. In this project, we leverage the power of BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art transformer model, for sentiment analysis on a substantial Twitter dataset. The dataset comprises approximately 1,600,000 tweets, but for computational efficiency, we randomly selected and analyzed 100,000 tweets.

## Description
### Data Preprocessing
To ensure the success of our sentiment analysis model, we invested considerable effort in data preprocessing. This phase involved cleaning and optimizing the tweet data. We addressed various challenges such as removing special characters, handling emojis, and normalizing text. These steps were essential to prepare the data and ensure that the features extracted for sentiment analysis were of high quality and conformed to the input requirements of the pretrained BERT model.

### Model Training
Our model training process was designed to maximize performance and efficiency. We adopted the AdamW optimizer, a popular choice for training deep neural networks. Additionally, we implemented a linear warm-up learning rate scheduler, a technique that proved effective in facilitating weight updates and promoting stable convergence. These optimizations collectively improved the performance of our sentiment analysis model.

### Performance Metric
To assess the effectiveness of our sentiment analysis model, we employed the Mathews correlation coefficient (MCC) as our primary performance metric. The MCC is a reliable metric for evaluating the performance of binary classification models, especially in scenarios where class distribution is imbalanced. The MCC score achieved by our model is an impressive 0.71, indicating its ability to effectively discern sentiment in the analyzed tweets.

## Dataset
The dataset used in this project is publicly available on Kaggle, a popular platform for data science and machine learning enthusiasts. You can access the dataset at the following link: [Twitter Sentiment Analysis Dataset](https://www.kaggle.com/code/arunrk7/nlp-beginner-text-classification-using-lstm).





