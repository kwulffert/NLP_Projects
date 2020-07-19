# NLP_Projects
This is my corner to experiment with NLP algorithms.

### [Sentiment analysis of US airlines tweets using ULMFiT](https://github.com/kwulffert/ULMFiT_Sentiment_Analysis/blob/master/ULMFiT_Sentiment_Analysis.ipynb)

In this notebook the NLP transfer learning method "Universal Language Model Fine-tuning" (ULMFiT) is applied for sentiment classification of travellers' tweets about their experiences flying with six US airlines.

The work is structured as follows:

* Import libraries.
* Data load.
* Data exploration.
* Text pre-processing.
* Universal Language Model Fine-tuning (ULMFiT) application.
 * Getting the data ready for modeling.
 * Tweets generator Language Model.
 * Sentiment classifier of US airlines tweets.
* Analysis of results.
* Conclusions.


### [Alice's adventures in wonderland](https://nbviewer.jupyter.org/github/kwulffert/NLP_Projects/blob/master/Alices_Adventures_In_Wonderland.ipynb)
As Alice's adventures in wonderland has taken a special place in our home, I found it a great fit to train a word2vec model, use bigrams and trigrams to include in the embeddings context around the words and to find out if similar words can be clustered to characters.

The notebook is divided in the following steps:

* Data load and pre-processing.
* Text pre-processing.
* Tokenization and lemmatization.
* Create bigrams and trigrams.
* Create and train a word2vec model.
* Explore similarity of words resulting from the model.
* Visualisation of similarity: are cluster of words related to characters from the book?.
