# 🤖 JAM – Python Voice Assistant

JAM is a simple Python-based artificial voice assistant that listens to voice commands and performs useful tasks like playing songs, telling the current time, searching Wikipedia, and telling jokes.  
This project demonstrates the integration of speech recognition, text-to-speech, and basic AI logic.

---

## ✨ Features

- 🎤 Voice command recognition
- 🔊 Text-to-speech responses
- 🎶 Play songs on YouTube
- ⏰ Speak current time
- 📚 Wikipedia search & summary
- 😂 Tell random jokes
- 💬 Fun conversational replies

---

## 🧠 How It Works

1. The assistant continuously listens through the microphone.
2. It activates when the keyword **"jam"** is spoken.
3. Speech is converted into text using Google Speech Recognition.
4. Commands are matched with predefined actions.
5. The assistant responds using text-to-speech.

---

## 🛠️ Technologies Used

- Python
- speech_recognition
- pyttsx3
- pywhatkit
- wikipedia
- pyjokes
- datetime

---

## 📦 Installation

### 1️⃣ Clone the repository
git clone https://github.com/your-username/jam-voice-assistant.git
cd jam-voice-assistant

###2️⃣ Install dependencies
pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes pyaudio

⚠️ Note:
Installing pyaudio may require additional setup on Windows.
Use:
pip install pipwin
pipwin install pyaudio

#### Run the assistant using: - python main.py
Example Voice Commands

"Jam play Believer"

"Jam what is the time"

"Jam who the heck is Elon Musk"

"Jam tell me a joke"

📌 Supported Commands
Command Phrase	Action
play	Plays song on YouTube
time	Tells current time
who the heck is	Wikipedia summary
joke	Tells a joke
date	Funny response
are you single	Fun response

🚀 Future Improvements

Weather updates

Open system applications

ChatGPT integration

GUI interface

Wake word customization

👨‍💻 Author

Ayush Ghai 
Python | AI/ML | Software Development
