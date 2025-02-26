# Vision Transformer (ViT) Implementation from Scratch

This repository contains my implementation of the **Vision Transformer (ViT)**, developed as part of a university seminar. The implementation is entirely from scratch, inspired by the original [ViT paper](https://arxiv.org/abs/2010.11929), with the constraint that `torch.nn` (or any high-level deep learning framework) could not be used.

## Overview

- **Objective**: Implement a Vision Transformer from scratch without using high-level libraries like `torch.nn`.
- **Dataset**: The model was trained on a subset of CIFAR-100 (details provided in the notebook). Due to size constraints, the dataset is not included in this repository.
- **Performance**: While the model's performance is not competitive with state-of-the-art results (due to limited training data and compute resources), it was one of the best-performing models within the seminar. The implementation demonstrates the potential for scaling with more data and compute, which is where transformer models truly shine.

## Repository Contents

- **Notebook**: The notebook contains:
  - Details about the dataset.
  - A step-by-step breakdown of the Vision Transformer architecture.
  - Training and evaluation procedures.
- **Code**: A fully from-scratch implementation of the Vision Transformer, including:
  - Multi-head self-attention.
  - Positional embeddings. (Including a deep dive into RoPE)
  - Transformer encoder blocks.
  - Classification head.
- **Results**: Insights into the model's performance and limitations.

## Key Takeaways

- This project was a great learning experience in understanding the inner workings of transformer architectures.
- While the current performance is modest, the architecture is designed to scale with more data and compute.

## How to Use

Since the dataset is not included in this repository, the notebook cannot be run directly. However, the notebook provides a detailed walkthrough of the implementation, architecture, and training process. If you're interested in the technical details or want to adapt the code for your own dataset, feel free to explore!
