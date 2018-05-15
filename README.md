# Basic-Sentiment-Analysis with Python
#### Note1: Don't expect complicated and tremendous strategies to achieve opinion mining, this is only a practical instance of using some basic rules to elicit the polarity of an input text.
#### Note2: I focus on detecting the overall polarity (Document Level Sentiment Classification) instead of Aspect level Sentiment Classification.
#### Note3: For detecting the polarity of the sentences, a dictionary has been used. A dictionary is no more than a list of words that share a category. But sth that should be considered is, the design of the dictionaries depends on the domain where you want to do the opinion mining.
### Text Structure:
*   Each input txt is a list of sentences, each sentence is a list of tokens and each token is a row/tuple consists of <i>three</i> features:
   *   First Feature: Exact word
   *   Second Feature: A word Lemma (e.g: am/is/are:be)
   *   Third Feature: A list of associated tags
## Steps:
### Preprocessing the input text
