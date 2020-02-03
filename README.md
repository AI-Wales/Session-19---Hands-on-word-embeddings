# Session-XX---Hands-on-word-embeddings
A practical example training word2vec embeddings using Gensim in Python.

This follows on a presetation by Jose Camacho Collados on  Word, Sense and Contextualised Embeddings: Vector Representations of Meaning in Natural Language Processing


Over the past years, word embeddings have proved to be effective and flexible keepers of prior knowledge to be integrated into downstream Natural Language Processing (NLP) applications.

In this talk we start by briefly presenting word vector space models in general, and then highlighting one of their major limitations: the meaning conflation deficiency, which arises from representing a word with all its possible meanings as a single vector (e.g. mouse can be an animal or a computer device). This deficiency can be addressed through a transition from the word level to the more fine-grained level of word senses. An overview of the wide range of techniques in the two main branches of sense representation, i.e., unsupervised and knowledge-based.

We also present some of the latest developments in this area, namely contextualised embeddings. This branch has been quickly popularised by methods like ELMo and BERT, leading to substantial improvements in NLP tasks thanks to a more dynamic modelling of meaning.

In the practical companion session we introduce how to practically train your own embeddings by using the Gensim library in Python. We focus on training word2vec on a limited text of Alice in Wonderland, and discuss several key points - the effect of preprocessing, the effect of model settings and the use of pretrained models. 
