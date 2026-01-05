# Semantic Similarity Evaluation

This project evaluates sentence-level semantic similarity using two approaches:

- **TF-IDF** (statistical baseline)
- **Sentence-BERT** (neural sentence embeddings)

The goal is to compare their performance on a custom dataset of sentence pairs labeled as semantically similar or not similar.

## Repository Structure

- `dataset.csv`  
  Custom dataset containing sentence pairs and binary similarity labels.

- `semantic_similarity_evaluation.ipynb`  
  Google Colab notebook implementing vectorization, cosine similarity, and evaluation.

## How to Run

1. Install dependencies
2. Open the notebook and run all cells.
