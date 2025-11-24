# Day 3 – Health & Wellness Voice Companion

This repository contains my **Day 3 submission for the Murf AI Voice Agent Challenge**. The task was to build a wellness-focused voice agent that functions as a brief, supportive daily check-in companion.

---

## 🌿 Project Overview

The agent carries out a short conversation each day and:

- Checks in on mood and energy  
- Helps define 1–3 achievable daily goals  
- Provides small, grounded, non-medical suggestions  
- Stores each session in a JSON log  
- Uses past entries to add context to future interactions

This allows conversations to feel more personalized and reflective over time.

---

## 🧠 Core Behaviour

### ✔ Daily Check-In Structure

**1. Mood & Energy Check**  
Example prompts:
- “How are you feeling today?”
- “What’s your energy like?”
- “Anything stressing you out right now?”

No medical advice or diagnosis — this is a supportive companion, not a clinician.

**2. Goal Setting**
Example prompts:
- “What are 1–3 things you want to accomplish today?”
- “Anything you want to do for yourself today?”

**3. Actionable, Realistic Suggestions**
Advice stays simple and grounded, ranging from:
- Breaking tasks into smaller steps  
- Planning short breaks  
- Suggesting simple self-care (like a 5-minute walk)

**4. Session Recap**
Each check-in ends with a brief summary:
- Mood overview  
- Main objectives  
- Confirmation from the user

---

## 💾 JSON-Based Data Persistence

Each session is written to a single JSON file and includes:

- Date/time  
- Self-reported mood  
- Stated objectives  
- *(Optional)* short summary

On future conversations, the agent reads the log and can reference past sessions, such as:

> “Last time we talked, you mentioned low energy. How is today in comparison?”

---

## ⚙ Tech Stack

- **LiveKit Agents + Python** → Conversation & agent logic  
- **Murf Falcon TTS** → Fast and natural speech output

---

## 📂 Repository Status

- **Frontend and backend implementation will be uploaded soon.**  
- For now, a **demo video is included**, showing:
  - The agent in conversation  
  - JSON logging updating live

---

## 🚀 Next Steps

- Add full backend and frontend files  
- Expand historical insights  
- (Optional) Integrate MCP tools for:
  - Task management  
  - Notes and reminders  
  - External tracking

---

Stay tuned for updates!
