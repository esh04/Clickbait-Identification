# Clickbait-Identification
In this project we have compared the properties of Clickbait titles vs Non-Clickbait titles. We have then classified the data using simple classifier models such as SVMs, Logistic Regression and XGBoost. </br>
The project is done in Hindi. Created for the course project of the Spring '21 Course - Computational Linguistics -1.

## Tasks
1. Preprocess the dataset
2. Analysis of data
3. Plotting graphs of all the analysis.
4. Making word clouds for the different name entities present.
5. Comparing the list of entities present in Clickbait vs Non-Clickbait
  
## Analysis
Analysis is done on the basis of-
1. Number of tokens
2. Presence of Question mark
3. Presence of Exclamation mark
4. Presence of quotations
5. Number of stopwords
6. Presence of numerals
7. The entities present
8. POS tags

In Clickbait.ipynb all the above analysis have been made for Clickbait vs Non-Clickbait sentences. 

## Classifying Data
Classifier.ipynb contains the scaled version of data generated and code to make predictions on the test dataset. We use >70% of the training data for training the models and the rest to verify the accuracy of the models. 

## Dataset Used
  Dataset containing 41800 Hindi sentences labelled either 0(Non-Clickbait) or 1(Clickbait).
  
## Tools used
We have used 
  - `pandas` to analyse data 
  - `re` to clean the data
  - `NLTK` to tokenize
  - a custom stopword file (stopword.txt) to identify stopwords
  - `polyglot` library for NER
  - `wordcloud` python package and `mathplotlib.pyplot` to make wordclouds
  - `stanza` to POS tag
  - `mathplotlib` and `seaborn` have been used to make the graphs.
  
## Results
### Classifier 1: Logistic Regression
Highest accuracy achieved was:
### Classifier 2: SVMs
Highest accuracy achieved was:
### Classifier 3: XGBoost
Highest accuracy achieved was:
##
The report.pdf contains the analysis of the graphs obtained in the process and some other observations.
