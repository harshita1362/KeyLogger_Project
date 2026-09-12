🔐 KeyLogger Project

A Python-based Keyboard Event Monitoring project built with Tkinter and pynput to demonstrate keyboard event handling, GUI integration, and file-based logging.

«⚠️ Educational Use Only: This project is intended for cybersecurity learning and controlled lab environments. Use only on systems and applications where you have explicit permission.»

✨ Features
- 🖥️ Simple Tkinter-based GUI
- ⌨️ Keyboard event detection using "pynput"
- 📝 Event logging to text format
- 📦 JSON-based event storage
- 🔄 Press and release event tracking
- 🐍 Built entirely with Python

🛠️ Tech Stack
- Python
- Tkinter
- pynput
- JSON

📂 Project Structure

KeyLogger/
├── keylogger.py
├── logs.txt
├── logs.json
└── README.md

⚙️ How It Works

User Interaction
       ↓
Tkinter GUI
       ↓
Keyboard Event Listener
       ↓
Press / Release Events
       ↓
Event Processing
       ↓
TXT / JSON Logging

The application initializes a Tkinter interface and uses "pynput" to detect keyboard events. Detected events are processed and stored in structured formats for analysis.

🚀 Getting Started
1. Clone the repository
git clone <your-repository-url>
cd KeyLogger

2. Install dependency
pip install pynput

3. Run
python keylogger.py

🎯 Learning Objectives
This project demonstrates:
- Keyboard event handling
- Python GUI development
- Event-driven programming
- JSON file handling
- Basic cybersecurity concepts
- Python library integration

⚠️ Disclaimer
This project is created strictly for educational and authorized security-testing purposes. Do not use it to monitor other people's activity, credentials, or private information without explicit authorization.

👩‍💻 Author

Harshita
Cybersecurity Enthusiast | Python | Linux | Machine Learning

⭐ If you find this project useful, consider giving it a star!
