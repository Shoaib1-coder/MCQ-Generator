# 🧠 AI MCQ Generator Web App

This Flask-based web application allows users to upload a document (`.pdf`, `.txt`, `.docx`) and automatically generates Multiple Choice Questions (MCQs) using Google Gemini AI. It outputs results in both `.txt` and `.pdf` formats.

---

## 🚀 Features

- Upload files in `.pdf`, `.txt`, or `.docx` format
- Extracts text from uploaded files
- Generates high-quality MCQs using Gemini 1.5 Pro
- Downloads MCQs in `.txt` and `.pdf` formats
- Clean web interface built with HTML/CSS

---

## 📁 Project Structure

```
mcq_generator_app/
│
├── api/                       # Backend logic (app.py lives here)
├── static/                    # Static files like CSS
├── templates/                 # HTML templates (index.html, results.html)
├── uploads/                   # Uploaded documents
├── results/                   # Generated MCQs (PDF/TXT)
├── index.py                   # Main Flask application
├── requirements.txt           # Python dependencies
└── vercel.json                # Vercel deployment config
```

---

## 📌 Technologies Used

- **Flask** – Web framework
- **Google Gemini 1.5 Pro** – Text generation
- **pdfplumber** – Extract text from PDFs
- **python-docx** – Read `.docx` files
- **FPDF** – Generate PDF output
- **HTML/CSS** – Frontend interface

---

## 🔧 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Shoaib1-coder/mcq-generator-app.git
cd mcq-generator-app
```

### 2. Create a virtual environment (optional but recommended)
   # Make sure Anaconda is installed: https://www.anaconda.com/products/distribution
   # Anaconda Prompt open
   # Create a new environment named 'mcqs' with Python 3.10

```bash

conda create --name mcqs python=3.10

# Activate the environment
conda activate mcqs

```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up your Google API key

Make sure your environment has:

```bash
export GOOGLE_API_KEY=your_api_key_here
```

Or set it in your terminal or `.env` file.

---

## ▶️ Run the App

```bash
python index.py
```

Then visit:  
📍 `http://127.0.0.1:5000/`

---

## 📤 How to Use

1. Open the app in your browser
2. Upload a `.pdf`, `.txt`, or `.docx` file
3. Enter the number of MCQs you want
4. Click **Generate**
5. View MCQs in your browser and download as `.txt` or `.pdf`

---

## 📄 Sample Output Format

```
## MCQ
Question: What is Python?
A) A kind of snake
B) A programming language
C) A planet
D) A browser
Correct Answer: B
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Muhammad Shoaib Sattar**  
📧 Email: mshoaib3393@gmail.com  
🔗 GitHub: [shoaib1-coder](https://github.com/shoaib1-coder)
