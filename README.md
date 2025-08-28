# Video Vocab Urdu Translator

This project takes a video containing English vocabulary words, extracts the audio, converts speech to text, translates the text into **Urdu**, and optionally adds Urdu titles/subtitles back to the video.

---

## Features
- 🎤 **Speech-to-Text**: Extracts spoken English words from the video using [OpenAI Whisper](https://github.com/openai/whisper) or other STT APIs.
- 🌐 **Translation**: Translates English text into **Urdu** using [Google Translate API](https://cloud.google.com/translate) or similar services.
- 🎥 **Video Processing**: Adds translated Urdu text as titles/subtitles to the video using [MoviePy](https://github.com/Zulko/moviepy) or FFmpeg.
- ⚡ **End-to-End Automation**: Just provide a video, get the translated video with Urdu titles.

---

## Tech Stack
- **Python 3.9+**
- **Whisper** or **Google Speech-to-Text** for transcription
- **Google Translate API** or OpenAI for translation
- **MoviePy** or **FFmpeg** for video editing

---

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/video-vocab-urdu-translator.git
   cd video-vocab-urdu-translator
