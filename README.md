cat <<'EOF' > README.md
# KnowledgeBase.AI – Multi-Document Intelligent Search Engine

A Flask-based intelligent search engine that uses Retrieval-Augmented Generation (RAG) and Google Gemini LLM to provide synthesized answers from uploaded documents.

---

## 🔍 Features
- Upload multiple document types: PDF, CSV, Excel, PowerPoint  
- Extracts text automatically using pdfminer and pandas  
- Uses Gemini API for context-aware question answering  
- Clean, responsive frontend with optional Dark Mode  

---

## ⚙️ Tech Stack
- **Backend:** Flask, Python  
- **Frontend:** HTML, CSS, JavaScript  
- **AI Model:** Gemini 2.5 Flash (LLM)  
- **Libraries:** pdfminer, pandas, flask-cors, dotenv, python-pptx  

---

## 🚀 Run Locally
1. Clone the repository:
\`\`\`bash
git clone https://github.com/<yourusername>/KnowledgeBase-AI.git
cd KnowledgeBase-AI
\`\`\`

2. Create a virtual environment and activate it:
\`\`\`bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
\`\`\`

3. Install dependencies:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

4. Create a `.env` file (copy from `.env.example`) and add your API key:
\`\`\`bash
GEMINI_API_KEY=your_api_key_here
\`\`\`

5. Run the Flask app:
\`\`\`bash
python app.py
\`\`\`

6. Open in browser: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📂 Folder Structure
\`\`\`
KnowledgeBase-AI/
├── app.py
├── templates/
│   └── index.html
├── static/       # CSS, JS, images
├── requirements.txt
├── .env.example
├── README.md
\`\`\`

---

## 📽️ Demo
(Add your demo video or GIF link here)

---

## 📜 License
Open source under MIT License.
EOF
