# 🧠 RAG Agent with LangChain, Streamlit, and Google Gemini

This project is a **Retrieval-Augmented Generation (RAG) Agent** built using **LangChain**, **Streamlit**, and **Google’s Gemini 2.5 Flash model**.  
It allows users to upload **PDF**, **CSV**, and **text files** to create a context-aware AI assistant capable of retrieving and answering queries from your custom data.

---

## 🚀 Features

✅ Upload and process **PDF**, **CSV**, or **TXT** files  
✅ Uses **LangChain** for chunking, embeddings, and retrieval  
✅ **Google Gemini 2.5 Flash** model for fast, high-quality responses  
✅ Simple and elegant **Streamlit web interface**  
✅ Real-time question answering from uploaded documents  
✅ **Vector database** for context storage and efficient retrieval  
✅ Automatically handles multiple files and combines their context  

---

## 🧩 How It Works

1. **File Upload**  
   The user uploads one or more files (`.pdf`, `.csv`, `.txt`).  

2. **Document Processing**  
   LangChain loads the content, splits it into smaller chunks, and generates embeddings using a vector store (like FAISS or Chroma).

3. **Question Answering**  
   When a user types a question, the system retrieves the most relevant document chunks and sends them—along with the question—to **Gemini 2.5 Flash**, which generates a natural, accurate answer.

4. **Display in Streamlit**  
   The response is displayed instantly in an interactive Streamlit UI.

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|----------------|
| Frontend | Streamlit |
| AI Framework | LangChain |
| Model | Google Gemini 2.5 Flash |
| Embeddings | LangChain Embedding Models |
| Storage | FAISS / Chroma (Vector Database) |
| File Types | PDF, CSV, TXT |
| Language | Python 3.10+ |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/rag-agent.git
cd rag-agent
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate    # On Mac/Linux
venv\Scripts\activate       # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Add Environment Variables
    Create a .env file and include your Google API key:

```bash
GOOGLE_API_KEY=your_api_key_here
```

### 5️⃣ Run the Streamlit App
```bash
streamlit run ui.py
```

## Credits 
Original project by [611noorsaeed](https://github.com/611noorsaeed) Modified and updated by me.