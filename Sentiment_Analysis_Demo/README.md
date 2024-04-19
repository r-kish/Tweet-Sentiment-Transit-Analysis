# Sentiment Analysis Demonstration (RStudio)

Since the R code and methods used in the original project are privately protected by the City College of New York, I have included a demonstration of the sentiment analysis techniques used in this folder.

All methods shown are those used in the original transit/sentiment analysis project.
In the context of this study, sentiment refers to the positive or negative valence of emotion that is attached to a word or passage.

## Comparing word frequencies of Jane Austen's works to the Bronte Sisters' + H.G. Wells works.
- While this concept wasn't used in the Tweet/Transit study, this concept could have been used had we conducted a study regarding the difference in word frequencies/post sentiment across different social media platforms.
- tidyverse was used to tokenize every book (separate every word into its own tibble)
![AllWordFreq](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AllWordFreq.png)

## Sentiment analysis of top words from Jane Austen's works
- This portion of the analysis relies on a sentiment-rated dictionary to be paired with the tokenized dataset. 
- When conducting sentiment analysis within the Tweet/Transit study, custom dictionaries were used to focus on transit-specific terms. This allowed for identifying top concerns of MTA customers, and their expectations of transit service.
![AustenWordFreq](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AustenWordFreq.png)

## Sentiment analysis of each separate book from the Jane Austen library
- This portion of the analysis gives an idea of how sentiment changes throughout the length of an entire book, as well as how sentiment differs from book to book.
- ok
![AustenSentiment](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/blob/main/Sentiment_Analysis_Demo/images/AustenSentiment.png)



