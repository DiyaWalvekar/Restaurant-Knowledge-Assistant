# 🍽️ Restaurant Knowledge Assistant

An AI-powered Restaurant Knowledge Assistant built using Retrieval-Augmented Generation (RAG) to answer user queries about restaurant information, including menus, reservations, events, FAQs, and team details.

The application leverages LangChain, ChromaDB, HuggingFace model Embeddings, and Gradio to provide accurate, context-aware, and source-grounded responses through semantic document retrieval.

## 🚀 Features

- Semantic document search using vector embeddings
- Retrieval-Augmented Generation (RAG) pipeline
- AI-powered question answering
- Source-attributed responses
- Interactive Gradio web interface
- Fast and relevant information retrieval
- Restaurant-specific knowledge base

## 🛠️ Tech Stack

- Python
- LangChain
- ChromaDB
- HuggingFace -sentence-transformers/all-MiniLM-L6-v2 model Embeddings
- Groq model
- Gradio
- RetrievalQA Chain

## 📂 Dataset

The knowledge base consists of restaurant-related information including:

- Restaurant Overview
- Menus and Dining Experience
- Reservations
- FAQs
- Events and Private Dining
- Team Information
- Contact Details

Data was processed and converted into vector embeddings for semantic search and retrieval.

## ⚙️ System Architecture

1. Load restaurant documents
2. Split documents into manageable chunks
3. Generate embeddings using HuggingFace model Embeddings
4. Store vectors in ChromaDB
5. Retrieve relevant chunks based on user query
6. Generate context-aware responses using an Groq LLM
7. Display results through Gradio UI

## 📸 Workflow

User Query
↓
HuggingFace model Embeddings
↓
ChromaDB Vector Search
↓
Relevant Document Retrieval
↓
LangChain RetrievalQA
↓
Groq LLM Response Generation
↓
Gradio Interface

---

## 📈 Key Achievements

- Developed a Retrieval-Augmented Generation (RAG) pipeline using LangChain, ChromaDB, and HuggingFace model Embeddings.
- Achieved 90%+ query relevance through semantic search and context-aware retrieval.
- Built an AI-powered Q&A assistant capable of answering restaurant-related queries with source-grounded responses.
- Deployed an interactive web application using Gradio for real-time user interaction.

## 🔧 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/restaurant-knowledge-assistant.git
cd restaurant-knowledge-assistant
```


## 💡 Example Queries

- What menus are available at the restaurant?
- How can I make a reservation?
- What are the restaurant timings?
- Who is the head chef?
- Are private events available?
- What is the cancellation policy?

---

## 🎯 Future Enhancements

- Multi-restaurant support
- Voice-based querying
- Chat history memory
- Hybrid search (Keyword + Vector Search)
- Cloud deployment
- Advanced analytics dashboard

---

## 👩‍💻 Author

Diya Walvekar

LinkedIn: www.linkedin.com/in/diya-walvekar-905248230

---

## 📜 License

This project is developed for educational and portfolio purposes.
