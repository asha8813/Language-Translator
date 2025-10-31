Language Translator

A simple and interactive **Python-based Language Translator** that converts text from one language to another using the **Googletrans API**.  
It features a clean **Tkinter GUI**, supports **multiple languages**, and offers **text-to-speech** functionality for pronunciation assistance.

---

## 🚀 Features

- 🔤 Translate text between multiple languages  
- 🪄 Detect source language automatically  
- 🎧 Listen to translated text with text-to-speech  
- 🖥️ User-friendly GUI built with Tkinter  
- ⚡ Lightweight and runs locally on Python

---

## 🛠️ Technologies Used

| Component | Purpose |
|------------|----------|
| **Python 3** | Core programming language |
| **Tkinter** | GUI interface |
| **googletrans==4.0.0-rc1** | Translation engine |
| **playsound / gTTS** | Audio playback for translations |

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/asha8813/Language-Translator
   cd "Language Translator"
Create and activate a virtual environment

bash
Copy code
python -m venv .venv
.venv\Scripts\activate   # For Windows
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the application

bash
Copy code
python main.py
🧠 How It Works
The user enters text and selects source and target languages.

The app uses Googletrans to fetch the translation.

The result is displayed in real time in the output field.

Optionally, the playsound/gTTS feature plays the translated text aloud.

💡 Use Cases
Language learning and communication

Quick translations for students and travelers

Integration into chatbots or AI assistants

🖋️ Author
Aasha Vashist
🎓 B.Tech CSE (AI/ML) | AI & ML Enthusiast
🔗 LinkedIn | GitHub

🪪 License
This project is open source and available under the MIT License.
