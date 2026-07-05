# AI-Research-Paper-Intelligence-System
AI-powered research paper intelligence system with semantic search, classification, clustering, summarization, keyword extraction, NER, and transformer-based question answering.

An end-to-end Machine Learning and Natural Language Processing (NLP) project that transforms arXiv research papers into an intelligent research assistant. The system enables semantic search, document clustering, research paper classification, keyword extraction, named entity recognition, abstractive summarization, and transformer-based question answering using state-of-the-art NLP models.

Features
Semantic Search using Sentence Transformers and FAISS
Research Paper Classification using SGD Classifier
Document Clustering using K-Means
PCA Visualization of Research Paper Embeddings
Named Entity Recognition (NER) using SpaCy
Keyword Extraction using KeyBERT
Research Paper Summarization using BART
Transformer-based Question Answering using DistilBERT

Tech Stack
Programming Language: Python Libraries: Pandas, NumPy, Scikit-learn, Matplotlib Machine Learning: PCA, K-Means, SGD Classifier NLP: SpaCy, KeyBERT Embeddings & Search: Sentence Transformers, FAISS Transformer Models: BART, DistilBERT (Hugging Face) Dataset

This project uses the arXiv Scientific Research Papers Dataset from Kaggle. The original dataset contains over 250,000 research papers, while this project processes approximately 20,000 papers to ensure efficient experimentation and model execution.

After downloading the dataset, place the CSV file in the project directory before running the notebook. Link for the dataset:- https://www.kaggle.com/datasets/sumitm004/arxiv-scientific-research-papers-dataset?resource=download

Models Used
Model	Purpose
all-MiniLM-L6-v2	Semantic Embedding Generation
facebook/bart-large-cnn	Research Paper Summarization
distilbert-base-cased-distilled-squad	Question Answering
