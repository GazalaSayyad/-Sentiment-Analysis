# -Sentiment-Analysis
Naive Bayes classification for sentiment analysis.


Sentiment analysis or sentiment classification fall into the broad category of text classification tasks where you are supplied with a phrase, or a list of phrases and your classifier is supposed to tell if the sentiment behind that is positive, negative or neutral. Sometimes, the third attribute is not taken to keep it a binary classification problem. In recent tasks, sentiments like "somewhat positive" and "somewhat negative" are also being considered.



The words that you found out in the bag-of-words will now construct the feature set of your document. So, consider you a collection of many movie reviews (documents), and you have created bag-of-words representations for each one of them and preserved their labels (i.e., sentiments - +ve or -ve in this case). 
This representation is also known as Corpus.

All the rows are independent feature vectors containing information about a specific document (movie reviews), the particular words and its sentiment. Note that, the label sentiment is often denoted as (+, -) or (+ve, -ve). Also, the features w1, w2, w3, 34, ..., wn are generated from a bag of words, and it is not necessary that all the documents will contain each of these features/words.

You will pass these feature vectors to the classifier.
