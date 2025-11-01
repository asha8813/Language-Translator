<<<<<<< HEAD
\# 🗣️ Real-Time Speech-to-Text Language Translator



The \*\*Real-Time Speech-to-Text Language Translator\*\* is a Python-based application that listens to speech through a microphone, converts it into text, translates it into another language, and optionally speaks out the translated output — all in real time.  



It combines \*\*Speech Recognition\*\*, \*\*Translation\*\*, and \*\*Text-to-Speech (TTS)\*\* technologies to make multilingual communication effortless and natural.  

Designed with an interactive \*\*Tkinter GUI\*\*, this tool provides smooth and user-friendly translation experiences for live conversations, presentations, or language learning.



---



\## 🚀 Features



\- 🎤 \*\*Real-Time Speech Recognition\*\* – Converts your spoken words into text instantly.  

\- 🌍 \*\*Language Translation\*\* – Translates recognized text into the selected target language using Google Translate API.  

\- 🔊 \*\*Speech Output\*\* – Speaks the translated text aloud using text-to-speech.  

\- 🪄 \*\*Interactive GUI\*\* – Built with Tkinter for simple and intuitive user interaction.  

\- ⚡ \*\*Lightweight \& Fast\*\* – Works locally and requires minimal resources.  



---



\## 🛠️ Technologies Used



| Component | Purpose |

|------------|----------|

| \*\*Python 3\*\* | Core programming language |

| \*\*SpeechRecognition\*\* | Captures and processes voice input |

| \*\*googletrans==4.0.0-rc1\*\* | Handles language translation |

| \*\*gTTS / playsound\*\* | Converts translated text to audio output |

| \*\*Tkinter\*\* | Provides GUI interface |



---



\## 📦 Installation



1\. \*\*Clone the repository\*\*

&nbsp;  ```bash

&nbsp;  git clone https://github.com/<your-username>/RealTime-Speech-Translator.git

&nbsp;  cd "RealTime-Speech-Translator"

Create and activate a virtual environment



bash

Copy code

python -m venv .venv

.venv\\Scripts\\activate   # For Windows

\# or

source .venv/bin/activate  # For macOS/Linux

Install dependencies



bash

Copy code

pip install -r requirements.txt

Run the application



bash

Copy code

python main.py

🧠 How It Works

The app continuously listens to the user’s speech via the microphone.



The SpeechRecognition library converts the audio input to text.



The recognized text is sent to Googletrans for translation.



The translated text is displayed in the GUI and optionally spoken aloud using gTTS/playsound.



💡 Use Cases

Live multilingual meetings or events



Real-time communication with foreign-language speakers



Language learning and pronunciation practice



Accessibility tool for hearing or language-impaired users



🖋️ Author

Aasha Vashist

🎓 B.Tech CSE (AI/ML) | AI \& ML Enthusiast

💬 Passionate about building intelligent, human-centered applications

🔗 LinkedIn | GitHub



🪪 License

This project is open source and available under the MIT License.

=======
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
>>>>>>> 9f8500f69deaeb58286007bdc4304ad56d55af85
