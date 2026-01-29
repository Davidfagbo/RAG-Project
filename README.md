# Retrieval-Augmented Generation (RAG) with PDFs

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using **LangChain**, **OpenAI embeddings**, and **FAISS** to query information from a PDF document.

The system loads a PDF file, splits it into chunks, embeds the content, stores it in a vector database, and allows natural language questions to be answered using an LLM with document context.

---

## Features

- Load and process PDF documents
- Split text into manageable chunks
- Generate embeddings using OpenAI
- Store and search embeddings with FAISS
- Query documents using a chat-based LLM
- Simple and extensible RAG workflow


---

## Installation

Install the required dependencies:

```bash
pip install pypdf openai
pip install langchain langchain-openai
pip install langchain-community langchain-text-splitters
pip install faiss-cpu
pip install -U langchain-xai
```

