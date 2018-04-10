# Twitter-Sentiment-Analysis
Value Miners Hackathon

Using a textblob Naive Bayes Classifier to identify sexist and racist tweets:
https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/

ideas to improve:
- better data cleaning <- BS4, delete user word maybye

- use Positive Naive Bayes Classifier (works on labeled and unlabeled dataset) 

- load all of the data in a few parts not only 10k (use update() function) <- Memory problem, textblob NB classifier is poorly optimized
(64 bit and 32bit also makes a difference) it is a better idea to use MultinominalNB classifier form scikit learn or use other ML algorithm for example Support Vector Machine

