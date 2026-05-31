# Disease Prediction Chatbot Using Large Language Models (LLMs)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Project Overview

This project explores the use of Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) for intelligent disease prediction and healthcare question answering.

The objective was to develop a healthcare chatbot capable of analyzing medical reports, retrieving relevant medical knowledge, and generating context-aware responses to assist users in understanding potential health conditions.

The system combines modern LLM technology with medical document retrieval techniques to improve response quality and reduce hallucinations.

---

## Key Features

- Medical report analysis
- Disease prediction assistance
- Retrieval-Augmented Generation (RAG)
- Vector database-based document retrieval
- Context-aware healthcare chatbot
- Prompt engineering for improved medical responses
- Evaluation of different embedding and language models

---

## Technologies Used

### Programming & Frameworks
- Python
- Jupyter Notebook
- LlamaIndex

### Large Language Models
- BioMistral-7B
- Meditron-7B (evaluated)

### Embedding Models
- PubMedBERT
- BGE Embeddings

### Vector Database
- Chroma DB

### Supporting Libraries
- Hugging Face Transformers
- Sentence Transformers
- PyTorch

---

## System Architecture

The chatbot follows a Retrieval-Augmented Generation (RAG) pipeline:

1. Medical documents are processed and embedded.
2. Embeddings are stored in a vector database.
3. User queries are converted into embeddings.
4. Relevant medical information is retrieved.
5. The retrieved context is supplied to the LLM.
6. The model generates a context-aware response.

---

## Project Workflow

### Data Processing
- Medical reports collected and prepared
- Text cleaning and preprocessing
- Document chunking

### Knowledge Retrieval
- Vector embeddings generated
- Chroma DB used for document storage
- Similarity-based retrieval

### Response Generation
- Retrieved medical context passed to the LLM
- Prompt engineering applied
- Response generated with supporting context

### Evaluation
- Embedding model comparison
- LLM comparison
- Human evaluation of generated responses

---


## Files Included

### report.pdf
Contains the complete project documentation, methodology, architecture, experiments, evaluation results, and conclusions.

### prototype_notes.ipynb
Available prototype notebook demonstrating the early implementation and experimentation phase of the project.

---

## Results

The project demonstrated that combining Retrieval-Augmented Generation with domain-specific medical language models can significantly improve the quality and relevance of healthcare-related responses.

Key findings include:

- Improved response accuracy using RAG
- Better medical understanding using BioMistral-7B
- Enhanced retrieval performance with PubMed-based embeddings
- Reduced hallucination compared to standalone LLM responses

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Vector Databases
- Medical NLP
- Embedding Models
- Prompt Engineering
- Healthcare AI Applications
- Model Evaluation and Comparison

---

## Disclaimer

This project is intended for educational and research purposes only.

The chatbot does not provide professional medical advice and should not be used for diagnosis or treatment decisions.

---
