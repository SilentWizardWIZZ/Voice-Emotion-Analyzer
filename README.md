🎤 Voice Emotion Analyzer
A browser-based Voice Emotion Analyzer that detects emotions from a user's voice input using HTML, CSS, and JavaScript. This project can be used for experiments in emotion recognition, AI-assisted interfaces, or interactive web experiences.

📋 Features
🎙️ Real-time voice input through the microphone

🧠 Emotion analysis based on audio tone (simulated or via API)

😊 Detects emotions like Happy, Sad, Angry, Neutral, etc.

💻 Runs entirely in the browser — no installation required

🎨 Customizable UI with CSS

🚀 How to Use
Download or Clone the Repository

bash
Copy
Edit
git clone https://github.com/SilentWizardWIZZ/voice-emotion-analyzer-html.git
Open index.html in a browser

Grant microphone access when prompted.

Click the "Start" button to begin recording.

The app will analyze your voice and display an emotion result.

To Embed on a Website


🛠️ How It Works
Uses the Web Speech API (webkitSpeechRecognition) to capture voice.

Audio data is analyzed using predefined tone keywords or (optionally) a cloud-based emotion detection API.

The emotion result is displayed visually on the screen.

🔧 Customization Tips
Edit script.js to tweak emotion logic or connect an external API.

Replace placeholder logic with machine learning models or APIs for more accurate emotion detection.

Modify UI in style.css to match your brand/theme.

⚠️ Limitations
Basic implementation may not reflect accurate emotional states.

For true voice emotion recognition, consider integrating APIs like:

Microsoft Azure Emotion API

IBM Watson Tone Analyzer

Deepgram or AssemblyAI with emotion detection

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Inspired by voice-based AI and emotion AI research

Thanks to the Web Speech API for enabling voice input in browsers

![image](https://github.com/user-attachments/assets/ff8c8c9a-080d-40bf-9fac-26bebd5e8cb8)


Include all files in your project directory.

Add <iframe> or chatbot-style popup to launch it.


