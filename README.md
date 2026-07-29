# Multimodal RAG System for PDF Question Answering

## Overview

A multimodal Retrieval-Augmented Generation (RAG) system that enables users to ask questions about PDF documents by retrieving relevant text, tables, and images, then generating answers using an LLM.

The system processes complex documents and combines vector search with Gemini LLM to provide context-aware responses.

---

## Features

- Extracts text, tables, and images from PDF documents.
- Creates separate vector databases for text and image embeddings.
- Uses semantic search to retrieve relevant document information.
- Supports multimodal retrieval from text and images.
- Generates answers using Google Gemini LLM.

---

## Workflow

```
PDF Document
      |
      v
Document Parsing
      |
      v
Text / Tables / Images Extraction
      |
      v
Embedding Generation
      |
      v
ChromaDB Vector Storage
      |
      v
Semantic Retrieval
      |
      v
Gemini LLM Response Generation
```

---

## Technologies Used

- Python
- LangChain
- Google Gemini LLM
- ChromaDB
- Sentence Transformers
- OpenCLIP
- Unstructured PDF Processing

---

## Example Use Case

Upload a research paper or technical document and ask questions about its content.

The system retrieves relevant sections, tables, and images, then generates an answer based on the retrieved context.

---

## Future Improvements

- Add support for more document formats.
- Build a web interface for interactive querying.
- Improve image-text fusion for better multimodal reasoning.
