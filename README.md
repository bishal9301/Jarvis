# Jarvis

JARVIS is a Python-based voice-activated virtual assistant designed to perform various tasks such as web browsing, music playback, news fetching, and AI-powered responses. The assistant listens for a wake word ("Jarvis") and executes commands based on voice input.

Key Features:

1.Speech Recognition & Text-to-Speech
 * Uses speech_recognition for voice input.
 * Outputs responses using gTTS (Google Text-to-Speech) and pyttsx3.
 
2.Web Browsing & Online Services
 * can open Google, Facebook, YouTube, and LinkedIn in a web browser.
 
3.Music Playback
 * Maintains a predefined music library (musicLibrary.py) with YouTube links.
 * Plays songs based on voice commands (e.g., "Play Skyfall").
 
4.News Fetching
 * Retrieves top news headlines using the News API and reads them aloud.
 
5.AI-Powered Responses
 * Integrates OpenAI GPT-3.5-turbo for answering user queries.
 * Responds concisely to general questions, similar to Alexa or Google Assistant.
 
6.Continuous Voice Listening
 * Listens for the wake word "Jarvis" and activates for further commands.


