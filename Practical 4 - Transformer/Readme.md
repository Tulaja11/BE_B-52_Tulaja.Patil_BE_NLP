# Practical 4

## Problem Statement
Create a transformer from scratch using the PyTorch library.

## Objective
To implement a simple Transformer model using PyTorch and understand attention mechanism.

## Explanation
Transformer is a deep learning model used in NLP tasks such as translation, chatbot and text classification.

Transformer uses Attention Mechanism to focus on important words in a sentence.

Main components of Transformer:

1. Embedding Layer – converts words into numeric vectors
2. Multi-Head Attention – finds important words
3. Feed Forward Layer – processes information
4. Output Layer – gives final output

Transformer works faster than RNN and LSTM because it processes words in parallel.

## Methodology
1. Imported torch library
2. Created embedding layer using nn.Embedding
3. Implemented Multihead Attention using nn.MultiheadAttention
4. Added Linear layer
5. Combined layers to create transformer model
6. Generated sample input
7. Passed input through model
8. Printed output shape

## Output
Model generated output tensor successfully.

Example:
torch.Size([4, 1, 32])

## Conclusion
Transformer model was implemented successfully using PyTorch.
Attention mechanism helps model understand important words in text.
Transformer is widely used in modern NLP applications.