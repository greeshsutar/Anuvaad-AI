# ANUVAAD.AI 🌐
### *Not just words. Meaning.*

> AI-powered platform to Translate, Summarize & Listen across English, Hindi, Marathi and Kannada.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.x-black?style=flat-square&logo=flask)
![HuggingFace](https://img.shields.io/badge/HuggingFace-BART-yellow?style=flat-square&logo=huggingface)
![Google Translate](https://img.shields.io/badge/Google-Translate-blue?style=flat-square&logo=googletranslate)
![gTTS](https://img.shields.io/badge/gTTS-Text--to--Speech-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=flat-square)

---

## ✨ What is ANUVAAD.AI?

**ANUVAAD.AI** is an intelligent language platform that breaks communication barriers.  
Upload any text or PDF, choose your language, and get an instant translation, a concise AI summary, and an audio output — all in one seamless workflow.

> **Anuvaad** (अनुवाद) means *Translation* in Hindi & Sanskrit.  
> **Har Bhasha, Ek Awaaz** — Every Language, One Voice.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| 🌐 **Smart Translation** | Translate between English, Hindi, Marathi & Kannada |
| ✦ **AI Summarization** | Powered by Facebook's BART model |
| 🎧 **Text-to-Speech** | Listen to translated & summarized content |
| 📄 **File Upload** | Supports TXT and PDF file input |
| ⚡ **Fast & Simple** | No login required — just paste and go |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| Summarization | Facebook BART (`facebook/bart-large-cnn`) |
| Translation | Google Translate API (`deep-translator`) |
| Text-to-Speech | gTTS |
| PDF Extraction | PyPDF2 |
| Frontend | HTML, CSS (Outfit font, custom design) |
| Deployment | Render / Gunicorn |

---

## 📁 Project Structure
```
Anuvaad-AI/
│
├── templates/
│   ├── home.html
│   ├── index.html        # Translate page
│   ├── about.html
│   ├── support.html
│   └── developer.html
│
├── static/
│   └── style.css
│
├── uploads/              # Uploaded files (auto-created)
├── output/               # Audio output (auto-created)
│   └── output.mp3
│
├── app.py                # Main Flask app
├── wsgi.py               # Production entry point
├── requirements.txt
├── Procfile
└── README.md
```

---

## ⚙️ Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/Anuvaad-AI.git
cd Anuvaad-AI
```

**2. Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the app**
```bash
python app.py
```

**5. Open in browser**
```
http://127.0.0.1:5000
```

---

## 📦 Requirements
```
flask
deep-translator
transformers
torch
gtts
PyPDF2
werkzeug
gunicorn
```

---

## 🌍 Supported Languages

| Language | Code |
|----------|------|
| English  | `en` |
| Hindi    | `hi` |
| Marathi  | `mr` |
| Kannada  | `kn` |

---

## 👨‍💻 Developer

**Greesh Sutar** — Founder & Lead Developer  
📧 girishasutar223@gmail.com

Built with passion for making AI accessible to everyone —  
especially for Indian language speakers. 🇮🇳

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify and distribute.

---

<div align="center">

**ANUVAAD.AI** — *Har Bhasha, Ek Awaaz* 🌐

</div>