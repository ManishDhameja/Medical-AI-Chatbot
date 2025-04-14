# 🏥 Medical AI Chatbot — LLM-Powered Healthcare Assistant

This project is a smart conversational Medical AI Chatbot built using modern open-source tools. It uses HuggingFace for generating embeddings, Faiss for efficient vector search, and Mistral to power the conversational logic — all integrated in a clean Streamlit interface.

Whether you're experimenting with healthcare-focused AI or exploring how to connect vector databases with LLMs, this project is a great place to start.

---

## 🚀 Features

- Ask medical-related questions in natural language
- Uses HuggingFace models for embeddings
- Faiss CPU for fast and efficient vector-based search
- Built-in document ingestion from PDFs
- Simple frontend using Streamlit

---

## 📦 Installed Dependencies

pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit

### Or using pip:
pip install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pip install huggingface_hub
pip install streamlit

### ✅ Note: Make sure you have a .env file with your Groq API key:
HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token

### ▶️ Run the App
streamlit run main.py

---

## 🛠️ Tech Stack

- **Mistral** – For natural language understanding and response generation
- **LangChain** – Framework for connecting LLMs with external tools and memory
- **HuggingFace Transformers** – For generating embeddings from medical text
- **Faiss (CPU)** – Vector database for efficient semantic search
- **pypdf** – To parse and extract content from medical PDFs
- **Streamlit** – For building the web-based chatbot interface
