# Gemini API Educational Project

This repository contains a collection of educational notebooks demonstrating various applications of the Gemini API, including embeddings, similarity scoring, document Q&A with RAG, and text classification.

## Notebooks Overview

### 1. Embeddings and Similarity Scores
[`embedding_and_similarity.ipynb`](embedding_and_similarity.ipynb)  
Demonstrates how to use the Gemini API's embedding endpoint to calculate and visualize similarity scores between text samples. Key features:
- Text embedding generation
- Cosine similarity calculation
- Heatmap visualization of similarity scores

### 2. Document Q&A with RAG using Chroma
[`Q&A_with_GeminiAPI.ipynb`](Q&A_with_GeminiAPI.ipynb)  
Implements a Retrieval-Augmented Generation (RAG) system using ChromaDB and the Gemini API. Key features:
- Vector database creation
- Document retrieval
- Context-aware answer generation
- Hands-on example with technical documentation

### 3. Classifying Embeddings with Keras
[`Text-Classification-with-Gemini-Api.ipynb`](Text-Classification-with-Gemini-Api.ipynb)  
Shows how to use Gemini-generated embeddings as input features for a Keras classification model. Key features:
- Newsgroup text classification
- Embedding-based model architecture
- Custom prediction pipeline
- Performance evaluation

## Setup Instructions

### Prerequisites
- Python 3.9+
- Google Gemini API key (get one from [AI Studio](https://aistudio.google.com/app/apikey))
- Required Python packages (install via `pip install -r requirements.txt`)

