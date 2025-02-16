# AI Assistant – Python Voice Assistant  

An AI-powered voice assistant built with Python that can perform tasks like web search, open applications, play music, send emails, and more using speech recognition and text-to-speech synthesis.  

## Features  
- Voice Recognition (Google Speech API)  
- Text-to-Speech (TTS) (pyttsx3)  
- Wikipedia Search  
- Open Websites (Google, YouTube, Stack Overflow, etc.)  
- Play Music from Local Directory  
- Open Notepad or Other Applications  
- Send Emails (via SMTP)  
- Tell the Current Time  

## Folder Structure  
```
AI-Assistant/
│── main.py                # Main script for AI Assistant
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
│── assets/                # (Optional) Store icons, images, etc.
```  

## Installation  

### Step 1: Clone the Repository  
```
git clone https://github.com/AnishKanojia/AI-assistant-.git
cd AI-assistant-
```  

### Step 2: Create a Virtual Environment (Recommended)  
```
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```  

### Step 3: Install Dependencies  
```
pip install -r requirements.txt
```  

### Step 4: Run the AI Assistant  
```
python main.py
```  

## Usage  
- Run `main.py`  
- Speak a command like:  
  - "Open YouTube" → Opens YouTube in the browser  
  - "What is AI? Wikipedia" → Fetches a Wikipedia summary  
  - "Play music" → Plays a random song from a folder  
  - "Email to Anish" → Sends an email  

## Deployment  

You can deploy this project using Render, Railway, or Heroku.  

### Deploy on Render (Recommended)  
1. Create a `requirements.txt` file with the following dependencies:  
   ```
   pyttsx3
   SpeechRecognition
   wikipedia
   webbrowser
   os-sys
   smtplib
   ```  
2. Push to GitHub and connect your repo to Render  
3. Set the build command:  
   ```
   pip install -r requirements.txt
   ```  
4. Set the start command:  
   ```
   python main.py
   ```  
5. Click Deploy → Done  

### Deploy on Railway  
1. Install the Railway CLI:  
   ```
   npm i -g @railway/cli
   ```  
2. Log in to Railway:  
   ```
   railway login
   ```  
3. Deploy the project:  
   ```
   railway init
   railway up
   ```    
## Contributors  
- Anish Kanojia - [GitHub](https://github.com/AnishKanojia)  

## Next Steps  
- Host on a server (Flask API + Frontend)  
- Convert into a mobile app (Kivy for Android)  
- Add more AI-powered features  
```
```
git add README.md
git commit -m "Added complete README.md"
git push origin main
```  
