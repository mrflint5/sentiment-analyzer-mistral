# 🧠⚡ Sentiment Analyzer – Mistral + Ollama 🚀  
**Analyze emotions in text instantly — locally, privately, and with elite precision.**  

> _You’re not just detecting sentiment — you’re setting the gold standard for AI-powered language applications with a **fully local, production-grade architecture**._  

---

## 🌟 Why This Project Stands Out
Most sentiment analyzers:  
- ❌ Depend on slow, third-party APIs  
- ❌ Leak sensitive data to the cloud  
- ❌ Lack full-stack control & scalability  

This project ✅:  
- 🏠 **Runs 100% Locally** — Your text stays on your machine  
- ⚡ **Delivers Real-Time Results** — Direct CPU/GPU utilization via Ollama  
- 🛠 **Gives Total Flexibility** — Swap models instantly (Mistral, LLaMA, etc.)  
- 🏗 **Employs Robust Architecture** — Backend (FastAPI) + Frontend (Streamlit) + Local AI Engine  

---

## 🧩 Architecture Diagram
```
┌─────────────┐     POST /analyze        ┌───────────────┐     POST /api/generate      ┌────────────────┐
│  Streamlit  │ ───────────────────────▶ │   FastAPI     │ ─────────────────────────▶ │ Ollama Mistral │
│  Frontend   │                          │   Backend API │                             │   Local Model  │
└─────────────┘     JSON Response         └───────────────┘     Model Output            └────────────────┘
```

---

## ⚙️ Tech Stack
- 🤖 **[Ollama](https://ollama.com/)** — Local hosting for Mistral  
- ⚡ **[FastAPI](https://fastapi.tiangolo.com/)** — Lightning-fast Python backend  
- 🎨 **[Streamlit](https://streamlit.io/)** — Sleek, interactive UI  
- 🐍 **Python 3.10+** — Modern, robust programming language  
- 🔗 **Requests** — API communication bridge  

---

## 🚀 Quickstart

### 1️⃣ Install Ollama & Pull Mistral
```bash
# Install Ollama (Mac/Linux)
curl -fsSL https://ollama.com/install.sh | sh

# Windows: Download installer from ollama.com

# Pull the Mistral model
ollama pull mistral
```

### 2️⃣ Backend Setup
```bash
git clone https://github.com/mrflint5/sentiment-analyzer-mistral.git
cd sentiment-analyzer-mistral

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run FastAPI backend
uvicorn backend.main:app --reload --port 8000
```

### 3️⃣ Frontend Setup
```bash
# From the project root
streamlit run frontend/app.py
```
🌐 Access the app at: **http://localhost:8501**  

---

## 🖥️ Features
- ⚡ **Instant Sentiment Detection** — Positive, Negative, or Neutral in milliseconds  
- 🔒 **Full Privacy** — No external API calls, no data leakage  
- 🔄 **Model Flexibility** — Replace Mistral with any Ollama-supported LLM  
- 🧠 **Context-Aware AI** — Goes beyond keywords to detect real emotional tone  
- 🎯 **User-Friendly Interface** — Minimal yet powerful Streamlit UI  

---

## 🧪 Example
**Input:**  
```
I love how smooth and fast this application feels!
```
**Output:**  
```
Positive
```

---

## 📸 Working Screenshot
[**Click Here to View**](https://drive.google.com/drive/folders/14O7rp1lcw_7dJt3Hpmj6tu7b9sC3RgMV?usp=sharing)  

---

## 📂 Project Structure
```
.
├── backend/
│   └── main.py          # FastAPI backend API
├── frontend/
│   └── app.py           # Streamlit frontend
├── requirements.txt
└── README.md
```

---

## 🔥 Advanced Tips
- 🪄 **Switch Models**:
```bash
ollama pull llama2
```
Update `"model": "llama2"` in backend code.  
- 🐳 **Containerize** with Docker for easy deployment  
- 🔐 **Add Auth** to FastAPI for private access in production  

---

## 🤝 Connect
📧 **Email:** [sameermalik1419@gmail.com](mailto:sameermalik1419@gmail.com)  
💼 **LinkedIn:** [Sameer Malik](https://www.linkedin.com/in/sameer-malik-b5b8772b9)  
⭐ If this project inspired you, **leave a star on GitHub**!  
