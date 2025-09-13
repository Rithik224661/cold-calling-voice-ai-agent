<div align="center">

# 🎙️ Cold Calling Voice AI Agent – Anthica

![Hero](https://user-images.githubusercontent.com/6234599/228337850-e32bb01d-3701-47ef-a433-3221c9e0e56e.png)

**An AI-powered outbound calling agent for automated lead generation and sales.**  
Built using [Vocode](https://github.com/vocodedev/vocode-python) as the core engine with GPT-based dynamic conversation, real-time transcription, and natural text-to-speech.

[![GitHub Repo stars](https://img.shields.io/github/stars/vocodedev/vocode-core?style=social)](https://github.com/vocodedev/vocode-core)
[![pypi](https://img.shields.io/pypi/v/vocode.svg)](https://pypi.python.org/pypi/vocode)

</div>

---

## 🚀 Overview

Anthica is a **Conversational AI agent** that can make **cold calls** to potential leads, deliver a product pitch, and collect responses automatically.  
This project demonstrates how to integrate **LLMs, speech recognition, telephony, and TTS** into a single system.

---

## ⭐ Features

- 📞 **Outbound Cold Calls:** Automatically dial prospects using Twilio.
- 🗣 **Speech-to-Text:** Converts customer responses to text using Whisper / Deepgram.
- 🤖 **Dynamic Conversation:** GPT-powered responses tailored to the sales pitch.
- 🔊 **Text-to-Speech:** Natural, human-like speech with ElevenLabs / Azure TTS.
- 📝 **Lead Capture:** Stores user responses and call summary in a database.
- 🧠 **Context-Aware:** Maintains conversation state and adapts to user replies.

---

## 🏗 Tech Stack

| Component              | Tool/Library |
|----------------------|-------------|
| **Backend** | FastAPI / Python |
| **Telephony** | Twilio Programmable Voice |
| **Speech-to-Text (STT)** | OpenAI Whisper / Deepgram |
| **Conversation Engine** | OpenAI GPT-4 / Hugging Face Transformers |
| **NLP** | spaCy (entity extraction, intent recognition) |
| **Text-to-Speech (TTS)** | ElevenLabs / Azure TTS |
| **Database** | PostgreSQL / Supabase |
| **Deployment** | Render / Railway / Docker |

---

## 🧩 Architecture

```mermaid
graph TD
    A[Outbound Call via Twilio] --> B[Speech-to-Text (Whisper/Deepgram)]
    B --> C[Conversation Engine (GPT-4 / Transformer)]
    C --> D[Text-to-Speech (Azure/ElevenLabs)]
    D --> E[Play Voice Response to User]
    C --> F[Log Conversation + Lead Data to DB]
