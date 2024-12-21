# Voice-to-Text-Translation-and-Speech-Synthesis-System
Project Overview
This project is a Voice-to-Text Translation and Speech Synthesis System designed to enable real-time language translation and spoken feedback. It converts spoken input into text, detects the language, translates the text to a target language, and then generates speech for the translated text. This system provides a seamless experience for users, supporting multiple languages, particularly focusing on Indian languages.

Key Features
Speech Recognition: The system listens to spoken input through a microphone and converts the voice into text using Google’s Speech Recognition API.

Language Detection: After recognizing the text, the system automatically detects the language of the spoken input using the googletrans library.

Text Translation: Once the language is detected, the recognized text is translated into the language of choice (such as Hindi, Tamil, Telugu, etc.) using the Google Translate API.

Speech Synthesis: The system generates speech from the translated text using Google’s Text-to-Speech (gTTS) library, making the output accessible audibly.

Multi-language Support: The system is built to support a variety of Indian languages, including Hindi, Telugu, Tamil, Kannada, Malayalam, and Bengali, making it useful for a diverse range of users.

How It Works
Voice Input: The user speaks into the microphone, and the system captures this audio.
Speech-to-Text Conversion: The audio is converted to text using Google’s Speech Recognition API.
Language Detection & Translation: The detected text is analyzed, and the system translates it into the specified target language.
Speech Output: The translated text is then converted back to speech and played for the user using the gTTS library.
Technologies Used
Python: The core programming language used to develop this system.
Speech Recognition (speech_recognition library): For converting voice input into text.
Google Translate API (googletrans library): For detecting and translating text.
Google Text-to-Speech (gTTS library): For converting translated text back into speech.
OS Module: To handle file operations and audio playback across different platforms (Windows, macOS, Linux).
