# Building GPT From Scratch

A simple GPT implementation following Andrej Karpathy's ["Let's build GPT from scratch"](https://www.youtube.com/watch?v=kCc8FmEb1nY) tutorial.

## Overview

This project implements a basic character-level language model that can generate Shakespeare-like text. It includes two versions:

- `biagram.py`: Simple bigram model
- `v2.py`: Enhanced version with position embeddings

## Requirements

```bash
python3 -m pip install torch
```

## Usage

Train and generate text with either model:

```bash
python biagram.py  # Basic model
# or
python v2.py      # Enhanced model
```

## Project Structure

```
.
├── biagram.py    # Basic model
├── v2.py        # Enhanced model
├── input.txt    # Shakespeare training data
└── README.md    # This file
```

## Acknowledgments

- Andrej Karpathy for the tutorial
- The PyTorch team
