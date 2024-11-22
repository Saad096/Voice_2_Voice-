#### Real-Time Voice-to-Voice Chatbot
This project implements a real-time voice-to-voice chatbot using Gradio, Whisper, and the Groq API. The application accepts voice input from the user, transcribes it to text using Whisper, generates a conversational response using the Groq language model, and converts the response back to speech using Google Text-to-Speech (gTTS).
# Features
    1. Speech-to-Text Conversion
        ◦ Converts voice input to text using OpenAI's Whisper model.
    2. Conversational Response Generation
        ◦ Generates conversational responses using Groq's llama3-8b-8192 language model.
    3. Text-to-Speech Conversion
        ◦ Converts the generated response back to speech using gTTS.
    4. Interactive User Interface
        ◦ Built using Gradio for an intuitive, user-friendly interface.
    5. Real-Time Communication
        ◦ Facilitates smooth, end-to-end voice interactions.
# Prerequisites
    • Python 3.8+
    • Install the following libraries:
        ◦ gradio
        ◦ whisper
        ◦ gtts
        ◦ groq
    • Set up an API key for Groq.

# Installation
    1. Clone the repository or copy the script to your local system.
    2. cd to cloned repository
    3. Install the required Python libraries:
           pip install -r requirements.txt
    4. Ensure you have the ffmpeg package installed on your system for audio processing:
       sudo apt-get install ffmpeg  # For Debian/Ubuntu
       brew install ffmpeg         # For macOS
# Usage
    1. Replace api_key="key" in the script with your actual Groq API key.
    2. Run the script:
       python voice_to_voice_chatbot.py
    3. Access the chatbot interface from the local URL provided in the terminal or share the public link for others to use.
