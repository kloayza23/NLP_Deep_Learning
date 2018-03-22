# Analsis of natural language processing with deep learning #

The main contribuition of this project is the use of the deep learning tools in their application in the NLP projects.

## Outline ##

#### Concepts of natural language processing ####

Here is explained the importance of the natural language processing and their appliances.
	
#### Concepts of Deep Learning ####

Here is explained the types of tools of deep learning as LSTM or Convolutional neural networks, 
and how this tools can be used in the NLP projects.
	
#### Load Data Set ####
The first dataset used is metamorphosis_clean.txt, this file can be download here:
https://github.com/nickoralias/clean-text/blob/master/metamorphosis_clean.txt
The second dataset used is txt_setoken positive and negative reviews, this file can be download here:
http://www.cs.cornell.edu/people/pabo/movie-review-data/review_polarity.tar.gz
#### Split text with white space ####
Here show how to split with white space with string functions.
#### Remove punctuation ####
To remove punctuation is necessary use the function string.punctuation.
#### Normalize words in lower case ####
The normalize of word only is the conversion to lower case.
#### Tokenization with NLTK ####
Here words is sent to sent_tokenize to convert to an array of words.
#### The Bag of Words Model(BOW)	 ####
This model is necessary because the algorithm of machine learning only work with number, and for this reason this model convert all features in numbers. This model can be used to classify documents, where each document is a input and a label is the output.
#### Word Count with CountVectorizer ####
This function let a collection of documents and build a vocabulary de known words.
#### Prepare Text Data With Keras ####
To work with deep learning, is necessary work with numeric data, therefore is very important to work with the process of
encode categorical to numeric data. This process can be done trhough tokenizer process. Also exist the process hashing_trict to encode data.
#### Encoding with One Hot ####
A way to encode categorical data is through one_hot encoding, where it receive the vocabulary size.
#### Hash encoding with Hashing Trick ####
#### Text function to matrix tokenizer ####
Another function of tokenizer is to convert text to matrix, and this is possible with function tokenizer.texts_to_matrix, where it have all information of the text, but transform in 1 and 0 through matrix.
#### Design Vocabulary ####
#### Prepare data for Sentiment Analysis ####
#### Final Project ####
