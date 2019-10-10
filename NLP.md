# Natural Language Processing

## The Bigram Language Model

<p align="justify">
  The statistical language model is known as the probability ditribution of the sequences of words that provides context distinguish between words and phrases that sound familiar.
  The main goal of applying a probabilistic language model is to compute the probability of a sentence or sequence of words.
</p>

<p align="justify">
  The project revolves around data collection using a webcrawler package in python programming language. The data is a collection of sport new information from http://bbc.com. A corpus is built from the 10,000 sentences collected automatically by using the webcrawler related to sport news. Then, an English stemmer based on Porter’s algorithm is implemented. After that, the constructed corpus is processed by using stemmer in which a dictionary is built. Lastly, a bigram model is built by selecting 10% of the total data as test data. 90% accuracy of classification is obtained.
</p>

<p align="justify">
  In the beginning of the project, the data was collected automatically using webcrawling method such that collector did not need to go to each pages of the news but rather making a loop that collect information per news webpage. The focus of the webpage was sport news in this project. 10,000 sentences were collected to form the corpus.
</p>

## Making a dictionary from a corpus
<p align="justify">
  Some part of the 
  After the data collection, the articles are segmented into sentences. Then, the 'Regular Expression' was applied to seperate the text into word by changing all non-alpha into newlines.

  The segmented words were then sorted in alphabetical order. Then they were merged per similar words and each unique words was counted (how many times appeared)
</p>

## The implementation of English Stemmer
<p align="justify">
  Another part of the NLP Project is to create the dictionary after porter stemming process. In Natural Language Processing (NLP), stemming is the process of reducing derived or infected words to their own word stem. The word stem is the root form that generally written.

  Using the collected corpus, an English stemmer based on Porter's algorithm was applied. Then the dictionary was built based on the process corpus.
</p>

## Building the Bigram Language Model
<p align="justify">
  Using the collected corpus, 100 random sentences were chosen as a test data and the rest as the training data. The bigram model was built after applying the Porter's Stemming.
</p>

## Link to the source code
<p align="justify">
  The link to the source code is available here:
  https://github.com/Melvin555/NLP
</p>


