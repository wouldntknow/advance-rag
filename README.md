# Retrieval-Augmented Generation (RAG) System

## Overview
A Retrieval-Augmented Generation (RAG) based question answering system built using LangChain, ChromaDB, and Google Gemini embeddings.  
The project demonstrates semantic search, vector storage, and context-aware response generation using LLM workflows.

---

## Features
- Vector embeddings using Google Gemini embedding models
- Semantic similarity search
- ChromaDB vector database integration
- Context retrieval pipeline using LangChain
- LLM-based response generation
- Retrieval-based question answering workflow

---

## Technologies Used
- Python
- LangChain
- ChromaDB
- Google Gemini API
- Google Colab

---

## Project Workflow
1. Generate embeddings for documents
2. Store embeddings in ChromaDB vector database
3. Perform semantic similarity search
4. Retrieve relevant context
5. Generate responses using LLMs

---


```Installing Dependencies 
pip install -U google-generativeai
pip install -U langchain-chroma
pip install -U langchain-google-genai
```
Usage

Run the notebook or Python script in Google Colab or a local Python environment after configuring your API key.

## Future Improvements
Add Streamlit or Chainlit interface
Support PDF/document uploads
Improve retrieval accuracy
Add chat memory and conversation history
