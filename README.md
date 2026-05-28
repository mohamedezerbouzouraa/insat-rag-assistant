# 🎓 INSAT RAG Assistant

AI-powered multilingual chatbot for INSAT (Institut National des Sciences Appliquées et de Technologie).

Built using:

* LangChain
* BM25 Retrieval
* Groq LLMs
* Flask
* Vanilla JavaScript
* Glassmorphism UI

---

# ✨ Features

* 🔍 BM25 Retrieval-Augmented Generation (RAG)
* 🌍 Multilingual support (English / French / Arabic)
* ⚡ Ultra-fast Groq inference
* 🎨 Modern luxury UI
* 📚 Source chunk transparency
* 💬 Real-time typing animation
* 🧠 Context-aware responses
* 📱 Fully responsive design

---

# 🏗️ Architecture

Frontend:

* HTML
* CSS
* JavaScript

Backend:

* Flask API
* LangChain
* BM25Retriever
* Groq LLM

Pipeline:
User Query → BM25 Retrieval → LangChain Prompt → Groq LLM → Response

---

# 📂 Project Structure

```bash
backend/
frontend/
docs/
README.md
```

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/insat-rag-assistant.git
cd insat-rag-assistant
```

## 2. Install Dependencies

```bash
pip install -r backend/requirements.txt
```

## 3. Add Groq API Key

Create a `.env` file:

```env
GROQ_API_KEY=your_key_here
```

---

# ▶️ Run Backend

```bash
python backend/app.py
```

Server runs on:

```txt
http://localhost:5000
```

---

# 🌐 Run Frontend

Open:

```txt
frontend/index.html
```

Or use VSCode Live Server.

---

# 📸 Screenshots

Add screenshots here.

---

# 🧠 Technologies Used

* Flask
* LangChain
* BM25Retriever
* Groq API
* HTML/CSS/JS

---

# 🔒 Security Notes

Never expose your API keys publicly.

Use environment variables instead of hardcoding secrets.

---

# 📈 Future Improvements

* Vector database support
* Hybrid search
* Authentication
* Chat history
* Voice assistant
* PDF ingestion
* Docker deployment
* MongoDB integration

---

# 👨‍💻 Author

Mohamed Ezer

INSAT — Institut National des Sciences Appliquées et de Technologie

---

# 📜 License

MIT License
