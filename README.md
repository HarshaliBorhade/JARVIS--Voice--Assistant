# **Jarvis - Voice Assistant**

**Jarvis** is a personal voice assistant application that listens for commands, processes them, and performs actions like opening websites, playing music, reading the latest news, and interacting with OpenAI's GPT model for various tasks. It leverages speech recognition, text-to-speech synthesis, and web browsing to deliver a convenient user experience.

## **Technologies Used**

- **Speech Recognition**: For recognizing commands via microphone input.
- **Text-to-Speech**: Using `pyttsx3` and **gTTS** to convert text to speech and speak the responses.
- **OpenAI API**: Utilizes GPT-3.5 to process and respond to user commands intelligently.
- **Web Browser Automation**: Opens websites such as Google, YouTube, Facebook, and LinkedIn.
- **Music Library**: Allows users to play songs using predefined links.
- **News API**: Fetches top headlines and news articles and reads them aloud.

## **Features**

- **Voice Command Recognition**: Jarvis listens for the wake word "Jarvis" and responds to user commands.
- **Web Browsing**: Open websites like Google, Facebook, YouTube, LinkedIn by voice command.
- **Music Playback**: Play songs from the music library based on the user’s command.
- **News Updates**: Fetches and reads the latest news headlines.
- **OpenAI Integration**: Uses GPT-3.5 for handling more complex queries.

## **Installation**

### 1. Install Dependencies

Make sure to install the required libraries:

```bash
pip install SpeechRecognition
pip install pyttsx3
pip install gTTS
pip install pygame
pip install requests
pip install openai
pip install musicLibrary
