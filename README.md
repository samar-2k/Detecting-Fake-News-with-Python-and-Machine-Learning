# Detecting-Fake-News-with-Python-and-Machine-Learning
-> Fake news is hoaxes spread via mass communication media <br/>
-> In modern day it is a rather a large menace <br/>
-> To find out fake news in a corpus, we need to label it REAL or FAKE depending on some parameters<br/>
-> The dataset that is used is news.csv and has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. The dataset takes up 29.2MB of space. <br/>
-> TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms. <br/>

->IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus. <br/>

-> The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features. <br/>
-> PassiveAgressive classifier: Used for large scale learning <br/>
                                online classifier <br/>
                                passive if prediction is correct <br/>
                                aggresive if prediction is wrong <br/>
-> Accuracy of 92.89% <br/>
-> Created a confusion matrix with 589 true positives, 587 true negatives, 42 false positives, and 49 false negatives. <br/>
                    array([[588,  50], <br/>
                           [ 44, 585]],)<br/>
