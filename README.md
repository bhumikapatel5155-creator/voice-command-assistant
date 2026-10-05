# Voice Command Assistant 🎙️

A Python-based voice command assistant that listens to spoken commands, converts them into text, and performs useful actions such as web searches, opening applications, retrieving information from Wikipedia, and responding with voice.

## 🚀 Features

- 🎤 Voice command recognition
- 🔊 Text-to-speech responses
- 👋 Personalized greeting based on the time of day
- 🌐 Open Google, YouTube, and GitHub using voice commands
- 🔎 Search Google using voice commands
- ▶️ Search and play content on YouTube
- 📚 Get information from Wikipedia
- ⏰ Tell the current time
- 💻 Open applications such as:
  - Notepad
  - Calculator
  - Microsoft Edge
  - Microsoft Word
  - Microsoft Excel
- ❌ Exit the assistant using a voice command

## 🛠️ Technologies Used

- Python
- SpeechRecognition
- PyAudio
- pyttsx3
- Wikipedia API
- Webbrowser
- Regular Expressions
- OS module

## 📂 Project Structure

```text
voice-command-assistant/
│
├── README.md
└── speechreco.py
⚙️ Installation
1. Clone the repository
git clone https://github.com/bhumikapatel5155-creator/voice-command-assistant.git

2. Navigate to the project directory
cd voice-command-assistant

3. Install the required packages
pip install SpeechRecognition
pip install PyAudio
pip install pyttsx3
pip install wikipedia

▶️ How to Run
Run the Python file:
python speechreco.py

Make sure your microphone is connected and accessible.
🎯 Example Voice Commands
You can try commands such as:
"Open YouTube"
"Open Google"
"Open GitHub"
"Search for Python programming"
"What time is it"
"Search Wikipedia for Artificial Intelligence"
"Play Python tutorial on YouTube"
"Open Notepad"
"Open Calculator"
"Exit"

🔄 How It Works
Voice Input
     ↓
Microphone
     ↓
Speech Recognition
     ↓
Convert Speech → Text
     ↓
Process Command
     ↓
Perform Requested Action
     ↓
Text-to-Speech Response
     ↓
Voice Output

📌 Requirements
- Python 3.x
- Working microphone
- Internet connection for speech recognition, Wikipedia, and web searches
- Required Python libraries installed
🔮 Future Improvements
- Add a graphical user interface (GUI)
- Add more voice commands
- Improve error handling
- Add customizable wake words
- Add support for multiple languages
- Add weather and news APIs
- Add AI-powered conversational responses
- Add more system automation features
👩‍💻 Author
Bhumika Patel
GitHub: @bhumikapatel5155-creator
⭐ If you find this project useful, consider giving it a star!

### Then save it

In VS Code:

**`README.md` → Ctrl+A → paste the above → Ctrl+S**

Then **don't commit yet**.

We should do this professionally using a **new feature branch**, because you just learned the PR workflow. Next we'll do:

```text
main
 ↓
git checkout -b improve-readme
 ↓
edit README
 ↓
git add
 ↓
git commit
 ↓
git push
 ↓
Pull Request
 ↓
Merge → main