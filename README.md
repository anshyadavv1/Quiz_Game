# 🗺️ Voice-Enabled U.S. States Quiz Game

An interactive Python game where users guess the U.S. states — now with voice assistant support! 🎤  
Built using the Turtle graphics module, this project combines visual interaction with speech recognition to make learning geography fun and engaging.

---

## 🎮 Features

- 🐢 Turtle-based map of the U.S.
- 🎤 Voice assistant integration (guess states by speaking!)
- 💬 Custom dialog box with microphone input
- 🧠 Keeps track of guessed and missed states
- 📋 Exports missed states to `states_to_learn.csv` for later study

---

## 🧰 Tech Stack

- Python 3.x
- `turtle` for graphics
- `speech_recognition` for voice input
- `pandas` for data handling
- `gTTS` and `playsound` for text-to-speech
- Custom GUI with `tkinter`

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/anshyadavv1/Quiz_Game.git
   cd Quiz_Game
(Optional but recommended) Create a virtual environment:

bash
Copy code
python -m venv .venv
.venv\Scripts\activate  # Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the game:

bash
Copy code
python state_quiz_with_Voice_Assistant.py
