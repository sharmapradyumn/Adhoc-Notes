# DAY 29 
# Deeplearning
1. ``NLP`` Natural language processing(lexicon,Sematic)
2. ``NN`` Neural Networks(ANN,CNN,RNN)
```
* text processing
* text summerise
* opinion mining
* Reviews
```
## NLP libraries
1. NLTK
2. Textblob
3. spacy


## NLTK(Natural Language Tool Kit)

* `` Web Crawler`` this is a program that show  your search result
* `` web spider``


* To install
``pip3 install NLTK textblob spacy``
* download all the data from standford (3.5G)
Web Scraping
Requirements
* website is hosted somewhere
* web crawler and web spyder
* most powerful crawler is google bot , it moves to every website in every 2 hr to refresh its index table
#### practice site for web scraping
* Wiki
* Britanika
* php.net
#### Parser
* Use BeautifulSoup(https://www.crummy.com/software/BeautifulSoup/bs4/doc/), to install
```
pip3 install bs4
```
* to install parser
```
apt-get install python-html5lib
            or
pip3 install html5lib
```
*
### Tokenization
* DATA can be divided into 3 categories :
1. sentence
2. words
3. character
* this concept is based on making a list by seperating the words or sentences
### Stemming
* when there is a huge amount of data and need to find a specific keyword in it to be able to predict the type of text either mail or spam
* just make a decision based on certain keyword search
### Lemmatization
* it creates a meaningful word from a collection of words
### Task
* Take picture of a newspaper and extract text + apply nltk + remove stop words and plot top 10 frequency graph(cv2 + )
* make word from a sentence
*  apply naive bayes while reading mail from program
* find a speech of APJ abdul kalam, scrape it , tokenize it + remove stopwords and apply stemming then replace the word and save it in a new file.
* mark a mail as a spam using python
SPAM and HAM detection