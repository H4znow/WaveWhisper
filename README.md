# 🎧 WaveWhisper

**Audio Agent Lab** is an experimental AI project exploring the intersection of sound classification, audio transformation, and agent-based interaction. The project combines deep learning models for audio understanding with large language model (LLM)-driven agents capable of multitasking and interacting with sound data in flexible, user-friendly ways.

---

## 🧠 Project Goals

This project aims to:
- Train a deep learning model for **audio classification**, inspired by [this article](https://medium.com/data-science/audio-deep-learning-made-simple-sound-classification-step-by-step-cebc936bbe5).
- Develop a suite of intelligent **AI agents**, powered by LLMs, to interact with audio in natural language and perform various tasks.

---

## 🛠️ Planned Features

### 🔊 Core Audio Classification
- Train a neural network to classify different types of sounds (e.g., speech, noise, animal sounds, music, etc.)
- Build a robust pipeline for feature extraction and training

### 🤖 LLM-Powered Agents for Multitasking
LLM agents will be capable of interpreting user prompts and performing audio-related tasks, such as:
- **Audio length modification** (e.g., trim, extend with silence or repetition)
- **Voice modification** (e.g., pitch shift, style transfer – experimental)
- **Audio classification** (query-based classification via agent)
- **Text-to-speech** synthesis from input text
- **Speech-to-text** transcription from audio files

---

## 🚧 Development Status

- [ ] Audio classification model implementation
- [ ] Basic agent interface
- [ ] Audio transformation utilities
- [ ] TTS / STT integration
- [ ] LLM prompt interface for multitask control

---

## 🧰 Tech Stack (tentative)

- Python, PyTorch / TensorFlow
- Librosa, torchaudio
- Hugging Face Transformers or OpenAI GPT for agent logic
- TTS/STT APIs (e.g., Google, Whisper, Coqui)

---

## 🗂️ Directory Structure (planned)

```
audio-agent-lab/
├── classifiers/
├── agents/
├── audio_utils/
├── data/
├── notebooks/
└── README.md
```

---

## 📌 Why This Project?

To explore how intelligent agents can bridge the gap between deep learning models and end-user interaction, especially in the creative domain of audio and sound.
