# Sentiment Analysis Classification from Comment Section on Gibran's YouTube Video "Generasi Muda, Bonus Demografi dan Masa Depan Indonesia"

It's a random day, and suddenly we decided that we would do a sentiment analysis classification research on Gibran's, Indonesia vice president, most viral yet controversial YouTube video;  "Generasi Muda, Bonus Demografi dan Masa Depan Indonesia" for our Ethics Paper.

The methodologies for this research
- Crawl the comment section
- Preprocessing the data
- Visualize the data
- Classification using RoBERTa Base Sentiment Classifier

## Data crawling
First of all, we crawled the comment section on his vide (https://youtu.be/SzXMacu80o8?feature=shared)
This crawled 24.231 comments and their replies and stores it in csv format.

## Preprocessing the data
The text data needs to be cleaned in order to get visualized and classified with the model. This includes case folding, normalization, tokenizing, stopword removal, and stemming.

## Visualization
The preprocessed data is used to visualize using wordcloud and bar chart.

## Classification
RoBERTa Base Sentiment Classifier by Wongso is used to classify the comment sentiment based on positive, neutral, or negative sentiment.
