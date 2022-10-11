# IMDB_reviews_-sentiment_classification_by_NLP
I used 'IMDB Dataset of 50K Movie Reviews' dataset(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)<br/>
The dataset consists 👇<br/>
![image](https://user-images.githubusercontent.com/90775147/195128670-9ed29702-4e4b-41e7-9215-47b34e2a4b27.png)

## Performeed following tasks to build Sentiment Classification Model
#### Imported nltk
The Natural Language Toolkit (NLTK) is a platform used for building Python programs that work with human language data for applying in statistical natural language processing (NLP). It contains text processing libraries for tokenization, parsing, classification, stemming, tagging and semantic reasoning.

#### Imported CountVectorizer
CountVectorizer means breaking down a sentence or any text into words by performing preprocessing tasks like converting all words to lowercase, thus removing special characters.


### Data Preparation, Tokenization, Stopwords Removal and Stemming<br/>
・Removed links and all the special characters from the review column<br/>
・Tokenized and removed the stopwords from the review column<br/>
・Stem the words in the review column<br/>

#### To perform above activities 
・Imported re<br/>
A regular expression (RE) is a language for specifying text search strings. RE helps us to match or find other strings or sets of strings, using a specialized syntax held in a pattern.

・ Imported SnowballStemmer
Snowball is a small string processing language for creating stemming algorithms for use in Information Retrieval, plus a collection of stemming algorithms implemented using it.

#### Wordcloud of the review column:
![image](https://user-images.githubusercontent.com/90775147/195133829-46044484-47d5-4905-8d96-dc33f2037cdb.png)

### Text Vectorization
Text Vectorization is the process of converting text into numerical representation. It means to transform all the text tokens into numerical vectors.

### Text Classification
Trained a Text Classification model to analyse sentiment of Review.
