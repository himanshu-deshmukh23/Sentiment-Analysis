# Sentiment Analysis of Stock News
## Description:
Implemented a comprehensive sentiment analysis project to gauge market sentiment for specific stock tickers using Python. Leveraged web scraping, natural language processing, data manipulation, and data visualization techniques to analyze news articles related to prominent companies in the stock market. The project aimed to provide insights into market sentiment trends over time for informed decision-making.

## Key Contributions:

Web Scraping: Utilized the urllib library along with BeautifulSoup to scrape relevant news articles from the Finviz website for chosen stock tickers (e.g., AMZN, GOOG, FB).

Sentiment Analysis: Employed the nltk.sentiment.vader module for sentiment analysis, utilizing the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon to compute sentiment scores for news article titles. The sentiment analysis provided a quantifiable measure of the positive, negative, and neutral sentiments.

Data Manipulation: Utilized the pandas library for data manipulation, transforming the scraped data into a structured DataFrame. Extracted relevant information such as ticker symbol, publication date, time, and news title for further analysis.

Time Series Analysis: Processed and converted date data using pd.to_datetime, enabling temporal analysis. Grouped sentiment scores by ticker and date, calculating the mean sentiment scores to observe sentiment trends over time.

Data Visualization: Utilized matplotlib to visualize sentiment trends through bar plots. Created meaningful visualizations by plotting the mean sentiment scores for each ticker over different dates. The visualizations provided an intuitive understanding of sentiment shifts over time.
