# Web-Scraping-Project-Gutenberg

# Overview

This is a web crawling task, which downloads the top-k ebooks (k=number of ebooks to download) in the last 30 days from Project Gutenberg using BeautifulSoup library.

# Data Processing
The downloaded texts were processed using nltk library to tokenize and lemmatize the texts.

# Text Analytics
A unified vocabulary was created for the downloaded texts and the top-100 words were obtained using different statistics such as total word counts, total number of ebooks each unique word appears in and variance counts. 
