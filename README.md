# Byte-Pair Encoding (BPE) Implementation (GPT tokenizer)

This repository contains a implementation of the Byte-Pair Encoding (BPE) algorithm at the byte level, specifically designed for use in Large Language Models (LLMs). This project was inspired by and based on a tutorial by Andrej Karpathy titled "Let's build the GPT Tokenizer."

## Overview

Byte-Pair Encoding is a type of data compression technique that is also widely used for tokenizing text in natural language processing (NLP). This implementation demonstrates the building blocks of a tokenizer that operates directly on UTF-8 encoded strings, making it robust across multiple languages and special characters.

## Learning Journey

Following Andrej Karpathy's tutorial, I learned about the BPE algorithm and implemented it for some text samples. The steps included:

1. **Building a Basic Tokenizer**: Implementing core functions `train`, `encode`, and `decode`. Trained the tokenizer on various texts to visualize the merged tokens.
2. **Advancing to RegexTokenizer**: Enhancing the BasicTokenizer with a regex pattern that matches the GPT-4 tokenizer's splitting rules, ensuring no tokens go across categories like numbers, letters, and punctuation.
3. **Matching GPT-4 Tokenizer**: Attempted to replicate the encoding and decoding functionality of the GPT-4 tokenizer using `tiktoken`.

Tutorial Reference: [Let's build the GPT Tokenizer by Andrej Karpathy](https://www.youtube.com/watch?v=zduSFxRajkE&t=3527s&ab_channel=AndrejKarpathy)
