✅ README.md
# 🤖 AI Document Intelligence System

A powerful Streamlit-based application that extracts, analyzes, chunks, summarizes, and chats with documents using local **Ollama AI models**.  
Supports **PDF, DOCX, TXT**, provides a beautiful UI, live chat, analytics, and full-document contextual question answering.

---
<img width="1919" height="1006" alt="Screenshot 2025-12-03 000711" src="https://github.com/user-attachments/assets/93dc3a93-b8c3-4433-bdf8-ee87ee7561d3" />

## 🚀 Features

### 📁 Document Processing
- Extract text from **PDF**, **DOCX**, and **TXT**
- Automatic document analytics:
  - Word count  
  - Sentence count  
  - Paragraph count  
  - Unique words  
  - Average word length  
  - File size  
  - Processing time  

### 🧩 Smart Text Chunking
- Customizable chunk size  
- Adjustable overlap  
- Automatically builds structured JSON  

### 🤖 AI-Powered Interaction
- Chat with documents like ChatGPT/Claude  
- Uses local **Ollama models** (Llama, Mistral, etc.)  
- Supports:
  - Summaries  
  - Q&A  
  - Translations  
  - Extraction  
  - Explanation  
  - Code generation  
  - General chat  
<img width="1919" height="1015" alt="Screenshot 2025-12-03 000956" src="https://github.com/user-attachments/assets/264b520b-c293-4785-bb8a-22e1f01295ff" />

### 🎨 Beautiful UI
- Gradient headers  
- Animated chat messages  
- Stylish metric cards  
- Auto summary  
- Interactive JSON preview  
- Chunk viewer  

---

## 📦 Installation

### 1️⃣ **Clone the repository**

```bash
git clone https://github.com/guptapreeti194/ClauseEase-AI.git
cd ClauseEase-AI

2️⃣ Install dependencies

Create a virtual environment (recommended):

python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows


Install packages:

pip install -r requirements.txt


Required Python Libraries:

streamlit
requests
PyPDF2
python-docx

3️⃣ Install Ollama

Download from:
https://ollama.com/download

Pull a model (example):

ollama pull llama3.2


Check available models:

ollama list

▶️ Running the Application
streamlit run app.py


Open in browser:
👉 http://localhost:8501

Make sure Ollama is running locally on:
👉 http://localhost:11434

📁 Folder Structure
ai-document-system/
│── app.py
│── README.md
│── LICENSE
│── requirements.txt
└── assets/

⚙️ Configuration

You can modify:

Chunk size

Overlap

Model used

Auto summary toggle

JSON view

Chunk viewer

All available in Sidebar → Configuration Panel

📤 Export Features

Export chat history as JSON

Reset document/session anytime

🤝 Contributing

Pull requests are welcome!
If you find any issues, open a ticket here:

👉 https://github.com/guptapreeti194/ClauseEase-AI/issues
