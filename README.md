## Yelp Reviews
- In this project, Natural Language Processing (NLP) strategies will be used to analyze Yelp reviews data
- Number of 'stars' indicate the business rating given by a customer, ranging from 1 to 5
- 'Cool', 'Useful' and 'Funny' indicate the number of cool votes given by other Yelp Users. 
![image.png](https://upload.wikimedia.org/wikipedia/commons/a/ad/Yelp_Logo.svg)

### Steps:

- Run the following Command:-

  `import nltk` <br/>
  `nltk.download()`
  
- Download stopwords Package By execute this command

   `import nltk`<br/>
   `nltk.download('stopwords')`
- NLP:
  - Tokenization
  - Stemming
  - Lemmatization
  - Stopwords
  - **term frequency(tf)**=[(no of frequency of a word in a sentence)/(total no of words in sentense)]

  - **IDF**=log[(no of sentenes)/(no of sentenses containing words)]

  - **tf-idf model**= Tf * IDF


