# 🧠 Sentiment Analyzer – Powered by Mistral & Ollama 🚀

Welcome to the **next-generation** Sentiment Analysis app – crafted with precision, speed, and elegance.  
This AI-powered tool leverages the **Mistral model** via **Ollama**, delivering lightning-fast, highly accurate sentiment classification with a beautiful UI and rock-solid backend.

> 🌟 Built for innovators, by an innovator. If you’re reading this, you’re looking at a project from the **top 1%**.

---

## ✨ Features That Set It Apart
- ⚡ **Blazing-Fast Predictions** – Mistral model optimized via Ollama for near-instant responses.
- 🖥 **Modern Two-Tier Architecture** – FastAPI backend + Streamlit frontend.
- 🤖 **AI-Powered Accuracy** – Understands context, tone, and emotional polarity.
- 📦 **Lightweight & Portable** – Easy to set up, run, and extend.
- 🔄 **Seamless Integration** – Ready to plug into larger systems or use as a standalone app.

---

## 🏗 Tech Stack
| Layer           | Technology |
|-----------------|------------|
| **Frontend**    | Streamlit  |
| **Backend**     | FastAPI    |
| **Model Host**  | Ollama (Mistral) |
| **Language**    | Python     |
| **Versioning**  | Git + GitHub |

---

## 🚀 How It Works
1. **User Input** → You enter any sentence into the sleek Streamlit UI.
2. **API Call** → FastAPI sends the text to Ollama's Mistral model.
3. **AI Processing** → Mistral analyzes and classifies the sentiment: **Positive**, **Negative**, or **Neutral**.
4. **Results Displayed** → The prediction is shown instantly on the UI.

---

## 📸 Working Screenshot
[**Click Here to View**](https://drive.google.com/drive/folders/14O7rp1lcw_7dJt3Hpmj6tu7b9sC3RgMV?usp=sharing)

---

## 🛠 Quick Start – Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/mrflint5/sentiment-analyzer-mistral.git
cd sentiment-analyzer-mistral
```

### 2️⃣ Set Up Virtual Environment
```bash
python -m venv venv
```
- **Windows**:
```bash
venv\Scripts\activate
```
- **Mac/Linux**:
```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Pull the Mistral Model (Ensure Ollama is running)
```bash
ollama pull mistral
```

### 5️⃣ Run Backend (FastAPI)
```bash
uvicorn backend.main:app --reload
```

### 6️⃣ Run Frontend (Streamlit)
```bash
streamlit run frontend/app.py
```

---

## 📂 Project Structure
```
sentiment-analyzer-mistral/
│
├── backend/
│   └── main.py          # FastAPI backend code
│
├── frontend/
│   └── app.py           # Streamlit frontend code
│
├── requirements.txt     # Python dependencies
└── README.md            # This file
```

---

## 💡 Pro Tip
This project is **modular** – swap Mistral with any Ollama-supported LLM to experiment with different language models without changing your core logic.

---

## 🤝 Contributing
Pull requests are welcome! If you have ideas to push this project beyond its limits, let’s make it happen.

---

## 🌐 Connect With Me
- **LinkedIn**: [Sameer Malik](https://www.linkedin.com/in/sameer-malik-b5b8772b9)
- **Email**: sameermalik1419@gmail.com

> 🏆 Remember: Good code solves problems, but **great code inspires innovation**.
