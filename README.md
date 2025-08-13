# 🎤 Murf AI Voice Tools

A FastAPI-based AI voice generation and transcription tool powered by **Murf API** and **AssemblyAI**.  
Includes text-to-speech, voice selection, audio history, and real-time transcription features.

---
## 🌐 Live Demo
The application is now hosted on **Render** and can be accessed here:  
🔗 [https://murf-ai-voice-tools.onrender.com](https://murf-ai-voice-tools.onrender.com)

---

## 🚀 Features
- ✅ Convert text to speech using Murf API  
- ✅ Multiple voice and accent options  
- ✅ Real-time transcription using AssemblyAI  
- ✅ Audio local download  
- ✅ Echo Bot mode (speak → transcribe → respond in AI voice)  
- ✅ Privacy-focused (no saving in `static/` directory)  
- ✅ Responsive frontend for smooth user experience  

---

## 🧰 Technologies Used
- **Python** (FastAPI)  
- **JavaScript** (Frontend)  
- **HTML + CSS**  
- **Murf API** (Text-to-Speech)  
- **AssemblyAI API** (Speech-to-Text)  

---

## 📂 Project Structure
```text
Murf-AI-Voice-Tools/
│
├── Screenshots/               # Project screenshots
│   ├── Main UI.png
│   ├── Text to Voice.png
│   ├── Voice Selection.png
│   └── Voice to Text.png
│
├── static/                    # Static assets
│   ├── favicon.png
│   └── style.css
│
├── templates/                 # HTML templates
│   └── index.html
│
├── .env                        # Environment variables (API keys, etc.)
├── main.py                     # Main Python application file
├── requirements.txt            # Python dependencies
```
---
## 📸 Screenshots
![Main UI](Screenshots/Main%20UI.png)
![Text to Voice](Screenshots/Text%20to%20Voice.png)
![Voice Selection](Screenshots/Voice%20Selection.png)
![Voice to Text](Screenshots/Voice%20to%20Text.png)

---

## ⚙️Configuration
**Update the .env file in the project root with your own API keys from Murf and AssemblyAI:**
- MURF_API_KEY=your_actual_murf_api_key
- ASSEMBLYAI_API_KEY=your_actual_assemblyai_api_key

**Important:**
- Keep the .env file private and never push it to GitHub.
- If deploying on Render, Heroku, or similar, add these keys in the platform’s environment variables settings instead of a .env file.

## 🛠️ How to Run

**1️⃣ Clone the repository**
```
git clone https://github.com/keerthana12hv/Murf-AI-Voice-Tools.git
cd Murf-AI-Voice-Tools
 ```
2️⃣ Install backend dependencies
```
pip install -r requirements.txt
```
3️⃣ Run the backend
```
uvicorn main:app --reload
```
4️⃣ Open frontend
- Open templates/index.html in your browser.

---
👩‍💻 Author
- J Keerthana
- 🔗 [GitHub Profile](https://github.com/keerthana12hv)
