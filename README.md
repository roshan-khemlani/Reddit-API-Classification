# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification

#### Problem Statement

To classify Reddit posts from 2 different Subreddits, Personal Finance and Investing. We will be using Natural Language Processing (NLP) and Classification modelling, to
predict which subreddit a given post belongs to.<br>
The model should provide researchers an understanding of how the average retail investors feel towards to allocating a certain portion of their income for investments.
Researchers can work with financial consultants to identify which products/instruments are more marketable and strive to focus on that product during their sales pitch.

#### Description

1. Using Reddit's API, you'll collect posts from two subreddits of your choosing.
2. You'll then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.

#### Data Collection

Data was collected from the below subreddits API
[`/r/investing`](https://www.reddit.com/r/investing)
[`/r/personalfinance`](https://www.reddit.com/r/personalfinance)
A total of 1742 rows was collected
- Investing - 842 rows
- Personal Finance - 897 rows

#### Conclusion

The Naive Bayes with CountVectorizer and Logistic Regression with TfidfVectorizer worked very well with an high train and test score, even though both subreddits were almost in the same category.<br>
Evaluated the model and notice the accuracy level is really high with 92% for Logistic Regression with TfidfVectorizer and 91.67% for Naive Bayes with CountVectorizer.<br>
Model precision of Logistic Regression is slightly higher to Naive Bayes at 92.36% compared to 91.69%.<br>
This could be attributed to the current market condition, with Covid-19 having a negative impact on job securities and financial stability.
Hence more retail investors, would not want to venture into riskier investments and focus more to reduce their reliabilities.

#### Recommendation

We can tune the parameters of the model, to get an more accurate however it's really time consuming.
Hence I suggest to allocate more time on the modeling section, as it's really important to obatin the optimum results.<br>

Right now with investors appetite at a all time low, I would suggest financial consultants to work with their current and potential clients in other financial services like offering them to refinance with a lower interest rates, taking up insurance or short term saving plans with interest<br> 

This can been seen in the word cloud where student loan, debt, credit cards and tax were ones most mentioned.
