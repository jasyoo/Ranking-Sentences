README

included:
All source files (.py)
this README

I'd like to first mention that the biggest problems I encountered during this project were vectorizing sentences rather than words. Having the machine learn relevance of each sentence based on the overall meaning of the passage, and vectorizing it was a big challenge.

Once that has been established, I used cosine similarity to rank each vectorized sentences based on relevance since other techniques like bagofwords and TF-IDF ignore the order of words. 

Using GloVe to create vectors for the input sentences. Although Bag-of-Words and TF-IDF can also be used to create features for the sentences, but these methods ignore the order of the words.

Also included is a bar chart showing the frequency of each word, and a wordcloud presentation without stopwords. 

I hope you enjoy the model, and I welcome any comments or suggestions to improve this model. 
