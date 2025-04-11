**Smart Education Solution - Final Hackathon
Project Report
Project Objective:**
__To design a smart, inclusive, and multilingual educational platform aligned with NEP2020. The goal is to improve learning engagement, ensure inclusivity through language support, offer real-time assessments, and protect online classrooms from abuse.
Problem Statements Solved:__

1. Lack of real-time engagement and gamification in online assessments.
2. Difficulty in understanding content due to language barriers.
3. No real-time translation available in educational videos and audio.
4. Unsafe online learning spaces prone to abusive behavior.


**Main Features:**

**1. Smart Assessment Board:**
Gamified quiz system for fun learning
Teachers can create and assign quizzes
• Real-time scoring system
Voice or touch-based answering

__Dashboard for teachers to track progress__

**Quiz translation into students' mother tongues using Indic Trans2**
Backend with Firebase or Flask and proper authentication

**Text Language Translator:**

• **Input:** English/Hindi
•**Output:** Translated text in regional languages
**Models Used:** Whisper for speech-to-text and Indic Trans2 for translation

Shows both original and translated text

Beautiful and clean UI layout

**Audio & Video Translation Module:**
• Upload or paste link of video/audio
• Auto transcription + translation + subtitle generation
• Optional Al voice dubbing with Coqui TTS
• FFmpeg used for audio/video processing
• Displays both original and translated versions side-by-side

**Online Meeting Protection Feature:**

Connect with Google Meet or Zoom
Detects abusive language in chat and voice
Alerts host and blocks abusers in real-time
Ensures a safe online classroom environment

**Tech Stack Used:**

**Frontend:** React.js, Tailwind CSS, Chart.js, Framer

Motion

**Backend:** Flask or FastAPI, Node.js (optional)

**Database/Storage:** Firebase, Flask-SQLAlchemy,

**AWS S3**

**AI/NLP:** Whisper, Indic Trans2, spaCy, Coqui TTS

**Audio/Video:** FFmpeg, OpenCV

**Others:** Tesseract OCR, Redis, PWA support

**How the UI Works:**

Homepage contains four animated laptop screens in staircase layout
Each laptop represents a feature

**On click:** animation plays message shows "Logging in..." → feature Ul appears

Clean beach brown background

**Scroll and click-based animations**
• Responsive and fast design

Installation Instructions (for developers):

1. Clone the project
2. Run frontend:
Go to frontend folder

**Run: npm install
Then: npm run dev**

3. **Run backend:**

Go to backend folder

**Run: pip install -r requirements.txt**

•**Then: python app.py**

**Possible Future Enhancements:**

**Offline PWA mode**

__• Integration with LMS
Al-based quiz level adaptation
Facial detection during quiz
• Voice cloning for more personalized dubbing
• Export reports in PDF/Excel for teachers__
