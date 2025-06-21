# 🧠 Auto MCQ Generator using Groq LLM & LangChain

An AI-powered web and desktop application that automatically generates Multiple Choice Questions (MCQs) from uploaded text-based files (PDF, DOCX, or TXT) using Groq’s ultra-fast LLMs and LangChain.

---

## 🚀 Screenshots

> 📸 Interface Preview

![Screenshot 1](https://github.com/user-attachments/assets/c111a947-31ec-4a3f-a11a-b6236047b98c)
![Screenshot 2](https://github.com/user-attachments/assets/8c30af62-d347-4e22-865b-c7c5f698bd89)
![Screenshot 3](https://github.com/user-attachments/assets/ac370dae-56f7-40ae-8038-b352081aa01f)

---

## ✨ Features

- 📤 Upload PDF, DOCX, or TXT files
- 🔢 Choose the number of MCQs to generate
- ⚡ Real-time MCQ generation using LLaMA 3 or Mixtral via Groq
- 💾 Download questions as `.txt` or `.pdf`
- 🎨 Clean, responsive UI built with Bootstrap
- 🧱 Powered by LangChain & Groq's blazing-fast LLM

---

## 🧠 Tech Stack

- **Python**
- **Flask**
- **LangChain**
- **Groq API** (`llama-3-70b`, etc.)
- **FPDF**
- **pdfplumber**
- **python-docx**
- **Bootstrap 5**

---

## 🖥️ How It Works

1. **Upload** a learning content file (PDF, DOCX, or TXT)
2. **Enter** the number of questions
3. **Processing** is done using LangChain + Groq LLM
4. **Download** your generated MCQs as `.txt` or `.pdf`

---

## 📁 Project Structure

```bash
📦 mcq-generator/
├── app.py               # Flask web app
├── main.py              # Standalone CLI version
├── templates/
│   ├── index.html       # Upload form
│   └── results.html     # Display and download MCQs
├── uploads/             # Uploaded input files
├── results/             # Output files (MCQs in PDF/TXT)
├── static/              # (Optional) For assets like CSS/images
└── README.md            # You're here
# 1. Clone the repository
git clone https://github.com/Yogeshkharb111/Auto-MCQ-Generator-from-Text-PDF-using-Groq-s-LLM-LangChain.git
cd Auto-MCQ-Generator-from-Text-PDF-using-Groq-s-LLM-LangChain

# 2. (Optional) Create a virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your Groq API key in app.py
api_key="gsk_your_actual_key"
  # Run Flask app
python app.py
