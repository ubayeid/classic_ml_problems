# Classic ML Problems

This repository contains small machine learning practice projects.

## Included Project

### Sentiment Analysis (IMDB)
- Notebook: `sentiment_analysis/sentiment_classification.ipynb`
- Task: Binary sentiment classification (`positive=1`, `negative=0`)
- Models: Simple RNN and LSTM
- Metric: Test accuracy

## Quick Start

1. Open `sentiment_analysis/sentiment_classification.ipynb`.
2. Install dependency in the first cell (`datasets`) if needed.
3. Run all cells in order.

## Environment

- Python 3.9+
- PyTorch
- Hugging Face `datasets`
- NumPy

## Current Notebook Results

From the latest saved outputs:
- RNN Test Accuracy: **53.71%**
- LSTM Test Accuracy: **65.14%**

LSTM performs better than the simple RNN baseline in this setup.