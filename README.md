# Movie RAG — Semantic Search & Retrieval-Augmented Generation

A Python project exploring semantic search and Retrieval-Augmented Generation (RAG) using an IMDb movie dataset.

## Project Overview

The goal is to build a movie knowledge assistant capable of retrieving relevant movie information and generating answers grounded in the retrieved documents.

## Current Implementation

- IMDb dataset preparation (999 movies)
- Document construction using movie descriptions and metadata
- Semantic embeddings using Sentence Transformers (`all-MiniLM-L6-v2`)
- Vector indexing and similarity search using FAISS
- Cosine similarity through L2-normalized embeddings and inner product search

## Planned Features

- LLM integration for retrieval-augmented generation
- Retrieval evaluation using Recall@K and other ranking metrics
- Groundedness evaluation
- Comparison of retrieval strategies

## Technologies

Python, Pandas, Sentence Transformers, FAISS, Jupyter Notebook

## Status

Work in progress — semantic retrieval implemented; LLM integration and evaluation pending.
