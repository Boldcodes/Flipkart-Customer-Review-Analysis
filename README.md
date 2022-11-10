# Flipkart-Customer-Review-Analysis
This Project is all about sentiment analysis of FlipKart store customers review on Boat's Headphone from Flipkart

INTRODUCTION
Sentiment analysis is the systematic identification, extraction, quantification, and study of affective states and subjective data using natural language processing, text analysis, computational linguistics, and biometrics.

One of the most well-known Indian businesses is Flipkart. It is an online storefront that goes up against well-known online retailers like Amazon. The task of doing sentiment analysis on customer reviews of products sold on e-commerce platforms is one of the most well-known use cases of data science.
I'll be conducting a sentiment analysis of user reviews of Boat's Headphone from Flipkart, one of the company's goods.

The dataset used here for Flipkart reviews sentiment analysis was downloaded from Kaggle, here's the link:https://www.kaggle.com/datasets/kabirnagpal/flipkart-customer-review-and-rating?resource=download.

STEPS 
1. I imported the necessary libraries for the analysis and loaded the dataset using SQL through pyodbc library, because the dataset was downloaded and stored in database in my local machine.

2. Data Preprocessing and Exploratory Data analysis
The data contains no missing values.
The column containing reviews was cleaned before doing a sentiment analysis on the reviews

3. Sentiment Analysis
The ratings column contained the ratings given by customers on the product.
After exploring the ratings column, it was observed that 60% of reviewers gave the Flipkart products they purchased a 5 out of 5 star rating. Let's now examine the kind of reviews that people write. For this, I'll employ a word cloud to represent the words that appear most frequently in the reviews column:


4. By adding three columns to this dataset and labeling them Positive, Negative, and Neutral, I examined the feelings of the reviews on Flipkart by computing the sentiment scores of the reviews.
The majority of the reviews are Neutral. To draw a conclusion about customer reviews for Flipkart, I looked at the sum of the scores for the positive, negative, and neutral sentiments.

5. Conclusion
Therefore, the majority of reviewers are Neutral, and a minor percentage are Negative. Therefore, we may conclude that customers are happy with Flipkart's Products and Services


