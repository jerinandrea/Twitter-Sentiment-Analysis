# TWITTER-SENTIMENT-ANALYSIS

## Data Collection

The tweets are related to the top Indian retailers and are collected using snscraper module using python. 
Tweets are collected from  JioMart, BigBasket, AmazonIndia,Snapdeal,Flipkart and Myntra.
The tweets are collected over a period  from 2019-01-01 to 2021-12-31 using keywords Amazon support,Flipkart,Snapdeal,Myntra,Jiomart,BigBasket.


## Packages Used

1.SnScraper

2.Pandas

3.Matplotlib


4.Sklearn


5.Wordcloud


6.Textblob

## Data Preprocessing

It is essential to preprocess the data before feeding to the model necessary data cleaning stets are implemented.

Removed "@" mentions,
Removed "#" tags,
Removed extra space,
Removed punctuations,
Removed Numerical values,
Removed Duplicates,
Removed Hyperinks.
Removed Underscores,
Removed Next lines,
Removed Emojis,
Converted the data in to lowecase

As there was no target column, it is created by calculating the subjectivity and polarity the tweets having polarity greater than 1 are classified as positive tweets, the tweets having polarity less than 0 are classified as Negative tweets, the tweets having polarity equal to 0 are classified as neutral tweets.

## Model Building

As we have only one target column and one independent column and the data we had was catrgorical data so i have selected Random forest and used converted the data in to train and test data and the data is fed to the model.
The Accuracy is 91.78%
The evaluation of the model are as below
                
![image](https://user-images.githubusercontent.com/75555487/153761788-cfbd2a47-a65a-437f-8a4b-0f0361bfe2f2.png)



