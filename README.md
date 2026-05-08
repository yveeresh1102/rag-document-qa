# RAG-based Document Q&A System

A Retrieval-Augmented Generation (RAG) pipeline for answering questions from custom PDF documents using semantic search and LLM-based response generation.

## Features
- PDF document parsing
- Text chunking
- Semantic search using embeddings
- ChromaDB vector storage
- Retrieval-based context generation
- AI-powered question answering

## Tech Stack
- Python
- LangChain
- ChromaDB
- HuggingFace Transformers
- Sentence Transformers

## Architecture
PDF → Chunking → Embeddings → ChromaDB → Retrieval → LLM → Answer

## Use Case
Allows users to query custom documents and receive context-aware responses using Generative AI techniques.

## Future Improvements
- Streamlit UI
- Multi-document support
- Chat memory
- Local LLM integration
