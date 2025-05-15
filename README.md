![Screenshot 2025-05-15 202157](https://github.com/user-attachments/assets/ba1571df-ad28-4fd5-b593-881643222101)Voice Assistant  Pro 🎙️


![image](https://github.com/user-attachments/assets/1d81c399-96b2-441c-9d26-fd101a11c1ca)

A Python-based voice assistant with a modern GUI, capable of executing voice/text commands, managing custom actions, and integrating with APIs like OpenAI and weather services.
Features ✨
Voice Interaction

Speech-to-text using speech_recognition

Text-to-speech responses via pyttsx3

Custom Commands

Add/remove custom voice triggers (phrases + responses/URLs)

Persistent storage (JSON)

Built-in Functions

 Tell time/date

 Open websites (Google, Facebook, etc.)

 Play local music files

 Fetch real-time weather (Open-Meteo API)

 AI responses (OpenAI GPT-3.5 integration)

Modern UI (Tkinter)

Dynamic background

Command history log

Voice/speed settings

Installation ⚙️
Clone the repository:

bash
git clone https://github.com/your-username/voice-assistant-advanced-pro.git  
cd voice-assistant-advanced-pro  
Install dependencies:

bash
pip install -r requirements.txt  
Run the application:

bash
python main.py  
Configuration 🔧
OpenAI API (Optional):

Get an API key from OpenAI

Add it to the code where openai.ChatCompletion is called.

Custom Commands:

Edit va_custom_commands.json to add/remove commands.

Usage Examples 🎯
Voice Command: Say "What time is it?" → Assistant responds with current time.

Custom Action: Add a command "open news" to launch https://news.google.com.

Weather Check: Say "weather London" → Gets temperature/wind speed.

Project Structure 📂
voice-assistant-advanced-pro/  
├── main.py                # Main application script  
├── va_settings.json       # User settings (voice, speed)  
├── va_custom_commands.json # Custom commands database  
├── requirements.txt       # Dependencies  
└── assets/                # Screenshots/GIFs  
Contributing 🤝
Pull requests welcome! For major changes, open an issue first.

License 📜
MIT
