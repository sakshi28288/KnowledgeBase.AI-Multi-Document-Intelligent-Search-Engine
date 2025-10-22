cat <<'EOF' > README.md
# Knowledge-Base Search Engine

**Description:**  
This is a Flask-based Knowledge-Base Search Engine. Users can upload documents (PDF, CSV, Excel, PowerPoint) and ask questions. Answers are generated using Gemini LLM (Google Generative AI).

---

## Requirements
- Python 3.10 or higher
- Gemini API Key from Google
- Virtual environment recommended

---

## Setup Instructions

**Clone or copy the project folder**

**Create and activate a virtual environment**

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
Install required packages

bash
Copy code
pip install -r requirements.txt
Create a .env file in the project root with your Gemini API key

bash
Copy code
GEMINI_API_KEY="your_google_gemini_api_key_here"
Run the Flask server

bash
Copy code
python app.py
Open your browser and visit:

cpp
Copy code
http://127.0.0.1:5000
Supported File Types
PDF (.pdf)

CSV (.csv)

Excel (.xlsx, .xls)

PowerPoint (.pptx, .ppt) — requires python-pptx
