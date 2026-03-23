# Practical 3

## Problem Statement
Perform text cleaning, perform lemmatization (any method), remove stop words (any method), label encoding. Create representations using TF-IDF. Save outputs.

Dataset: News_dataset.pickle

## Objective
To preprocess text data by cleaning the text, removing stopwords, applying lemmatization, encoding labels into numeric form, and generating TF-IDF representation.

## Explanation
Text preprocessing is an important step in NLP.

Raw text contains punctuation, numbers, and common words (stopwords) that are not useful for analysis.

Lemmatization converts words into base form.
Example:
running → run
cars → car

Stopwords are common words such as "is", "the", "and".

Label Encoding converts category text into numbers.

TF-IDF (Term Frequency – Inverse Document Frequency) converts text into numerical vectors based on importance of words in dataset.

## Methodology
1. Loaded dataset using pickle file
2. Selected Content column as text data
3. Converted text into lowercase
4. Removed punctuation and numbers
5. Removed stopwords using NLTK
6. Applied lemmatization using WordNetLemmatizer
7. Converted Category column into numeric values using LabelEncoder
8. Applied TF-IDF vectorization
9. Saved outputs

## Output
TF-IDF matrix generated successfully

Example:
TF-IDF shape: (number_of_samples, number_of_features)

Labels converted into numeric values.

## Conclusion
Text data was successfully cleaned and converted into numerical representation using TF-IDF.
Processed data can be used for machine learning models.