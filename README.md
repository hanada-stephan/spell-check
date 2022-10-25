# Spell-check: Project overview ALTERAR

**Tags: NLP, bag of words, EDA, probability, spell-check**  

This notebook is based on Alura's course [Corretor Ortográfico em Python: aplicando técnicas de NLP (Spell-check with Python: applying NLP techniques)](https://cursos.alura.com.br/course/nlp-corretor-ortografico). Here you will find EDA and cleaning data, spell-check using probability capable of correcting four major mistype problems, and the model evaluation. The main steps were:

- EDA to understand the data;
- removed punctuations;
- unique word count and sorted the most frequent terms in the corpus;
- created a spell-check to correct missing, extra, inverted, and replaced letters problems;
- created a probability function to pick the right word among all the terms generated;
- Used a test set to evaluate the model's performance.

## Code and resources

Platform: Jupyter Notebook

Python version: 3.7.6

Packages: itertools, NLTK

## Data set

The data set has two files:
- **artigos.txt** which is a collection of Alura's blog articles;
- **palavras.txt** is the test set with the correct words and their mistyped terms.

## Model building

- Built a probabilistic model, i.e., the word frequency over all the words in the corpus, to choose the correct word among all the terms generated.

## Model performance

- The spell-check model can correct 76% among about 200 words from the test set.
