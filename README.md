🎥 AI YouTube Video Summarizer & Chat

An AI-powered YouTube video summarization and question-answering application built using Python, YouTube Transcript API, and Google Gemini AI. The application extracts video transcripts and uses Generative AI to generate summaries, key insights, detailed explanations, and answer questions based on the video content.

🚀 Features

- YouTube Transcript Extraction: Extract transcripts from YouTube videos using the YouTube Transcript API.
- AI-Powered Summarization: Generate concise summaries of video content using Google Gemini.
- Detailed Explanation: Get a detailed explanation of the video transcript.
- Key Points: Extract important information in bullet-point format.
- Important Insights: Identify significant insights from video content.
- Question & Answer: Ask questions based on the extracted video transcript.
- Multilingual Transcript Support: Supports transcript retrieval using specified language preferences where available.

🛠️ Technologies Used

- Programming Language: Python
- AI Model: Gemini 2.5 Flash-Lite
- Generative AI: Google Gemini API
- Transcript Extraction: YouTube Transcript API
- Environment: Google Colab

⚙️ How It Works

1. Enter a YouTube video ID.
2. Extract the video's transcript using the YouTube Transcript API.
3. Process the transcript and pass it to the Gemini AI model.
4. Generate a short summary, detailed explanation, key points, and important insights.
5. Ask questions about the video content and receive AI-generated answers based on the transcript.

🏗️ Workflow

YouTube Video ID → Transcript Extraction → Transcript Processing → Gemini AI → Summary & Insights → Question Answering

📋 AI Analysis Output

The application generates:

- Short Summary: A concise overview of the video.
- Detailed Explanation: An expanded explanation of the video content.
- Key Points: Important topics and takeaways.
- Important Insights: Significant information extracted from the transcript.
- Questions & Answers: Responses to user questions based on the video transcript.

📦 Installation & Setup

1. Install Dependencies

!pip install youtube-transcript-api google-genai

2. Configure Google Gemini API Key

Store your API key securely in Google Colab Secrets.

from google.colab import userdata

GOOGLE_API_KEY = userdata.get('GOOGLE_API_KEY')

3. Initialize Gemini

from google import genai

client = genai.Client(api_key=GOOGLE_API_KEY)

4. Extract the YouTube Transcript

Provide the YouTube video ID and retrieve the available transcript.

5. Generate Summary and Ask Questions

Use the extracted transcript as context for Gemini AI to generate the summary and answer questions.

🎯 Use Cases

- Summarizing educational videos
- Understanding programming tutorials
- Extracting important information from lectures
- Reviewing lengthy YouTube videos
- Asking questions about video content
- Supporting self-learning and research

🔮 Future Improvements

- Build a Streamlit web interface.
- Generate summaries in multiple languages.
- Add timestamp-based key points.
- Summarize longer videos using transcript chunking.
- Generate downloadable summary reports.
- Add a conversational chat interface.

👨‍💻 Author

Gowtham Sanapa

- GitHub: "gow504" (https://github.com/gow504)

---

⭐ If you find this project useful, feel free to explore and contribute.
