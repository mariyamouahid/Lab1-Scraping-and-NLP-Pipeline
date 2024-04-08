# Web Scraping and Natural Language Processing (NLP) Lab

## Objective
The objective of this lab session was to gain practical experience in web scraping and Natural Language Processing (NLP) techniques. The tasks aimed to familiarize us with extracting data from Arabic web sources and implementing various stages of NLP processing.

### 1. Data Loading
#### Scraping:
- Scraping is the process of extracting data from websites. 
- In this lab, data scraping is performed to collect recipe data from various pages on the Fatafeat website.
- BeautifulSoup, a Python library for web scraping, is utilized to parse the HTML content of the web pages and extract relevant information such as recipe titles, properties, chefs, links, ingredients, and recipes.
- The `scrape_recipe_data` function is defined to scrape recipe data from the specified URLs for cakes, pizzas, and cookies.
- The scraped data is stored in MongoDB for efficient storage and retrieval.

### 2. NLP Pipeline
#### Text Cleaning:
- Arabic text cleaning is performed to remove non-Arabic characters and extra spaces from the scraped data.
#### Tokenization:
- The NLTK library is used for tokenization of the text data into individual words.
#### Stop Words:
- Arabic stopwords are removed from the tokenized text to eliminate common words that do not add significant meaning to the data.
#### Discretization:
- The length of the 'ingredients' text is discretized into categories ('short', 'medium', 'long') based on predefined interval borders.
#### Normalization:
- Arabic text normalization is performed to remove diacritics and replace different forms of the same letter.
#### Stemming and Lemmatization:
- Stemming and lemmatization techniques are applied to the text data to reduce words to their root forms for analysis.

### 3. Text Analysis
- Implemented stemming and lemmatization techniques on the processed text data and compared their effectiveness.
- Applied Parts of Speech (POS) techniques using both rule-based and machine learning approaches.

### 4. Named Entity Recognition (NER)
- Implemented NER methods to identify and classify named entities in the text data.

## Conclusion
This lab effectively combines data scraping with NLP techniques to collect, preprocess, and analyze text data from the web. The scraping process enables the extraction of relevant information from web pages, while the NLP pipeline facilitates text processing and analysis for various applications such as text classification, sentiment analysis, and information extraction. Overall, this lab provides practical experience in utilizing web scraping and NLP techniques for data collection and analysis tasks.
