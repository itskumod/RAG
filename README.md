# 📚 Learning RAG (Retrieval-Augmented Generation)

Welcome to my **Learning RAG** repository! 🚀

This repository documents my journey of learning **Retrieval-Augmented Generation (RAG)**, from fundamental concepts to practical implementations. My goal is to understand how RAG systems retrieve relevant information from external knowledge sources and use Large Language Models (LLMs) to generate accurate, context-aware answers.

## 🎯 Objectives

- Understand the fundamentals of RAG.
- Learn how Large Language Models (LLMs) work with external knowledge.
- Understand embeddings and vector representations.
- Implement document loading and text splitting.
- Explore vector databases and similarity search.
- Build a complete RAG pipeline.
- Learn different RAG techniques and their applications.
- Develop practical RAG-based applications.

## 🧠 What Is RAG?

**Retrieval-Augmented Generation (RAG)** is a technique that combines information retrieval with text generation.

Instead of relying only on an LLM's trained knowledge, a RAG system retrieves relevant information from an external knowledge source and provides it as context to the LLM.

### Basic RAG Workflow

```text
          Documents / Knowledge Base
                     |
                     v
              Document Loading
                     |
                     v
               Text Splitting
                     |
                     v
              Generate Embeddings
                     |
                     v
                Vector Store
                     |
                     v
User Query ---> Retrieve Relevant Chunks
                     |
                     v
              Build Context
                     |
                     v
                LLM Response
                     |
                     v
                 Final Answer
```

## 📖 Topics Covered

### 1. RAG Fundamentals
- Introduction to RAG
- Why RAG is needed
- Limitations of traditional LLMs
- RAG architecture and workflow
- Advantages and real-world applications

### 2. Large Language Models (LLMs)
- Introduction to LLMs
- Transformer architecture
- Tokens and tokenization
- Attention mechanism
- Context windows
- Prompt engineering

### 3. Embeddings
- What are embeddings?
- Text-to-vector conversion
- Embedding dimensions
- Semantic similarity
- Cosine similarity
- Dense and sparse embeddings

### 4. Document Processing
- Loading documents from different sources
- Text cleaning and preprocessing
- Document chunking
- Chunk size and overlap
- Metadata handling
- Text splitters

### 5. Vector Databases
- Vector storage and retrieval
- Similarity search
- Indexing and searching embeddings
- Metadata filtering
- Introduction to vector databases

### 6. RAG Pipeline
- Document ingestion
- Embedding generation
- Vector storage
- Query processing
- Context retrieval
- Prompt construction
- LLM response generation

### 7. Advanced RAG Techniques
- Query transformation
- Query expansion
- Hybrid search
- Reranking
- Multi-query retrieval
- Parent document retrieval
- Contextual compression
- Corrective RAG (CRAG)
- Adaptive RAG
- Agentic RAG

## 🛠️ Technologies

Technologies and tools explored in this repository include:

- **Python** — Core programming language
- **LangChain** — Building LLM and RAG applications
- **Hugging Face** — Models and embedding tools
- **Sentence Transformers** — Generating text embeddings
- **Vector Databases** — Storing and retrieving embeddings
