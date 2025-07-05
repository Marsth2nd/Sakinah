<h1 align="center">🕊️ سكينة (Sakinah)</h1>
<h3 align="center">An AI-Powered Mental Health Chatbot for Men in the Middle East</h3>

<p align="center">
  <em>A culturally conscious digital companion for private, stigma-free mental health support.</em>
</p>

---

## 🧠 What is Sakinah?

**Sakinah (سكينة)** — Arabic for *tranquility* — is a web-based mental health chatbot designed to support **men in the Middle East** through AI-driven, emotionally intelligent conversations.  
It is built with the core intention of breaking the silence around men’s emotional wellbeing by providing a safe, anonymous, and culturally aware support system.

> 💡 Think of Sakinah as your digital confidant — built to listen, understand, and support.

---

## ✨ Core Features

✅ **Private & Anonymous Support**  
🌍 **Middle East Cultural Context Awareness**  
🧘 **AI-Powered Mental Health Guidance** *(coming soon)*  
💬 **Emotionally Intelligent Dialogue**  
📱 **Responsive UI with Tailwind CSS**  
📚 **Evidence-Based Mental Health Resources** *(planned)*  
🧑‍💻 **Admin Panel for Moderation & Customization** *(planned)*

---

## 🧰 Tech Stack Overview

| Layer        | Technology              |
|--------------|--------------------------|
| **Backend**  | Django (Python)          |
| **Frontend** | Tailwind CSS + HTML      |
| **Templating** | Django Templates       |
| **Database** | SQLite (default) → MySQL (planned upgrade) |
| **AI/NLP**   | OpenAI GPT (planned) + Local NLP models |

---

### ✅ Prerequisites

- [Python 3.10+](https://www.python.org/downloads/)
- [Node.js & npm](https://nodejs.org/) (for Tailwind CSS)
- A virtual environment manager (`venv`, `pipenv`, or `poetry`)

---
## 🚀 Quick Start

> Want to run Sakinah locally? Follow these steps:

```bash
# 1. Clone the repo
git clone https://github.com/Marsth2nd/Sakinah.git
cd Sakinah

# 2. Set up Python environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# 3. Set up Tailwind CSS
npm install
npx tailwindcss -i ./static/src/input.css -o ./static/css/output.css --watch

# 4. Run the server
python manage.py migrate
python manage.py runserver

