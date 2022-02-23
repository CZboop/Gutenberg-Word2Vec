# Gutenberg Word2Vec

Creating word2vec embeddings/word vectors from open source book data from Project Gutenberg, using Gensim, NLTK and Python.

Currently trained on [this large dataset](https://www.kaggle.com/terminate9298/gutenberg-poetry-dataset) of over 2 million lines of poetry. Many thanks to the creator of the dataset!

To use these vectors, simply download all the .model files (including files with further file extensions after .model) or clone the repository. Use the path to the file that ends in .model when loading with Gensim or other methods of loading word2vec models (e.g. Word2Vec.load('word2vec.model') if using Gensim and the script using the model is in the same directory as the model files).
