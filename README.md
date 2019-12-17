# Whose Line is it Anyway?

## About

A repository of code from a machine learning project to classify Jane Austen and J.K. Rowling quotes. Written in jupyter notebooks.

A full write up at medium.com/@kscherich

## Structure

* **Web_Scraping**: Module to scrape Jane Austen and J.K. Rowling quotes from goodreads.com.

* **Text_PreProcessing**: Module to clean the quotes to prepare for a Bag of Words model (i.e., remove duplicate quotes, remove foreign language quotes, remove puncutation/ capitalization, generate a list of lemmas, remove quotes made up entirely of stop words), and calculate other features (i.e., sentence length and the percentage of words per sentence that are stop words). Natural Language Processing conducted with spaCy.

* **Data_Exploration**: Module to visually explore differences between the Jane Austen and J.K. Rowling classes.

* **Modeling**: Module to train and test Naive Bayes, Logistic Regression, and KNN machine learning models. This module also explores the most important features and mis-classified quotes.
