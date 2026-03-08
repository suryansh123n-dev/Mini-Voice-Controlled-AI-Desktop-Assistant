Mini – Voice Controlled AI Desktop Assistant 🤖🎤

Mini is a Python-based voice controlled desktop assistant that performs multiple tasks using speech recognition, natural language processing, and automation. The assistant listens for the wake word “Mini”, understands the user's command, and executes actions such as opening applications, playing YouTube videos, checking weather, sending emails, and controlling system functions.

This project demonstrates the integration of AI, APIs, and system automation to build a smart personal assistant similar to Siri, Alexa, or Google Assistant.

Features 🚀

🎤 Wake word activation ("Mini")

🗣️ Speech recognition and voice response

▶️ Play YouTube videos using voice commands

💻 Open desktop applications (Chrome, Notepad, VS Code, etc.)

🌦️ Weather updates using OpenWeather API

📰 Latest news headlines using News API

📧 Send emails via SMTP

🧮 Voice-based calculator

📸 Take screenshots automatically

📝 Write notes automatically in Notepad

⏰ Reminder system with memory storage

🔊 Volume control

🖥️ System control (shutdown, restart, lock)

📊 System status monitoring (CPU and battery)

🧠 AI-based intent detection using Hugging Face Transformers

Tech Stack 🛠️

Python

SpeechRecognition

pyttsx3

pywhatkit

pyautogui

psutil

transformers (Hugging Face)

OpenWeather API

News API

SMTP Email Automation

Project Structure 📁
mini-ai-assistant
│
├── mini_assistant.py
├── memory.json
├── screenshot.png
├── requirements.txt
└── README.md
Installation ⚙️
1️⃣ Clone the repository
git clone https://github.com/yourusername/mini-ai-assistant.git
2️⃣ Navigate to project folder
cd mini-ai-assistant
3️⃣ Install required dependencies
pip install -r requirements.txt
4️⃣ Run the assistant
python mini_assistant.py
Example Commands 🎙️

You can interact with the assistant using commands like:

Mini open chrome

Mini play music on YouTube

Mini tell me the weather

Mini take a screenshot

Mini set a reminder

Mini tell me a joke

Mini shutdown system

Mini send email

APIs Used 🔑

This project uses external APIs:

OpenWeather API → Weather updates

News API → Latest news headlines

You need to replace the API keys in the code with your own keys.

Security Note ⚠️

Do not upload sensitive information such as:

Email passwords

API keys

Instead, store them using environment variables.

Future Improvements 🚧

GUI interface

Offline speech recognition

WhatsApp automation

Face recognition login

Smart home integration

Improved AI model

Author 👨‍💻

Suryansh Sharma
B.Tech CSE (Data Science)
Chandigarh University

Email: suryansh123n@gmail.com

License 📄

This project is licensed under the MIT License.
