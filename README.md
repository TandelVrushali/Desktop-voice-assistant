# 🎤 Desktop Voice Assistant in Python

A voice-activated desktop assistant built with Python that responds to 15+ voice commands.  
📖 [Read the full tutorial on Medium]()

## ✨ Features
| Command | Action |
|---------|--------|
| "What's the time?" | Speaks current time |
| "What's the date?" | Speaks current date |
| "Open YouTube/Google" | Opens in browser |
| "Search [topic] on Wikipedia" | Reads 2-sentence summary |
| "Search [query]" | Google search |
| "Play music" | Plays random local song |
| "Send email to [name]" | Sends email via SMTP |
| "Play game" | Opens game selector GUI |
| "How are you?" | Default conversation |
| "Exit" | Closes assistant |

## 🎮 Games (via tkinter GUI)
- 🐍 Snake
- 👻 Pac-Man
- 🧠 Simon Says
- 🃏 Memory

## 🏗️ Architecture
- **Speech Input** — `SpeechRecognition` + Google Speech API
- **Voice Output** — `pyttsx3` with SAPI5 (Microsoft Speech API)
- **GUI** — `tkinter` for game selection
- **Email** — `smtplib` with TLS (Gmail SMTP)
- **Games** — `freegames` library

## 🛠️ Tech Stack
Python 3 · pyttsx3 · SpeechRecognition · wikipedia · tkinter · smtplib · freegames

## 🚀 How to Run
```bash
git clone https://github.com/VrushaliTandel/desktop-voice-assistant.git
cd desktop-voice-assistant
pip install -r requirements.txt
python main.py
```

> **Note:** Requires a working microphone. On Windows, SAPI5 voices must be installed.
