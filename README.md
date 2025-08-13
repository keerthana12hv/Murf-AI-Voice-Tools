🎤 Murf AI Voice Tools
A FastAPI-based AI voice generation and transcription tool powered by Murf API and AssemblyAI.
Includes text-to-speech, voice selection, audio history, and real-time transcription features.

🚀 Features
✅ Convert text to speech using Murf API
✅ Multiple voice and accent options
✅ Real-time transcription using AssemblyAI
✅ Audio local download
✅ Echo Bot mode (speak → transcribe → respond in AI voice)
✅ Privacy-focused (no saving in static/ directory)
✅ Responsive frontend for smooth user experience

🧰 Technologies Used
Python (FastAPI)
JavaScript (Frontend)
HTML + CSS
Murf API (Text-to-Speech)
AssemblyAI API (Speech-to-Text)

📂 Project Structure
Murf-AI-Voice-Tools/
│
├── Screenshots/              # Project screenshots
│   ├── Main UI.png
│   ├── Text to Voice.png
│   ├── Voice Selection.png
│   └── Voice to Text.png
│
├── static/                   # Static assets
│   ├── favicon.png
│   └── style.css
│
├── templates/                # HTML templates
│   └── index.html
│
├── .env                       # Environment variables (API keys, etc.)
├── main.py                    # Main Python application file
├── requirements.txt           # Python dependencies

🛠️ How to Run
1️⃣ Clone the repository:
git clone https://github.com/keerthana12hv/Murf-AI-Voice-Tools.git
cd Murf-AI-Voice-Tools

2️⃣ Install backend dependencies:
cd backend
pip install -r requirements.txt

3️⃣ Run the backend:
uvicorn main:app --reload

4️⃣ Open frontend/index.html in your browser.

👩‍💻 Author
J Keerthana
🔗 GitHub Profile

📜 License
This project is licensed under the MIT License.
