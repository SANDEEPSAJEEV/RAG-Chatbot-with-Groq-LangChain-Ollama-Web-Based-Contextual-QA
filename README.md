# RAG Chatbot with Groq + LangChain + Ollama | Web-Based Contextual QA

This project implements a **Retrieval-Augmented Generation (RAG) based conversational AI system** using:
- 🧠 **Groq’s Gemma2-9B-IT** model for fast, low-latency inference.
- 📄 **Ollama's `mxbai-embed-large`** for document embedding.
- 🕸️ **Web scraping** using `WebBaseLoader` to ingest content dynamically.
- 🧩 **LangChain** components for orchestration.
- 🧠 **Chroma** for vector database and similarity search.
- 💬 **Chat history-aware retrieval** to support multi-turn contextual Q&A.

---

## 🚀 Features

- 🔗 Web-based content ingestion and chunking.
- 🔍 Semantic search with `OllamaEmbeddings` + Chroma.
- 💬 Conversational memory using `MessagesPlaceholder`.
- 🤖 Context-aware responses using `ChatGroq` with `gemma2-9b-it`.
- 📦 Modular design with LangChain's RAG architecture.

---

## 🧰 Tech Stack

| Component | Usage |
|----------|--------|
| `LangChain` | Framework for chaining components |
| `Groq` | Fast inference using Gemma2-9B |
| `Ollama` | Local embedding model |
| `Chroma` | Vector database for storing embeddings |
| `BeautifulSoup` | Filter and parse web content |
| `dotenv` | Load environment variables |
| `bs4.SoupStrainer` | Restrict HTML parsing to specific content |

---

## 📁 Project Structure

