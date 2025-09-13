# 🤖 Conversational AI Cold-Calling Agent

This project is a **Voice AI Agent** that automates cold calling for businesses. It uses **speech-to-text**, **LLM-based conversation flow**, and **text-to-speech** to interact naturally with users over phone calls.

---

## 📌 Features
- **Automated Call Handling** – Handles calls via telephony APIs.
- **Real-Time Speech Recognition** – Converts speech to text.
- **Conversational Intelligence** – Generates human-like responses using LLMs.
- **Voice Output** – Converts text back to speech for natural interaction.
- **Lead Qualification** – Stores user responses for further analysis.
- **Logging & Monitoring** – Keeps call transcripts for review.

---

## 🏗️ Tech Stack
| Component             | Technology |
|----------------------|------------|
| **Backend**          | Python (Flask / FastAPI) |
| **Speech-to-Text**   | OpenAI Whisper / Google Speech API |
| **LLM for Dialogue** | OpenAI GPT / LangChain |
| **Text-to-Speech**   | gTTS / ElevenLabs |
| **Telephony**        | Twilio API |
| **Database**         | SQLite / PostgreSQL |

---

## ⚙️ Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/conversational-ai-cold-caller.git
cd conversational-ai-cold-caller
