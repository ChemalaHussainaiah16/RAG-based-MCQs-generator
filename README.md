# 📄 RAG MCQs Generator – Quiz from Any PDF using Azure OpenAI

This project allows users to upload any PDF (e.g., a research paper), and automatically:

✅ Generate 5 Multiple Choice Questions (MCQs)  
🧠 Generate 5 Short Answer Questions  
💬 Ask questions and get human-readable answers using natural language

Built using **LangChain**, **FAISS**, **Azure OpenAI**, and **Streamlit**.

---

## 🚀 Features

- Upload any PDF and extract readable content
- Chunk and embed text using FAISS & Azure Embeddings
- Ask natural questions and receive conversational answers
- Auto-generate quizzes: MCQs & short answers
- Fast and easy-to-use web interface

---

## 🛠 Tech Stack

- `Streamlit` – Web UI  
- `LangChain` – RAG logic  
- `FAISS` – Vector store  
- `Azure OpenAI` – Embeddings & chat completions  
- `PyMuPDF` – PDF text extraction  
- `.env` – Secure API config

---

## 🧠 How It Works

1. **Upload PDF**  
2. **Text Extraction** via PyMuPDF  
3. **Chunking & Embedding**  
4. **Store in FAISS vector DB**  
5. **Query with Azure ChatOpenAI**  
6. **Generate MCQs & Short Answers**

---

## ▶️ Demo

> [🔗 Live demo (Coming Soon)]  
> [💻 Code Walkthrough Video (Coming Soon)]

---

## 📂 Setup

1. Clone this repo  
2. Create a `.env` file with the following:

```env
AZURE_OPENAI_API_KEY=your_key
AZURE_OPENAI_ENDPOINT=https://your-endpoint.openai.azure.com
AZURE_OPENAI_API_VERSION=2023-05-15
AZURE_OPENAI_DEPLOYMENT_NAME=gpt-35-turbo

EMBEDDING_AZURE_OPENAI_API_KEY=your_key
EMBEDDING_AZURE_OPENAI_ENDPOINT=https://your-embedding-endpoint.openai.azure.com
EMBEDDING_AZURE_OPENAI_API_VERSION=2023-05-15
EMBEDDING_AZURE_OPENAI_DEPLOYMENT_NAME=text-embedding-ada-002
