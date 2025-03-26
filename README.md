# Product Recommendation using Transformer and Flask

## Overview
This project is an **AI-powered product recommendation system** that uses **Sentence-BERT** embeddings and **cosine similarity** to find the most relevant products based on user queries. The system features a **Flask backend** and a **Bootstrap-based frontend** for an interactive user experience.

## How It Works
1. **Preprocessing**: Cleans and combines product details into a single text column.
2. **Embedding Generation**: Uses **Sentence-BERT** to create vector representations of product descriptions.
3. **Similarity Matching**: Computes **cosine similarity** between user queries and product embeddings.
4. **Recommendation Display**: Renders the results dynamically on a Bootstrap-based UI.

## Features
- **AI-powered recommendations** with Sentence-BERT.
- **Fast and scalable** retrieval using cosine similarity.
- **User-friendly frontend** built with Bootstrap.
- **Interactive search bar** for real-time recommendations.

## Installation
```bash
pip install -r requirements.txt
