# Cross-lingual-Reverse-Dictionary

Implemented a Cross-lingual Reverse Dictionary i.e, reverse dictionary NLP model,
given a brief description of some objects in English, can provide synonyms in German.

E0 334 - Deep Learning for NLP
Assignment 6
Problem: The aim of this assignment is to design a neural approach which finds a word in
a target language given a rough definition or description of the target word in the source language.
For example, for the English language input “a road where cars go quickly and without stopping”
the system would output a word in the German language as “Schnellstrasse”.


In this assignment, you will first design a reverse dictionary [1, 2] for English language
using any of the models discussed in the class. A reverse dictionary finds a word given its rough
description. The dictionary file “EnglishDictionary.csv” can be used for training your Reverse
Dictionary model. One can then use the parallel bilingual corpus (English-German, “EN-DE.txt”)
to learn word-alignment and build a English-German dictionary [3, 4, 5, 6]. These two systems can
then be combined to achieve the desired objective.
The details about the metric for performance evaluation of your approach and the link for
submission will be provided later.

Some References:
1. Qi et al, WantWords: An open-source Online Reverse Dictionary System (available at
https://aclanthology.org/2020.emnlp-demos.23.pdf)
2. Yan et al, BERT for Monolingual and Cross-lingual Reverse Dictionary (available at
https://arxiv.org/pdf/2009.14790)
3. Using GIZA++ to Obtain Word Alignment Between Bilingual Sentences (Source - https:
//masatohagiwara.net/using-giza-to-obtain-word-alignment-between-bilingual-sentences.
html)
4. Alignment Scripts (Source - https://github.com/lilt/alignment-scripts)
5. Zenkel et al, End-to-end Neural Word Alignment Outperforms GIZA++ (Available at
https://aclanthology.org/2020.acl-main.146.pdf)
6. Garg et al, Jointly Learning to Align and Translate using Transformer Models (Available
at https://arxiv.org/pdf/1909.02074.pdf)
