# Sentiment Analysis Demonstration (RStudio)

Since the R code and methods used in the original sentiment analysis project are privately protected by the City College of New York, I have included a demonstration of the various sentiment analysis methods used in this folder.

All methods shown are those used in the original transit/sentiment analysis project.
In the context of this study, sentiment refers to the positive or negative valence of emotion that is attached to a word or passage.

## Sentiment analysis of top words from Jane Austen's works (used to measure sentiment of Tweets)
- This portion of the analysis relies on a sentiment-rated dictionary to be paired with the tokenized dataset. 
- When conducting sentiment analysis within the Tweet/Transit study, custom dictionaries were used to focus on transit-specific terms. This allowed for identifying top concerns of MTA customers, and their expectations of transit service.
![AustenWordFreq](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AustenWordFreq.png)

## Sentiment analysis of each separate book from the Jane Austen library (used to categorize transit performance metrics within Tweets)
- This portion of the analysis gives an idea of how sentiment changes throughout the length of an entire book, as well as how sentiment differs from book to book.
- In the Tweet/Transit study, this concept was used for the purpose of categorizing performance metrics identified within Tweets in order to measure the specific level of sentiment customers had towards different aspects of public transit performance, and identify their concerns in order of severity.
![AustenSentiment](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AustenSentiment.png)

## Word Cloud (used to summarize overall Tweet linguistics by sentiment)
- This word cloud displays words based not only the sentiment of the word, but the frequency of the word within the data. Bigger words have higher frequency, whereas words further from the middle have stronger polarity of sentiment.
- This word cloud was applied to the data within the Tweet/Transit study in order to show a brief summary of the general sentiment of the MTA customer base. If you read the research paper, you will see that the words displayed are those that coincide with the top customer concerns, as well as any other positive/negative words that are associated with contributing to sentiment within those tweets.
![AustenCloud](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AustenWordCloud.png)

## Comparing word frequencies of Jane Austen's works to the Bronte Sisters' + H.G. Wells works.
- While this concept wasn't used in the Tweet/Transit study, this concept could have been used had we conducted a study regarding the difference in word frequencies/post sentiment across different social media platforms.
- tidyverse was used to tokenize every book (separate every word into its own tibble)
![AllWordFreq](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AllWordFreq.png)



