Graph-based Approach for Studying Spread of Radical Online Sentiment
Le Nguyen
ln8378@g.rit.edu
12/9/2022

This repository contains the clean data set "Ansar1Clean.csv" and jupyter notebook "InterThreadAnalysis.ipynb" to create a sample output for our current work. "InterThreadAnalysis.ipynb" will take in "Ansar1Clean.csv" and create a sentiment graph from the data as well as take some statistics from said graph.

"Ansar1Clean.csv" is a cleaned version of the Ansar1 data set which can be found here: https://www.azsecure-data.org/dark-web-forums.html. The csv contains comments from many online dark web forums pertaining to radical islam.

To run "InterThreadAnalysis.ipynb" simply run the cells inside of the jupyter notebook.

Make sure to have jupyter installed as well as the following packages:
numpy 
matplotlib
networkx
pandas
nltk
spacy
ssl