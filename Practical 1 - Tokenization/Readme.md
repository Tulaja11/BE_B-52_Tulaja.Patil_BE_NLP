# NLP Practical 1: Text Preprocessing 

This file contains Natural Language Processing (NLP) practical using Python and the NLTK library.

## What is in this practical?
This practical demonstrates the three most basic and important steps in NLP text processing:

### 1. Tokenization (Breaking sentences into pieces)
* **Whitespace:** Splits text by spaces.
* **Punctuation:** Splits text by punctuation marks.
* **Treebank:** The standard way to split English words.
* **Tweet:** Keeps emojis like `:-)` and hashtags like `#NLP` together.
* **MWE (Multi-Word Expression):** Trained to recognize my name `Tulaja Patil` as one single word instead of two!

### 2. Stemming (Chopping off word endings)
Stemming roughly chops the ends of words to find their base form. 
* Used **Porter Stemmer** and **Snowball Stemmer**.
* Example: It chops the word `"successfully"` down to `"success"`.

### 3. Lemmatization (Finding the real dictionary root)
Unlike stemming, Lemmatization is smart and uses a dictionary to find the proper root word.
* Example: It correctly changes `"libraries"` to `"library"`.

## Requirements
To run this code, you will need Python installed along with the NLTK library.
```bash
pip install nltk
```

## How to Run
1. Download the `Practical - 1.ipynb` file.
2. Open it using Jupyter Notebook or VS Code.
3. Run the cells one by one to see the outputs!
