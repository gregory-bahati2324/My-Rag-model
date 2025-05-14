# RAG Model Implementation Project


## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Setup](#project-setup)
  

## Project Overview

This project provides a complete implementation of a Retrieval-Augmented Generation (RAG) model, designed to help developers:
- Process and query document collections
- Implement advanced NLP workflows
- Build knowledge-based question answering systems

## Features

- Document ingestion (PDF support included)
- Vector embedding generation
- Semantic search capabilities
- Integration with DeepSeek API
- Flask-based web interface
- Environment variable configuration

## Prerequisites

- Python 3.7+
- pip package manager
- DeepSeek API account (or other LLM provider)
- Basic understanding of RAG architectures

## Installation

1. **Create and activate virtual environment**:
   ```bash
   python -m venv rag_env
   source rag_env/bin/activate  # Linux/MacOS
   # or
   rag_env\Scripts\activate  # Windows
   pip install chromadb langchain-community python-dotenv flask langchain pypdf2

## Project setup
```bash
my-rag-model/
├── data/               # Your document storage               
├── .env                # Environment variables
├── template/index.html # your html file here
├── static/style.css     #your style file here       
├── fill_db.py           # file to create your chroma vector database
└── app3.py             # Main application
```
Never commit your .env file to version control.

Ensure your API key has sufficient credits.

For production, use proper secret management.

