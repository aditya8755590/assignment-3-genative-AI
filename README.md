# 📚 RAG Pipeline with LangChain, Ollama & FAISS

This project demonstrates a complete **Retrieval-Augmented Generation (RAG)** system built locally using:

- 🧠 Ollama LLMs (Mistral for generation, Nomic for embeddings)
- 🛠️ LangChain for pipeline orchestration
- 📂 FAISS for vector-based document retrieval
- 📄 Custom PDF file (Atomic Habits) as source knowledge

---

## 🔧 Tech Stack

| Component    | Tool                         |
|--------------|------------------------------|
| LLM          | Ollama (Mistral)             |
| Embeddings   | Ollama (nomic-embed-text)    |
| Vector DB    | FAISS                        |
| Framework    | LangChain                    |
| Interface    | Jupyter Notebook (.ipynb)    |

---

## 📌 Features

- Load and chunk a PDF using LangChain
- Generate vector embeddings using local Ollama
- Store embeddings in FAISS
- Query using natural language with local LLM (RAG)
- Custom prompt tuning for better responses

---

## 🧪 Sample Questions Asked

1. How does James Clear explain habit stacking?  
2. What is the role of identity in building habits?  
3. What are the four laws of behavior change?  
4. How can environment affect your habits?  
5. Give examples of how to break bad habits from the book.  

---

## 🚀 Getting Started

1. **Install [Ollama](https://ollama.com)**
2. Pull required models:

   ```bash
   ollama pull nomic-embed-text
   ollama pull mistral
