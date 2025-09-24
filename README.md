# Save README.md content locally

readme_content = """# 🛡️ AI Room Guard

An AI-powered room security agent that uses **vision, speech, and language models** to watch over your room when you’re away.  
It recognizes trusted individuals, warns intruders with escalating dialogue, and can be activated via voice command.  

## 🚀 Features
- Voice activation with keyword command (e.g., “Guard my room”).
- Face recognition for trusted users (you, roommates, friends).
- Escalating spoken dialogue with unknown visitors:
  - Level 1 → “Who are you?”
  - Level 2 → “Please leave.”
  - Level 3 → Alarm / stern warning.
- Works with pre-trained AI models (no heavy training required).
- Optional stretch goals: keyword spotter, personalized fine-tuning.

## 🛠️ Tech Stack
- **Programming Language:** Python 3.8+
- **Vision:** OpenCV, MediaPipe, face_recognition, DeepFace
- **Speech Recognition (ASR):** Whisper, SpeechRecognition, Vosk
- **Text-to-Speech (TTS):** gTTS, pyttsx3, Coqui TTS
- **Conversational Agent:** LLMs via Hugging Face (Llama-3, Mistral), OpenAI GPT-4o mini, Google Gemini
- **Utilities:** Pygame / playsound for audio, Streamlit/Gradio for optional UI

## 📂 Project Structure
--
## Authors
