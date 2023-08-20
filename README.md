# Capstone-3-Coronavirus-Tweet-Sentiment-Analysis
Classification ML project to predict the Sentiment of the Tweets using NPL method.

We have been provided with Coronavirus Tweet Sentiment Analysis dataset for the year 2020. This dataset contains the tweets made by people during the covid-19 pandamic. while analysing the data we have to create a Mechine Learning model to predict the tweet sentiment.

![How-Can-News-API-Supercharge-Your-Sentiment-Analysis-1](https://github.com/cltgoutham/Capstone-3-Coronavirus-Tweet-Sentiment-Analysis/assets/124442638/0755129e-b0c2-4bf6-bc40-d102e2d4e73b)

**Introduction**

Our objective is to build a classification model to predict the sentiment of COVID-19 tweets.The tweets have been pulled from Twitter and manual tagging has been done then. The names and usernames have been given codes to avoid any privacy concerns.
The dataset contains 41,157 rows and 6 columns, columns includes UserName, ScreenName, Location, OriginalTweet, TweetAt, Sentiment.

**Dataset Information :**
[Coronavirus Tweets csv file](https://drive.google.com/file/d/1GynuN4PNvefG0F9GkLlDaxQEUJNN8e24/view?usp=drive_link)

# Approach to the Project

**NLP Technique is used to build the model.**

## 1.**Data Collection and Cleaning**
* Check for duplicate values in the dataset
* Checking null values
* Examining the dataset to get basic informations
* Merging the two dataset.

## 2.**Exploratory Data Analysis**
* Analysing the data through different visualization techniques.
* Univariate and multivariate analysis were made.

![newplot (1)](https://github.com/cltgoutham/Capstone-3-Coronavirus-Tweet-Sentiment-Analysis/assets/124442638/be58348d-680b-47f9-8bef-7750e0fb1503)
![newplot](https://github.com/cltgoutham/Capstone-3-Coronavirus-Tweet-Sentiment-Analysis/assets/124442638/beeb547b-90d0-4b8e-aacf-0e9d89f35fbc)

Word cloud

![download](https://github.com/cltgoutham/Capstone-3-Coronavirus-Tweet-Sentiment-Analysis/assets/124442638/b7c4f496-6fb9-48d9-8071-562448f0226f)

## 3.**Data Preprocessing**
* Text Preprocessing - Removed Punctuations, Numbers, Urls
* Stopwords Removal - Stop words are those words in natural language that have a very little meaning, such as "is", "an", "the", etc. By removing these words we can reduce the noise in the data.
* Tokenization - Tokenization is the process of breaking down a sequence of text into smaller units called tokens.
* Stemming - Stemming is a method used in natural language processing to reduce words to their base or root form. The purpose of stemming is to normalize words so that different variations of the same word are treated as the same word. 
* Vectorization - Vectorization is the process of converting textual data into numerical vectors that can be used as input for machine learning models. 

## 4.**Model Building**
In this classification project we have used 6 Machine Learning Models.

LogisticRegression, SupportVectorMachine, DecisionTree, RandomForest, AdaBoost, GradientBoosting Classifier.

![Screenshot (6)](https://github.com/cltgoutham/Capstone-3-Coronavirus-Tweet-Sentiment-Analysis/assets/124442638/5c8113b4-ad7f-4fdd-8318-a31071d707c9)

## 5.**Model Evaluation**
For comparing the model based on their performance we have used Accuracy score, Precision, Recall and F1 score.

## 6.**Conclusion**

 Linear regression model with hyperparameter tuning gave the best performance among all the models.



