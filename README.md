# Finviz Stock Screen and Sentiment
## Stock screener and sentiment analysis using data and news from FinViz

* The purpose of this repo is to extract stock data as well as news articles stored at [FinViz](https://finviz.com/) for the stocks we screened based on the selected criteria.

* The tools used to accomplish this are [finvizfinance API](https://finvizfinance.readthedocs.io/en/latest/screener.html#module-finvizfinance.screener.overview) to setup a stock screen and pull news articles and [NLTK Vader Lexicon](https://pypi.org/project/vaderSentiment/) to obtain sentiment scores.

* Added also [FinViz scraper](finviz_scraper.ipynb) that parses HTML page and locates tables on the page, using [Beautiful Soup](https://pypi.org/project/beautifulsoup4/) library.

#
© 2021 Author: Dragan Bogatic