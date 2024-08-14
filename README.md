# README

This repo builds and queries a document search engine using PDFs. It loads PDF files, splits them into chunks, generates embeddings with the Ollama LLaMA model, and stores them in Chroma. You can query the stored data for relevant information.

## Files

- **`get_embedding_function.py`**: Generates text embeddings using the Ollama LLaMA model.
- **`indexing.py`**: Loads, splits, and stores PDF documents in Chroma.
- **`querying.py`**: Queries the stored documents and retrieves relevant information using the LLaMA model.

## Usage

1. **Indexing**: Place PDFs in `dataset`, then run `indexing.py`.
2. **Querying**: Set your question in `querying.py`, then run the script.

## Requirements

- Python 3.8+
- Install dependencies:
  ```bash
  pip install -r requirements.txt
