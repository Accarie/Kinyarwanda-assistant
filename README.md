# Kinyarwanda-assistant
Kinyarwanda Voice Assistant is a bilingual voice interaction tool that enables speech recognition and text-to-speech synthesis in Kinyarwanda and English. It uses OpenAI Whisper for automatic speech transcription, Coqui TTS for speech generation, and features an intuitive Gradio web interface for voice-based Q&amp;A and custom speech synthesis.

# 🗣️ Kinyarwanda Voice Assistant

This project is a bilingual voice assistant that leverages [Whisper](https://github.com/openai/whisper) for speech recognition and [TTS](https://github.com/coqui-ai/TTS) for converting text into speech. It features a user-friendly [Gradio](https://www.gradio.app/) interface with two main functions: voice-based question answering and custom text-to-speech generation.

---

## 🔧 Core Features

- 🎙️ **Speech Recognition** via OpenAI Whisper.  
- 💬 **Preset Kinyarwanda Q&A** matching based on transcribed input.  
- 🔊 **Text-to-Speech Output** using Hugging Face-supported TTS models.  
- 🖥️ **Web-based Interface** created with Gradio.  
- 🔁 **Voice Cloning Support** using uploaded reference audio.  
- 🌐 **Deployable Interface** with optional public sharing.

---

## 🛠️ Setup Instructions

### ⚙️ Install Python Libraries

First, install the necessary Python packages:

```bash
pip install -q openai-whisper
pip install numpy==1.24.3 --force-reinstall
pip install gradio
pip install transformers
pip install torchaudio
pip install TTS
pip install nemo-toolkit
