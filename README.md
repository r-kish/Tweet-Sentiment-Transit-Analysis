# Tweet Sentiment Transit Analysis
### (Please see below for public demonstration of sentiment analysis!)
## Brief Table of Contents of Research Paper
- Introduction
- Literature Review
- Methodology with Sentiment Analysis of Tweets in RStudio
- Sentiment Analysis of Tweets in RStudio
- Public Transit Performance Analysis in RStudio
- Longitudinal Analysis of Tweet Frequency and Tweet Sentiment pre- and post-COVID pandemic
- Other Visualizations in Tableau

This project started during my civil engineering studies at the City College of New York, and right when I started concentrating on Transportation Engineering. This was also my first deep dive into R, and the project that made me want to switch from engineering to pursue data analysis. Data analysis was done in R, data extraction was done in Python, and data cleaning was done in both R and Excel.

The project represents the New York Metropolitan Area, and covers an in-depth review of sentiment analysis conducted over a period of time on 300,000+ tweets related to MTA and New Jersey Transit agencies such as NYC Transit, Metro-North Railroad, and Long Island Rail Road. Additionally, transit performance analysis was conducted on the same date range as the transit-related tweets across the various transit agencies. A longitudinal study was conducted, comparing the tweet sentiment and transit performance from 2015-2016 (Pre-COVID era) to that of 2020-2021 (Post-COVID era). The findings suggest that customer social media behavior, and their concerns regarding transit performance, change in the wake of a natural disaster such as the COVID-19 pandemic.

The duration of my research was conducted between July 2020 and June 2023. The following research paper is published in Sustainability, and C2SMART in collaboration with USDOT University Transportation Research Center Region 2 (City College of New York), New York University, Rutgers University, University of Washington, and University of Texas at El Paso. This project was made possible through funding from the National Science Foundation.

### Read the published research paper here:
[UTILIZING SOCIAL MEDIA DATA FOR ESTIMATING TRANSIT PERFORMANCE METRICS IN A PRE- AND POST-COVID-19 WORLD](https://www.mdpi.com/2071-1050/15/23/16183)


## Sentiment Analysis Demo
Since the R code and methods used in the original sentiment analysis project are privately protected by the City College of New York, I've included a demonstration of the various sentiment analysis methods used in this folder.

See my [Sentiment Analysis Demonstration](https://github.com/r-kish/Tweet-Sentiment-Transit-Analysis/tree/main/Sentiment_Analysis_Demo) for the code.

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

