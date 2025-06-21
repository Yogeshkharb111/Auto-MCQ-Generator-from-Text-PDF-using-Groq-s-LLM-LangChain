# 🧠 Auto MCQ Generator using Groq LLM & LangChain

An AI-powered web and desktop application that automatically generates Multiple Choice Questions (MCQs) from uploaded text-based files (PDF, DOCX, or TXT) using Groq’s ultra-fast LLMs and LangChain.

---
## 🚀 Screenshot

![MCQ Generator Screenshot](![image](https://github.com/user-attachments/assets/c111a947-31ec-4a3f-a11a-b6236047b98c)
)
![MCQ Generator Screenshot](![image](https://github.com/user-attachments/assets/8c30af62-d347-4e22-865b-c7c5f698bd89)
)
![MCQ Generator Screenshot](![image](https://github.com/user-attachments/assets/ac370dae-56f7-40ae-8038-b352081aa01f)
)


## 🚀 Features

- 📤 Upload PDF, DOCX, or TXT files
- ⚙️ Choose number of MCQs to generate
- ✨ Real-time MCQ generation using LLaMA 3 / Mixtral via Groq
- 💾 Download output as `.txt` or `.pdf`
- 🌐 User-friendly interface with Bootstrap (Flask)
- 🧱 Powered by LangChain & Groq’s blazing-fast API

---

## 🧠 Tech Stack

- **Python**
- **Flask**
- **LangChain**
- **Groq API** (`llama-3.3-70b-versatile`)
- **FPDF**
- **pdfplumber**
- **docx**
- **Bootstrap 5**

---

## 🖥️ How It Works

1. **Upload** a document containing learning material (PDF, DOCX, TXT)
2. **Enter** the number of questions to generate
3. **Process** happens via LangChain + Groq LLM
4. **Download** the generated MCQs as `.txt` or `.pdf`

---

## 📁 Project Structure

📦 mcq-generator/
│
├── app.py # Flask app (web version)
├── main.py # Standalone script for direct MCQ generation
├── templates/
│ ├── index.html # Upload form UI
│ └── results.html # Output & download links
├── uploads/ # Uploaded user files
├── results/ # Generated output files (.txt & .pdf)
└── README.md # You're here 


---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/Yogeshkharb111/Auto-MCQ-Generator-from-Text-PDF-using-Groq-s-LLM-LangChain

cd mcq-generator

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install required packages
pip install -r requirements.txt


api_key="gsk_your_actual_key"

