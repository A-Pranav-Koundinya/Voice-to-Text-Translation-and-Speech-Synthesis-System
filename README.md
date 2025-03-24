# Voice-to-Text-Translation-and-Speech-Synthesis-System

### Project Overview

This project is a **Voice-to-Text Translation and Speech Synthesis System** designed to enable real-time language translation and spoken feedback. It converts spoken input into text, detects the language, translates the text to a target language, and then generates speech for translated text. This system provides a seamless experience for users, supporting multiple languages, particularly focusing on Indian languages.

### Key Features

- **Speech Recognition:** The system listens to spoken input through a microphone and converts the voice into text using Google’s Speech Recognition API.
  
- **Language Detection:** After recognizing the text, the system automatically detects the language of the spoken input using the `googletrans` library.
  
- **Text Translation:** Once the language is detected, the recognized text is translated into the language of choice (such as Hindi, Tamil, Telugu, etc.) using the Google Translate API.
  
- **Speech Synthesis:** The system generates speech from the translated text using Google’s Text-to-Speech (`gTTS`) library, making the output accessible audibly.

- **Multi-language Support:** The system is built to support a variety of Indian languages, including **Hindi**, **Telugu**, **Tamil**, **Kannada**, **Malayalam**, and **Bengali**, making it useful for a diverse range of users.

### Technologies Used

- **Python:** The core programming language used to develop this system.
- **Speech Recognition (speech_recognition library):** For converting voice input into text.
- **Google Translate API (googletrans library):** For detecting and translating text.
- **Google Text-to-Speech (gTTS library):** For converting translated text back into speech.
- **OS Module:** To handle file operations and audio playback across different platforms (Windows, macOS, Linux).

### Conclusion

This project provides a simple yet powerful solution for real-time language translation and voice feedback. It leverages popular APIs and libraries to bridge communication gaps, making it especially useful for multilingual users.



