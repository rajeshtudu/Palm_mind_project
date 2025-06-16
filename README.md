# 📚 Document Chatbot with LangChain & Gemini

A conversational AI chatbot that can answer user questions based on uploaded documents (PDFs) and collect user details like Name, Email, Phone, and Appointment Date via a conversational form.

---

## 🚀 Features

- 💬 Chat with any document (PDF)
- 🧠 Powered by **LangChain** and **Gemini (Google Generative AI)**
- 📂 Automatic document loading and embedding with FAISS
- 🗓️ Conversational form to book appointments
- 📅 Natural language date parsing (e.g., “next Monday” → `YYYY-MM-DD`)
- ✅ Real-time validation for email and phone number
- 🌐 Built with **Streamlit** for a clean browser UI

---

## 📦 Tech Stack

- **Python 3.10+**
- [LangChain](https://python.langchain.com/)
- [Google Generative AI (Gemini)](https://makersuite.google.com/app/apikey)
- **FAISS** (vector store for document retrieval)
- **Streamlit** (UI)
- `dateparser`, `dotenv`, `pydantic` for utility handling

---

## 🧰 Project Structure

