# 📝 Meeting Summarizer

**Meeting Summarizer** is a Python-based application designed to transcribe and summarize audio from meetings or conferences. By leveraging the power of OpenAI's GPT-3.5 model, it provides concise and coherent summaries, making it easier to review key points without going through lengthy recordings.

## 🚀 Features

- **Audio Transcription**: Convert meeting audio files into text.
- **Summarization**: Generate concise summaries of the transcribed text.
- **GPT-3.5 Integration**: Utilize OpenAI's GPT-3.5 model for accurate and coherent summaries.
- **User-Friendly Interface**: Simple command-line interface for easy interaction.

## 📂 Project Structure

Meeting-Summarizer/
│
├── audio_files/ # Directory to store audio files
├── transcriptions/ # Directory to save transcribed text files
├── summaries/ # Directory to save generated summaries
├── main.py # Main script to run the application
├── requirements.txt # List of dependencies
└── README.md # Project documentation

## ⚙️ How It Works

1. **Upload Audio File**  
   Place your meeting or conference audio file (MP3, WAV, etc.) in the `audio_files/` directory.

2. **Transcription**  
   The application uses Python's `speech_recognition` library to convert the audio into text. Each spoken word is transcribed into a readable format.

3. **Summarization**  
   The transcribed text is sent to the OpenAI GPT-3.5 API. The model processes the content and generates a concise, coherent summary highlighting the key points of the meeting.

4. **Save Output**  
   - The full transcription is saved in the `transcriptions/` directory.  
   - The summary is saved in the `summaries/` directory for easy access and sharing.

5. **Review & Download**  
   You can review the transcription and summary, then use them for meeting notes, documentation, or sharing with your team.


## 🛠 Technology Stack

- **Programming Language**: Python
- **Speech Recognition**: `speech_recognition` library for audio transcription.
- **OpenAI API**: For generating summaries using GPT-3.5.
- **Audio Processing**: `pydub` for audio file handling.
