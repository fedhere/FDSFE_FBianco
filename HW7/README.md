# DUE 11/20

# READING (you will be asked questions on this after thanks giving)
_On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜_
https://s10251.pcdn.co/pdf/2021-bender-parrots.pdf

# Assignment: Follow the notebook 
the only step that remains is to perform the sentiment analysis.
You are using a pretrained model that weights each word independently by its positive/negative weight and sums the weights of all words. 

NOTE: 
This is not an ideal way to do sentiment analysis - the correct way, and the intended use of the data, would be to _train_ the model on this dataset because otherwise the positive/negative connotation of the words is taken out of context and may not be applicable in general (e.g. a model trained for sentiment analysis on twitter, where posts are of limited length, may not perform on a book analysis)

