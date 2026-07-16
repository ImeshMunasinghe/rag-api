# AI DevOps RAG API

A local Retrieval-Augmented Generation (RAG) API built with FastAPI, ChromaDB, and Ollama. This API allows users to query an AI model grounded in custom local text documents using semantic search.

## Features
- **Local AI Pipeline:** Powered by Ollama (`qwen2.5:0.5b` for generation and `nomic-embed-text` for embeddings).
- **Vector Storage:** Semantic search and context retrieval managed via ChromaDB.
- **REST API:** Fast and interactive endpoints built using FastAPI.

## Tech Stack
- Python
- FastAPI & Uvicorn
- ChromaDB
- Ollama

## Setup Instructions
1. Clone the repository.
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate