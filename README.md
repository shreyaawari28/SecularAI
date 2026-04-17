# 📘 SecularAI — AI-Based Scripture Exploration System

## 🔷 Overview
SecularAI is an AI-powered chatbot that enables users to explore religious scriptures like the Bhagavad Gita, Quran, and Bible through natural language conversations. It uses Retrieval-Augmented Generation (RAG) to provide accurate, context-based answers grounded in authentic texts.

---

## 🎯 Objectives
- Provide an interactive platform for religious learning  
- Deliver accurate, context-aware responses  
- Reduce hallucination in AI-generated answers  
- Support multi-scripture exploration in one system  

---

## ⚙️ Tech Stack
- **Frontend:** React, TypeScript, Tailwind CSS  
- **Backend:** FastAPI (Python)  
- **Database:** PostgreSQL (user data), Pinecone (vector DB)  
- **AI Models:**  
  - LLM: Llama 3.3 (via Groq)  
  - Embeddings: Mistral  

---

## 🧠 How It Works (RAG Flow)
1. User inputs a question  
2. Question is converted into embeddings  
3. Vector search is performed in Pinecone  
4. Top-K relevant chunks are retrieved  
5. Context + query sent to LLM  
6. AI generates a grounded response  

---

## 🔑 Key Features
- Multi-religion support (Gita, Quran, Bible)  
- Context-based accurate answers  
- Hallucination prevention  
- Interactive chatbot UI  
- Verse highlighting system  
- Secure authentication (JWT + OTP)  

---

## 📊 System Design
- Uses **cosine similarity** for semantic search  
- Implements **chunking with overlap** for better context  
- Optimized with **Top-K retrieval (k = 3)**  

---

## 🚀 Installation

```bash
# Clone repository
git clone https://github.com/your-username/secularai.git

# Navigate to project
cd secularai

# Install backend dependencies
pip install -r requirements.txt

# Run backend
uvicorn main:app --reload

# Install frontend dependencies
npm install

# Run frontend
npm run dev
```

## 📌 Usage
- Select a scripture  
- Ask a question in natural language  
- Receive context-aware, accurate responses  
- View extracted verses separately  

---

## ⚠️ Limitations
- Depends on retrieval quality  
- May miss information if relevant chunks are not retrieved  
- Not a replacement for scholarly interpretation  

---

## 🔮 Future Scope
- Multilingual support  
- Voice interaction  
- Expansion to more knowledge domains  

---

## 👩‍💻 Contributors
- Shreya Awari  
- Team Members  

---

## 📜 License
This project is for academic and educational purposes.