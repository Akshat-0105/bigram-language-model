# Bigram Model and GPT-style Transformer (WiDS 2025)

This repository contains my **mid-term and end-term work** for **Winters in Data Science (WiDS) 2025**.  
The project progresses from a simple **Bigram Language Model** to a **decoder-only Transformer (GPT-style)** implemented from scratch using PyTorch.

---

## Repository Structure

- `bigram_model.ipynb`  
  Implements a character-level Bigram Language Model as part of the mid-term assignment.

- `gpt.ipynb`  
  Implements a decoder-only Transformer with self-attention, multi-head attention, and feed-forward layers as the end-term project.

- `images/`  
  Contains generated outputs, training curves, and architecture diagrams used in the report.

---

## Part 1: Bigram Language Model (Mid-Term)

- Character-level bigram model
- Learns next-character probabilities
- Demonstrates limitations due to lack of contextual memory
- Produces incoherent, gibberish-like text

This part establishes the motivation for more advanced architectures.

---

## Part 2: Decoder-Only Transformer (GPT) (End-Term)

- Implemented self-attention using Query, Key, and Value vectors
- Built multi-head attention, feed-forward networks, and residual connections
- Added positional embeddings for sequence order awareness
- Trained on the Tiny Shakespeare dataset
- Generated coherent English-like text using autoregressive sampling

---

## Training Details

- Dataset: Tiny Shakespeare
- Tokenization: Character-level
- Optimizer: AdamW
- Training iterations: ~5000
- Validation loss achieved: ~1.5–2.0

---

## Results

The Transformer model significantly outperforms the bigram baseline by capturing long-range dependencies and generating structured, English-like text.

Sample outputs and loss curves are available in the `images/` folder.

---

## Key Learnings

- Deep understanding of Transformer internals and self-attention
- Practical experience with tensor dimension management and debugging
- Insight into training stability, optimization, and autoregressive generation
- Hands-on exposure to the architecture behind modern large language models

---

## References

- Vaswani et al., *Attention Is All You Need*
- Andrej Karpathy, *Let’s Build GPT from Scratch*
- Jay Alammar, *The Illustrated Transformer*
- Jay Alammar, *The Illustrated GPT-2*
