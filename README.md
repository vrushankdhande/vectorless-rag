# 🚀 Vecless RAG (Vectorless Retrieval-Augmented Generation)

## 📌 Overview

Vecless RAG is an end-to-end Retrieval-Augmented Generation (RAG) system that eliminates the need for traditional vector databases. Instead of embeddings, it uses PageIndex for structured document retrieval and Groq LLMs for fast, context-aware response generation.

This approach simplifies architecture, reduces computational overhead, and enables efficient document querying.

Get Your API's By Creating Account.

- 🔑 Get your PageIndex API key from: [https://dash.pageindex.ai/api-keys](https://dash.pageindex.ai/api-keys)
- 🔑 Get your groq API key from: [https://platform.openai.com](https://groq.com/)

## ⚙️ Features
- 🔍 Vectorless document retrieval (no embeddings required)
- ⚡ Fast inference using Groq LLM APIs
- 🧠 Context-aware response generation
- 📄 Structured document indexing via PageIndex
- 🛠️ Lightweight and scalable architecture

## 🏗️ Architecture
- Ingestion → Documents are indexed using PageIndex
- Query Input → User provides a natural language query
- Relevant Node Retrieval → PageIndex fetches relevant sections
- LLM Processing → Groq LLM generates final response

## 🛠️ Tech Stack
- Python
- Groq API (LLM inference)
- PageIndex API (document retrieval)
- JSON processing

## 📂 Project Structure
```
vecless_rag/
│── vectorless_rag.ipynb   # Main Code File
│── constants.py         # Stores API key
│── requirements.txt     # Dependencies
└── README.md            # Documentation
```

## 🔑 Setup & Installation

- 1️⃣ Clone the repository
```
git clone https://github.com/your-username/vecless_rag.git
cd vecless_rag
```
- 2️⃣ Install dependencies
```
uv add -r requirements.txt
```
- 3️⃣ Add API Keys
-- Create a constants.py file:
```
Groq_API_KEY = "your_groq_api_key"
PAGEINDEX_API_KEY = "your_pageindex_api_key
```
- ▶️ Usage
-- Run the notebook:
```
jupyter notebook vecless_rag.ipynb
```
Steps:
1. Load your document/index
2. Enter a query
3. Retrieve relevant nodes
4. Generate response using LLM

📊 Example
- Input Query:
```
What is Handwriting Recognition?
```
- Output:
```
Handwriting recognition is a machine learning application that converts handwritten text into digital format...
```
## ✅ Advantages
- No need for vector databases (FAISS, Pinecone, etc.)
- Lower cost and complexity
- Faster setup and deployment
- Easier debugging and transparency

## 🚧 Future Improvements
- Add evaluation metrics for retrieval quality
- Integrate UI (Streamlit / React)
- Support multiple document formats (PDF, DOCX)
- Add caching for faster responses

## 🤝 Contributing
Contributions are welcome!
- Fork the repository
- Create a new branch
- Submit a pull request

## 👤 Author

Vrushank Dhande
Aspiring Data Scientist | Machine Learning Engineer

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub!
