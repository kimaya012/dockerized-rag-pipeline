# Dockerized-rag-pipeline

This is an ongoing project to build a Retrieval-Augmented Generation (RAG) pipeline that allows users to upload documents and ask questions based on their content. The system is designed for efficiency and scalability, leveraging a vector database for quick retrieval and a REST-based LLM for contextual response generation. The entire application is containerized using Docker for easy deployment.

---

## Features ✨

1. Document Ingestion: Supports uploading up to 20 documents, each with a maximum of 1000 pages.


2. Document Processing: Chunks documents into manageable sizes for efficient retrieval.


3. Vector Database: Uses text embeddings to store document chunks in a vector database.


4. RAG Pipeline: Retrieves relevant document chunks based on user queries and passes them to the LLM for contextual response generation.


5. REST API: Implemented using FastAPI, with endpoints for uploading documents, querying the system, and viewing processed document metadata.


6. Containerization: The entire application is containerized using Docker Compose for seamless deployment on local and cloud environments.

---

## Tech Stack 🛠️

1. Backend: Python, FastAPI

2. LLM API: Gemini API

3. Vector Database: ChromaDB

4. Embeddings: sentence-transformers

5. Document Processing: pypdf, langchain

6. Containerization: Docker, Docker Compose

---
