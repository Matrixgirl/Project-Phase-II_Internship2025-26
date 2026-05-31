1. 🎤 Audio Transcription
Uses Faster Whisper model for accurate speech-to-text conversion
Handles long audio files (30–40 minutes)
2. 🧩 Smart Segmentation
Splits audio into meaningful segments
Groups similar content using semantic similarity
3. 📝 Automatic Summarization
Generates concise bullet-point summaries
Uses transformer-based summarization model
4. 😊 Sentiment Analysis
Classifies segments into:
Positive 😊
Neutral 😐
Negative 😞
5. 🔑 Keyword Extraction
Extracts important keywords using YAKE algorithm
6. 📊 Data Visualization
Segment timelines
Sentiment graphs
Keyword frequency charts
7. ☁️ Word Cloud
Visual representation of most frequent words
8. 💬 AI Chatbot
Ask questions related to uploaded podcast
Retrieves most relevant answers using embeddings
9. 🔴 Live Captioning
Displays real-time captions synced with audio playback
Uses timestamp-based synchronization
10. 📥 Export Functionality
Download results as CSV file
🛠️ Tech Stack
🔹 Backend
Python
Flask
🔹 AI / ML Models
Faster Whisper (Speech-to-Text)
Sentence Transformers (Semantic Search)
Transformers (Summarization)
TextBlob (Sentiment Analysis)
YAKE (Keyword Extraction)
🔹 Frontend
HTML, CSS, JavaScript
Jinja2 Templates
🔹 Other Tools
FFmpeg (Audio processing)
WordCloud (Visualization)
📁 Project Structure
finalpro/
│── app.py
│── templates/
│   ├── home.html
│   ├── upload.html
│   ├── dashboard.html
│   ├── live_transcribe.html
│   └── chatbot.html
│── static/
│   ├── audio/
│   ├── css/
│   └── js/
│── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone <your-repo-link>
cd finalpro
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Install FFmpeg

Make sure FFmpeg is installed and added to PATH:

ffmpeg -version
4️⃣ Run the application
python app.py
5️⃣ Open in browser
http://127.0.0.1:5000/
📌 How It Works
User uploads podcast audio 🎧
Audio is transcribed using Whisper 🧠
Text is segmented and analyzed 📊
Dashboard displays insights 📈
Audio playback shows live captions 🔴
User can interact via chatbot 💬
🎯 Use Cases
Podcast analysis
Lecture transcription
Meeting summarization
Content understanding
Accessibility (live captions)
⚠️ Limitations
Works best with clear audio
CPU-based processing may be slower
Very long audio may take time to process
🔮 Future Improvements
GPU acceleration for faster processing ⚡
Real-time streaming transcription 🎙
Multi-language support 🌍
Speaker diarization 👥
Cloud deployment ☁️
👩‍💻 Author

Aditi Chintawar
Computer Engineering Student (2026 Batch)

📜 License

This project is for academic purposes.

⭐ Conclusion

This project demonstrates how AI can be used to automate audio understanding, improve accessibility, and provide intelligent insights from podcasts.