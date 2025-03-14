# Retrieval-Augmented Generation (RAG) Pipeline

## Overview
This repository contains an end-to-end **Retrieval-Augmented Generation (RAG) pipeline** leveraging **Azure OpenAI** for LLM inference, **Hugging Face embeddings** for vectorization, and **ChromaDB** for efficient knowledge retrieval. It allows for context-aware responses by retrieving relevant document chunks and enhancing LLM-generated answers.

## Features
- **Azure OpenAI GPT-4o** for high-quality text generation
- **Hugging Face Sentence Transformers** for embedding generation
- **ChromaDB** as the vector database for semantic search
- **LangChain** for conversational memory and orchestration
- **Gradio UI** for an interactive chat interface

## How It Works
1. **User Query**: The chatbot receives a question.
2. **Retriever Fetches Context**: The query is embedded and matched against stored document vectors.
3. **Azure OpenAI Generates Response**: The LLM uses the retrieved context to generate a more accurate response.
4. **Memory Maintains Context**: The conversation history is stored for multi-turn interactions.

## Future Improvements
- Implement **FAISS or Weaviate** for scalable vector retrieval.
- Optimize **query expansion** techniques for better search results.
- Enhance **prompt engineering** to refine model responses.


