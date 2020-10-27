# coursera_4_applied_text_mining
My work from Coursera's Applied Text Mining in Python course, the fourth course in the data science specialization through UM. The course is hosted here: <https://www.coursera.org/learn/python-text-mining>

# Author info
Patricia Schuster  
University of Michigan  

# Week 1: Working with Text in Python  

* [Notes](week_01_notes.ipynb)
    * Basic operations for handling text in python  
    * Working with larger texts  
    * File operations  
    * Regular expressions  
    * Working with text data in pandas

# Week 2: Basic natural language processing  

* [Notes](week_02_notes.ipynb)
    * Basic NLP tasks with `NLTK`  
    * Frequency of words, normalization, lemmatization, tokenization  
    * Part of speech (POS) tagging  
    * Parsing sentence structure  

* [Assignment 2](Assignment+2.ipynb)  
    * Use `nltk` to explore the book Moby Dick  
    * Create a spelling recommender function that uses `nltk` to find words similar to the misspelled words  

# Week 3: Classification of text

* [Notes](week_03_notes.ipynb)  
    * Text classification  
    * Supervised learning for text: topic identification, spam detection, sentiment analysis, spelling correction  
    * Types of textual features  
    
* [Assignment 3](Assignment+3.ipynb)  
    * Explore text message data and create models to predict if a message is spam or not  
    * Fit data using several model types: Count Vectorizer, multinomial Naive Bayes, Tfidf vectorizer  
    * Fit a logistic regression model and calculate AUC with additional features: length of the document, number of digits, number of non-word characters  
    
# Week 4: Topic modeling

* [Notes](week_04_notes.ipynb)  
    * `WordNet`  
    * Path similarity, Lin similarity  
    * Distributional similarity  
    * Latent Dirichlet Allocation (LDA)  
* [Assignment 4](Assignment+4.ipynb)    
    * Find path similarity between two documents  
    * Find the pair of documents with the highest maximum similarity score  
    * Model topics in news data, generate topic distribution