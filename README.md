# 📚 Telebot with RAG  

This project integrates **Retrieval-Augmented Generation (RAG)** with a **Telegram Bot**, enabling users to query any PDF document (e.g., books, research papers, reports). The bot retrieves the most relevant text chunks using **FAISS** and generates concise answers using **LLaMA 3.2 Instruct**.

---

## 🚀 Features
- 📖 Upload and process **PDF documents**.  
- 🔍 Retrieve the most relevant content using **FAISS vector search**.  
- 🧠 Generate clear, context-based answers using **LLaMA 3.2**.  
- 🤖 Seamless integration with **Telegram Bot**.  
- 🔒 Runs locally — your data stays private.  

---

## 🛠️ Tech Stack
- **Python 3.10+**
- [Transformers](https://huggingface.co/docs/transformers) (for LLaMA 3.2 Instruct)  
- [SentenceTransformers](https://www.sbert.net/) (for embeddings)  
- [FAISS](https://faiss.ai/) (for similarity search)  
- [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) (Telegram bot framework)  
- [pdfplumber](https://github.com/jsvine/pdfplumber) (PDF text extraction)  

---

## ⚙️ Installation  

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/telebot-with-rag.git
   cd telebot-with-rag
