# Using NewsAPI to scrape Bitcoin and Ethereum news data and performing sentiment and NER analysis using Spacy

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin. 

In this script we scrape NewsAPI for articles on Bitcoin and Ethereum, text data is cleaned and sentiment analysis is performed on both the cryptocurrecies .NLTK is used to for regex, lemmatization and tokenization. Spacy is used for Named Entity Recognition of the text data, and to extract the most named entities in both of the cryptos
