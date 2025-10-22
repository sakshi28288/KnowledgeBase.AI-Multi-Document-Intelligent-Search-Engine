# Knowledge-Base Search Engine

Knowledge-Base Search Engine is a Flask-based application that allows users to upload documents (PDF, CSV, Excel, PowerPoint) and ask questions. Answers are generated using **Gemini LLM (Google Generative AI)** for intelligent, context-aware responses.

---

### 📸 Features

- Upload multiple document types: PDF, CSV, Excel, PowerPoint  
- AI-powered question answering using Google Gemini API  
- Clean, responsive web interface  
- Virtual environment support for Python dependencies  

---

### 🛠️ Requirements

- Python 3.10 or higher  
- Gemini API Key from Google  
- Virtual environment recommended  

---

### 🚀 Setup Instructions

###1. Clone or copy the project folder
```bash
git clone <your-repo-url>
cd <project-folder>
```
### 2. Create and activate a Python virtual environment
### Windows
```bash
python -m venv venv
venv\Scripts\activate
```
### Linux/Mac
```bash
python3 -m venv venv
source venv/bin/activate
```
### 3. Install required packages
```bash
pip install -r requirements.txt
```
### 4. Create a .env file in the project root with your Gemini API key
```bash
echo 'GEMINI_API_KEY="your_google_gemini_api_key_here"' > .env
```
### 5. Run the Flask server
```bash
python app.py
```
### 6. Open your browser
### http://127.0.0.1:5000

📂 Supported File Types
PDF (.pdf)
CSV (.csv)
Excel (.xlsx, .xls)
PowerPoint (.pptx, .ppt)

Notes:
- Ensure the index.html file is in the same folder as app.py or inside a "templates" folder.
- For PowerPoint support, install python-pptx:
  ```bash
   pip install python-pptx
  ```




