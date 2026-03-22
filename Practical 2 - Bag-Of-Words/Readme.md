# NLP Practical 2: Feature Extraction and Embeddings

## Problem Statement
Perform the bag-of-words approach (count occurrence, normalized count occurrence) and TF-IDF on text data. Create word embeddings using Word2Vec. The dataset to be used is the CooperUnion car dataset.

## Explanation
This practical demonstrates how to convert text data into numbers so a computer can understand it. 
1. **Data Preparation:** The 'Make' and 'Model' columns from the car dataset were combined to create short text sentences. A small sample of 3 rows was used to keep the output matrices clean and easy to understand.
2. **Bag of Words (Count Occurrence):** Used `CountVectorizer` to create a vocabulary and count exactly how many times each word appeared in the text.
3. **Normalized Count:** Used L1 normalization to convert the raw word counts into fractions/percentages, which makes it fair to compare sentences of different lengths.
4. **TF-IDF:** Used `TfidfVectorizer` to find the importance of words. It gives a lower score to common words and a higher score to unique words.
5. **Word2Vec:** Used the `gensim` library to train a Word2Vec model. Instead of just counting, this neural network approach converted words (like 'BMW') into numerical coordinates (vectors).

## Conclusion
We can conclude that there are multiple ways to represent text mathematically. Bag of Words and TF-IDF are great for basic counting and finding important words, but they ignore the actual meaning of the words. On the other hand, Word2Vec is a much more advanced technique that captures the semantic meaning of words by placing them into a mathematical vector space.
