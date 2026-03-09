->AI Document Q&A Assistant using RAG

This project implements a Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions about them.

-> Architecture

PDF Upload
↓
Text Extraction (PyPDF2)
↓
Text Chunking
↓
Embeddings (HuggingFace)
↓
Vector Database (FAISS)
↓
Similarity Search
↓
LLM Response (Gemini)

-> Tech Stack

Python
Streamlit
LangChain
FAISS
HuggingFace Embeddings
Google Gemini API

->Features

Upload multiple PDFs
Generate embeddings
Vector similarity search
Context-aware AI responses

-> Run the Project

pip install -r requirements.txt  
streamlit run app.py
