# 📄 RAG-based PDF Question Answering System

I built this project to understand how Retrieval-Augmented Generation (RAG) systems work and to gain hands-on experience with document retrieval pipelines.

The project helped me learn about:

- PDF-based information retrieval
- Semantic search
- Vector embeddings
- Text chunking strategies
- Context retrieval
- LLM-based question answering

I mainly developed this system as a foundation for my current work involving medical data retrieval and healthcare-related AI applications. Working on this project gave me practical experience with how documents are processed, stored, retrieved, and used for generating responses in real-world RAG systems.

---

# 🚀 Live Demo

https://rag-based-pdf-question-answering-system.streamlit.app/

# 📂 GitHub Repository

https://github.com/Erebo/RAG-based-PDF-Question-Answering-System

---

# 🚀 Features

- Upload and process PDF documents
- Ask questions directly from uploaded PDFs
- Retrieval-Augmented Generation (RAG) pipeline
- Semantic chunk retrieval
- Adjustable chunk size and overlap
- Configurable top-k retrieval
- Retrieved context visualization
- Clean and interactive Streamlit UI

---

# 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- FAISS / Vector Store
- Sentence Transformers
- LLMs
- PyPDF
- Semantic Search

---

# 🧠 How It Works

The application follows a standard RAG (Retrieval-Augmented Generation) workflow.

## 1️⃣ PDF Upload

Users upload one or multiple PDF files.

## 2️⃣ Text Extraction

The system extracts text from the uploaded PDFs.

## 3️⃣ Text Chunking

The extracted text is divided into smaller chunks using configurable:

- Chunk size
- Chunk overlap

## 4️⃣ Embedding Generation

Each chunk is converted into vector embeddings for semantic understanding.

## 5️⃣ Vector Database Storage

The embeddings are stored in a vector database for efficient retrieval.

## 6️⃣ Query Processing

The user query is converted into embeddings and matched against stored vectors.

## 7️⃣ Context Retrieval

Top relevant chunks are retrieved based on semantic similarity.

## 8️⃣ Response Generation

The retrieved context is passed to the language model to generate accurate responses.

---

# 📷 Project Interface

## Main Features

- PDF Upload System
- Interactive Chat Interface
- Retrieval Configuration Panel
- Retrieved Context Viewer

## Adjustable Retrieval Parameters

- Chunk Size
- Chunk Overlap
- Top-k Retrieval

---

# ⚡ Installation

## Clone the repository

```bash
git clone https://github.com/Erebo/RAG-based-PDF-Question-Answering-System.git
```

## Move into the project directory

```bash
cd RAG-based-PDF-Question-Answering-System
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run the application

```bash
streamlit run app.py
```

---

# 📌 Example Use Cases

- Research paper analysis
- Academic PDF querying
- AI-assisted document retrieval
- Knowledge extraction from reports
- Understanding long-form documents efficiently

---

# 🔮 Future Improvements

- Adaptive chunking strategies
- Hybrid retrieval systems
- Citation-aware responses
- Multi-document memory
- Streaming response generation
- Medical-domain optimized retrieval
- Better context ranking mechanisms

---

# 👨‍💻 Author

Mahadi Rahman Jihad  
Research Enthusiast | AI | Computer Vision | Healthcare AI

GitHub: https://github.com/Erebo

---

# ⭐ Acknowledgement

This project was developed as a personal learning and research exploration project to better understand the practical implementation of modern Retrieval-Augmented Generation systems and intelligent document retrieval pipelines for future AI and healthcare-related applications.