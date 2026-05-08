Agentic AI  
Phase 1: Semantic Search Module

Objective
The goal of this assignment is to build the **memory system** of an AI Research Assistant.
You will design a **semantic search engine** that retrieves academic documents based on
meaning rather than keywords.

This phase focuses on:
- Document embeddings
- Vector databases
- Semantic retrieval
- Retrieval quality analysis

##  Tasks Overview
### Task 1: GUI-Based Data Selection
Your GUI must allow the user to:
- Upload or select a dataset (minimum 10–15 text documents)
- View dataset statistics (number of documents, size)
- No dataset should be hard-coded in the backend

### Task 2: Embedding & Vector Store Configuration
The GUI must allow the user to select:
- A Hugging Face embedding model
- A vector database (FAISS or Chroma)

Based on these selections:
- Generate embeddings
- Store them using LangChain

### Task 3: Semantic Retrieval
Your application must provide:
- A query input box
- A configurable `top-k` value
- Clearly ordered retrieval results based on relevance

### Task 4: Retrieval Evaluation & Analysis
Test your system with:
- Multiple queries
- Different datasets
- Different embedding models

Analyze and document the quality of retrieval results.

## EXECUTION
 - cd (FOLDER PATH)
   
 - python -m venv venv
   
 - venv\Scripts\activate.bat
   
 - python -m pip install --upgrade pip
   
 - pip install langchain langchain-community langchain-huggingface faiss-cpu chromadb sentence-transformers numpy pandas
   
 - python app/main.py
