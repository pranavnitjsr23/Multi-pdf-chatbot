# 📚 Chat with Your PDFs (RAG App)

An AI-powered web app that allows you to **chat with multiple PDF documents** using open-source models.
Built using **Streamlit + LangChain + Hugging Face**, this app extracts, processes, and answers questions from your documents in real-time.

---

## 🚀 Features

* 📄 Upload multiple PDFs
* ✂️ Automatic text chunking
* 🔍 Semantic search using embeddings
* 💬 Conversational Q&A with memory
* 🎨 Clean chat-based UI
* 🆓 Fully open-source (no OpenAI required)

---

## 🧠 Tech Stack

* **Frontend:** Streamlit
* **LLM:** Hugging Face (`google/flan-t5-base`)
* **Embeddings:** `sentence-transformers/all-MiniLM-L6-v2`
* **Vector DB:** FAISS
* **Framework:** LangChain

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/pdf-chatbot.git
cd pdf-chatbot
```

---

### 2️⃣ Create virtual environment (recommended)

```bash
conda create -n pdfbot python=3.10 -y
conda activate pdfbot
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Set Hugging Face API token

Get your token from: https://huggingface.co/settings/tokens

```bash
setx HUGGINGFACEHUB_API_TOKEN "your_token_here"
```

Restart your terminal after this step.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📌 How It Works

1. Upload PDFs
2. Text is extracted and split into chunks
3. Embeddings are created for semantic search
4. FAISS stores vector representations
5. LLM retrieves relevant chunks and generates answers



## ⚠️ Limitations

* Hugging Face free API can be slow
* Large PDFs may take time to process
* Accuracy depends on document quality

---

## 🚀 Future Improvements

* 📄 Show source citations (PDF + page number)
* ⚡ Streaming responses
* 🌐 Deploy on cloud (Streamlit Cloud / Render)
* 🧠 Use stronger open-source LLMs (Mistral, LLaMA)

---




---
