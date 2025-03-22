# YouTube Video Summarizer

## 📌 Project Overview
The **YouTube Video Summarizer** is a web application that extracts transcripts from YouTube videos and generates concise, structured summaries using **Google Gemini AI**. This tool helps users quickly understand key points from long videos without watching them entirely.

## 🚀 Features
- **Extracts YouTube transcripts** automatically from videos with subtitles.
- **Summarizes key points** using Google Gemini AI.
- **User-friendly interface** built with Streamlit.
- **Displays video thumbnail** for a visual preview.
- **Fast & efficient summarization** (within 250 words).

## 🛠️ Tech Stack
- **Frontend & UI:** Streamlit
- **AI Model:** Google Gemini (gemini-2.0-flash)
- **Backend:** Python
- **APIs Used:**
  - Google Generative AI API
  - YouTube Transcript API
- **Environment Management:** dotenv (for API key security)

## 📌 How It Works
1. **User inputs a YouTube video link.**
2. **Transcript is fetched** using `youtube_transcript_api`.
3. **Google Gemini AI processes the transcript** with a predefined prompt.
4. **A structured summary is generated and displayed.**

## 🏗️ Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/YouTubeSummarizer.git
cd YouTubeSummarizer
```

### **2️⃣ Create & Activate Virtual Environment**
```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Set Up Environment Variables**
Create a `.env` file in the project root and add:
```plaintext
GOOGLE_API_KEY=your_google_gemini_api_key
```

### **5️⃣ Run the Application**
```bash
streamlit run app.py
```



## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---
### 🌟 If you found this project helpful, don't forget to ⭐ the repository!

