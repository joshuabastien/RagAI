# README

This AI repo builds and queries using langchain and Retrieval-Augmented Generation (https://blogs.nvidia.com/blog/what-is-retrieval-augmented-generation/) using PDFs. It loads PDF files, splits them into chunks, generates embeddings with the Ollama LLaMA model, and stores them in Chroma. You can query the stored data for relevant information.

## Files

- **`get_embedding_function.py`**: Generates text embeddings using the Ollama LLaMA model.
- **`populate_database.py`**: Loads, splits, and stores PDF documents in Chroma.
- **`query_data.py`**: Queries the stored documents and retrieves relevant information using the LLaMA model.

## Usage

1. **Indexing**: Place PDFs in `dataset`, then run `populate_database.py` with Ollama server running.
2. **Querying**: Set your question in `query_data.py`, then run the script.
