# MiniGPT

A minimal GPT-style Transformer language model built from scratch using PyTorch.

This project was created to understand how autoregressive Transformer architectures work internally by implementing the core mechanics manually rather than relying on high-level APIs.

---

# Features

## Implemented

- Character-level tokenizer
- Token embeddings
- Positional embeddings
- Causal self-attention
- Multi-head attention
- FeedForward layers
- Residual connections
- Layer normalization
- Stacked Transformer blocks
- Autoregressive text generation
- GPU training with CUDA
- Tiny Shakespeare dataset training

---

# Architecture

Input Tokens
→ Token Embeddings
→ Positional Embeddings
→ Transformer Blocks
    → Multi-Head Attention
    → FeedForward Networks
    → Residual Connections
    → LayerNorm
→ Language Modeling Head
→ Next Token Prediction

---

# Current Results

The model now generates:
- pseudo-language structure
- dialogue formatting
- word-like continuity
- sentence rhythm
- long-range formatting consistency

Example generated output:

RICHAS:
Till to priche sir: hell to to feathese!

HAEDWIM:
Fard I muke I now salloud thund a bame wee jut

Although semantically incoherent, the model demonstrates emergent structural language behavior from a minimal Transformer implementation.

---

# Why This Exists

Most beginner LLM projects wrap existing APIs.

This project focuses on:
- implementing Transformer mechanics manually
- understanding how attention changes representation flow
- studying autoregressive generation behavior
- observing language structure emergence through architecture evolution

The goal is educational depth and systems understanding rather than model scale.

---

# Upcoming

- Attention visualization
- Larger context windows
- Improved tokenization
- Deeper Transformer stacks
- Dropout regularization
- Sampling improvements
- Transformer interpretability experiments
- Attention drift analysis under corrupted inputs

---

# Repository Goal

Build a progressively more complete Transformer implementation while studying:
- representation emergence
- attention behavior
- generation failure modes
- structural language formation
- internal Transformer dynamics
