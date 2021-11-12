![moviesystem]("https://user-images.githubusercontent.com/71333855/141502778-57e0a158-e094-4264-bfc0-d989a51c9b5c.png)

# Simple Netflix Movie Recommendation System

This respository contains an example of a simple Netflix movie recommendation system. The data was sourced from kaggle.com and can be found [here](https://www.kaggle.com/shivamb/netflix-shows)


# Recommendation System (Content Based)
**The TF-IDF(Term Frequency-Inverse Document Frequency)** score is the frequency of a word occurring in a document, down-weighted by the number of documents in which it occurs. This is done to reduce the importance of words that occur frequently in plot overviews and therefore, their significance in computing the final similarity score. It has many uses, most importantly in automated text analysis, and is very useful for scoring words in machine learning algorithms for Natural Language Processing (NLP).

**The TF-IDF model computes tfidf with the help of following two simple steps:**

* Step 1: Multiplying local and global component:

In this first step, the model will multiply a local component such as TF (Term Frequency) with a global component such as IDF (Inverse Document Frequency).

* Step 2: Normalise the Result

Once done with multiplication, in the next step TFIDF model will normalize the result to the unit length.

As a result of these above two steps frequently occurred words across the documents will get down-weighted.

Stopwords are those words that occur so frequently in the language that they rarely convey information about the meaning of a particular document.

# References
* [tutorialspoint](https://www.tutorialspoint.com/gensim/gensim_creating_tf_idf_matrix.htm#:~:text=TF-IDF%20model%20computes%20tfidf%20with%20the%20help%20of,%28Inverse%20Document%20Frequency%29.%20Step%202%3A%20Normalise%20the%20Result)

* [geeksforgeeks](https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/)

* [geeksforgeeks](https://www.geeksforgeeks.org/ml-content-based-recommender-system/)
