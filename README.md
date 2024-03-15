# Gensim NLP

This project explores a subset of Amazon reviews from the Cell Phones & Accessories category. The goal is to train a Word2Vec model using Gensim for analyzing and understanding the text data.

## Dataset
The dataset can be downloaded from the following link:
[Amazon Reviews Dataset](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Cell_Phones_and_Accessories_5.json.gz)

## Preprocessing
- Convert all words to lowercase.
- Remove extra spaces and punctuation.
- Remove stopwords like 'and', 'or', 'is', 'the', 'a', 'an'.
- Transform words to their base forms using lemmatization.

## Training the Word2Vec Model
- Use a window size of 10 (10 words before and after the present word).
- Set a minimum count of 2 (consider only sentences with at least 2 words).
- Use 4 CPU threads for training the model.

## Results
- The trained Word2Vec model can be used to find similar words and calculate similarity between words.
- The model is saved as `word2vec-amazon-cell-accessories-reviews-short.model`.

## Resources
- [Gensim Documentation](https://radimrehurek.com/gensim/models/word2vec.html)

## Conclusion
This project demonstrates how to preprocess text data and train a Word2Vec model for analyzing Amazon reviews in the Cell Phones & Accessories category.
