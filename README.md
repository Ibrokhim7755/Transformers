# 1. Introduction to Transformers

Transformers are a type of deep learning model architecture that have become the foundation for many state-of-the-art models in natural language processing (NLP). Introduced in the paper "Attention is All You Need" by Vaswani et al. in 2017, transformers rely heavily on a mechanism called "self-attention".

Key Components:

1. **Self-Attention Mechanism:** Allows the model to weigh the importance of different words in a sentence.
   
3. **Positional Encoding:** Since transformers don't have a built-in sense of order like RNNs, positional encodings are added to the input embeddings to retain the order of words.
   
5. **Encoder-Decoder Architecture:** Typically used for sequence-to-sequence tasks, where the encoder processes the input sequence and the decoder generates the output sequence.

# Transformer Architecture
**Encoder:**

Input Embedding: Converts words into vectors.
Positional Encoding: Adds information about the position of each word.
Stack of Encoder Layers: Each layer has:
Multi-Head Self-Attention
Feed-Forward Neural Network
Layer Normalization
Decoder:
Similar structure to the encoder but with an additional mechanism to attend to the encoder’s output.
