# British-Airways-Customer-Experience-Sentiment-Analysis-Project


###### British-Airways-Customer-Experience-Sentiment-Analysis-Project **Using NLTK (Natural Language Toolkit)**



In This Project Find Sentiment of British Airways Users Reviews and maximum people Sentiment are **Positive** and **Negative.** **Subjectivity Scores** to understand the prevalence of personal opinions in these reviews.Using **Subjectivity Score** shows how many reviewers gave their **Personal Opinion.** and using WordCloud visualizing unstructured text data and getting insights on trends and patterns.Analyze the sentiments of British Airways customers through their reviews. By employing sentiment analysis techniques.By employing Sentiment Analysis Techniques, we categorize the sentiments into **Positive** and **Negative** and **Neutral**, revealing an overarching Perspective of the Airline's Service Quality from the Customer's point of view.



![Sentiment Analysis of British Airways Customer Experience](https://github.com/anandshaw123/British-Airways-Customer-Experience-Sentiment-Analysis-Project/assets/129979768/2f7a7a4a-9a6b-4421-805a-cfb06015bc27)



## **Project Objective:**
Determine the subjectivity levels within the reviews to understand the prevalence of **personal opinions.**

To categorize customer reviews into **Positive** and **Negative** **Neutral** Sentiments.

WordCloud for visual data analysis, extracting key trends and patterns to gain deeper insights into customer sentiments.



## **Tool/Technique:**

pandas
numpy
nltk
import re
import string
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords
from nltk.stem import SnowballStemmer
from nltk.stem import WordNetLemmatizer

from nltk.probability import FreqDist
from textblob import TextBlob
from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer
from wordcloud import WordCloud


## Preprocessing:

**Lowercasing**,
**Tokenization**,
**Removing punctuation**,
**Stop word removal**,
**Stemming and Lemmatization**



## **Subjectivity Analysis:**

This Subjectivity Score is shows that how many reviewers Contain Personal Opinion. If a sentence has high subjectivity close to **1,** It resembles that the text contains more personal opinion than factual information. and i calculated the Subjectivity score using **TextBlob** tool.In out analysis some of the reviews having **Personal Openion.**

## **Compound Score:**
The compound score is the sum of positive, negative & neutral scores which is then normalized between -1(most extreme negative) and +1 (most extreme positive). It represents the overall sentiment of the sentence.

## **WordCloud Visualization:**

It contains the most frequently occurring words in the data, with more frequent words appearing larger in size than less frequent ones.Word clouds are great for visualizing unstructured text data and getting insights on trends and patterns.














