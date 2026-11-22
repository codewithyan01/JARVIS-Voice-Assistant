# JARVIS Voice Assistant 🤖

A Python-based voice-controlled desktop assistant inspired by JARVIS.  
It can recognize voice commands, speak responses, and perform basic system and web tasks.

---

## 🚀 Features

- 🎤 Voice command recognition (wake word: "Jarvis")
- 🗣️ Text-to-speech responses using Edge-TTS
- ⏰ Time and date information
- 👋 Smart time-based greetings (morning/afternoon/evening/night)
- 🌐 Open websites (YouTube, Google, etc.)
- 📰 Fetch latest news headlines
- 🔋 Battery status check
- 😂 Tell random jokes
- 📸 Screenshot capture

---



📦 Requirements
edge-tts
playsound==1.2.2
speechrecognition
pyaudio
requests
wikipedia
pyjokes
psutil
pyautogui


▶️ How to Run
python main.py

Then say:

Jarvis

and give commands like:

“What’s the time?”
“Tell me the date”
“Open YouTube”
“Give me news”
## What I learned

- integrating speech-to-text and text-to-speech into one working pipeline
- handling failed or unclear speech recognition without crashing the assistant
- structuring commands in a modular way so new features can be added without rewriting the main program

## Limitations

- requires an internet connection for speech recognition and the OpenAI API
- Windows-focused
- no offline mode
