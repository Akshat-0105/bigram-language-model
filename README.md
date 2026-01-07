# bigram-language-model

## Overview
This project implements a character-level Bigram Language Model based on Andrej Karpathy’s “Let’s build GPT from scratch” tutorial.

The model predicts the next character using only the current character, without any long-term memory.

## Dataset
The Tiny Shakespeare dataset is used, downloaded directly from Karpathy’s GitHub repository.

## Model Details
- Bigram language model
- Character-level tokenization
- Context size: 1
- Loss: Cross-Entropy
- Optimizer: AdamW

## Results
The generated text appears as broken and incoherent English, which demonstrates that the model has learned character-to-character probabilities but lacks long-term structure.

A screenshot of the generated output is included.

## Files
- `bigram_model.ipynb`: Complete implementation and training code
- `output.png`: Screenshot of generated gibberish text
