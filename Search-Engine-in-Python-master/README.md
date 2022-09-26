Search-Engine-in-Python

Python's NLTK library should be installed.
Python's Numpy library should be installed.
Python's PyEnchant library should be installed.
Python's Tkinter library should be installed.
WordNet should be downloaded from nltk.corpus.

The folder named "corpus" should contain all the text documents to be searched.

The program can be executed in two modes:
1. Using retrieval.py execution (command line interface)
2. Using gui.py execution (graphic user interface). GUI supports hyperlink feature for opening result documents.

# DESCRIPTION
**OVERVIEW**
The search engine employs vector space model for query searching in a text corpus, which uses proximity searching of query vector with individual document vectors to rank the documents according to relevance. The weight vectors formulated for this purpose use combination of term frequency and inverse document frequency scores. The proximity searching technique used is cosine similarity. The pre-processing of text in documents as well as the query is done using various Python libraries. The pre-processing includes tokenization, normalization and stemming of words. Spellchecking has also been employed for query input words. Synonym search is yet another feature employed by the application. Finally, a GUI interface has been created for the application for ease of searching.

