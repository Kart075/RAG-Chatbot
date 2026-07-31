# 🤖 RAG Chatbot | LangChain + OpenAI + FastAPI + Streamlit

## 📌 Overview
This project is a **Retrieval-Augmented Generation (RAG) Chatbot** built with:
- **LangChain** for orchestrating retrieval + generation
- **ChromaDB** as a vector store
- **FastAPI** for backend APIs (chat, doc upload, list, delete)
- **SQLite** for logging + document metadata
- **Streamlit** frontend for user interaction

It allows users to:
1. Upload documents (PDF, DOCX).
2. Index them into **ChromaDB** with embeddings from **OpenAI**.
3. Query with natural language, where answers are grounded in uploaded content.
4. Maintain **chat history** and **document store** with persistence.

---

## 🛠️ Tech Stack
- **Backend:** FastAPI, SQLite3  
- **Vector Store:** ChromaDB  
- **LLM & Embeddings:** OpenAI API (via LangChain)  
- **Frontend:** Streamlit  
- **Database:** SQLite for logs + doc metadata  
- **Deployment Ready:** Modular architecture for Docker/K8s  

---

## ✨ Features
- 📂 **Document Uploading** – Supports `.pdf`, `.docx`  
- 🔍 **Vector Search** – Retrieves relevant chunks using **Chroma** retriever  
- 💬 **Chat Endpoint** – Grounded Q&A with chat history  
- 🗄️ **Persistence** – Logs queries, responses, and documents in SQLite  
- ⚡ **FastAPI Endpoints**:
  - `/chat` → Ask a question  
  - `/upload-doc` → Upload + index documents  
  - `/list-docs` → List uploaded documents  
  - `/delete-doc` → Delete document by `file_id`  

---

