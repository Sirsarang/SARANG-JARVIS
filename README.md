# 🤖 Jarvis AI – Your Personal Desktop Assistant

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)


---

## 🚀 Overview

**Jarvis AI** is a **desktop-based intelligent AI assistant** built with **Python** and **OpenAI GPT-4o-mini**. Inspired by Iron Man’s Jarvis, it enables you to:

- Chat naturally with AI  
- Respond to **voice commands**  
- Open websites and desktop apps  
- Play local music files  
- Announce the **current time**  
- Save AI responses to files  
- Gracefully handle OpenAI quota limits  

Jarvis runs on macOS using the `say` command for voice output and is **extensible to Windows/Linux** with minor adjustments.

---

## 🌟 Key Features

| Feature | Description |
|---------|-------------|
| 💬 AI Chat | Chat with GPT-4o-mini for conversation or guidance |
| 🎤 Voice Commands | Speak to Jarvis for hands-free control |
| 🌐 Web Launcher | Open YouTube, Google, Wikipedia, or custom sites |
| 🎵 Music Player | Play local audio files instantly |
| 🕒 Time Teller | Get the current time in voice format |
| 🗂 Save Responses | Store AI responses to text files |
| 🔄 Reset Chat | Clear conversation history anytime |
| ⚠️ Quota Handling | Friendly message when API quota is exceeded |

---

## 🛠 Technology Stack

- **Python 3.10+**  
- **OpenAI GPT-4o-mini** for AI responses  
- **SpeechRecognition** for microphone input  
- **MacOS say command** for voice output  
- **Random & Datetime** for file management & time features  

---

## 🎨 Demo

### Chat & Voice Interaction:

![Jarvis Chat Demo](assets/demo.gif)  

> Jarvis listens, responds, and executes commands seamlessly.

---

💻 Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/JarvisAI.git
cd JarvisAI
2️⃣ Create Virtual Environment
python3 -m venv .venv
# Activate the environment:
# Mac/Linux
source .venv/bin/activate
# Windows
.venv\Scripts\activate

