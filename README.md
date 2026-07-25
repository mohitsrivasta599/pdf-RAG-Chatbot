# 📚 RAG Book Assistant

A Streamlit-based Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask questions based on their content.

## Features

- 📄 Upload any PDF document
- ✂️ Automatically split text into chunks
- 🧠 Generate embeddings using Hugging Face
- 💾 Store embeddings in Chroma Vector Database
- 🔍 Retrieve relevant document context
- 🤖 Generate accurate answers using Mistral AI
- 🌐 Interactive Streamlit web interface

## Tech Stack

- Python
- Streamlit
- LangChain
- Hugging Face Embeddings
- ChromaDB
- Mistral AI
- PyPDF

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file and add your Mistral API key:

```env
MISTRAL_API_KEY=your_mistral_api_key
```

## Run the Application

```bash
streamlit run app.py
```

## Project Structure

```
RAG-Book-Assistant/
│── app.py
│── requirements.txt
│── README.md
└── .gitignore
```

## Author

Mohit Srivastava
