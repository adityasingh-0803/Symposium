# Symposium: Talking to Virtual Minds

## 🧠 Project Overview

**Symposium: Talking to Virtual Minds** is an AI-powered, emotion-aware conversational experience featuring embodied avatars of visionary leaders across domains like space, design, and medicine. Users engage in **one-on-one conversations**, where each AI persona responds dynamically to the user's selected emotion — complete with expressive speech, lip-sync animation, and intelligent background transitions.

Built using a fusion of **Conversational AI**, **Text-to-Speech**, **Generative Visuals**, and **Unity avatars**, Symposium reimagines how we interact with intelligent systems through immersive storytelling.

---

## 🎥 Project Demo

🔗 **[Watch the Setup Video (60–90s)](https://drive.google.com/file/d/1253jno2u23covNzBAOvY9_V8qYdhKO1m/view?usp=sharing)**  
Watch the immersive experience here:  
**[▶️ Project Demo](https://drive.google.com/drive/folders/15-KTWxOjcAL3m29lORFIZZwGHejZDLgs?usp=sharing)**

🕹️ A complete walkthrough of the immersive experience, from emotion selection to avatar response and real-time background changes.

---

## 🎯 Key Features

- 🎭 Emotion-Driven Dialogue with GPT
- 👤 Embodied AI Leaders (Cooper, Elena Sparks, Dr. Aanya Verma)
- 🎧 Realistic Voice via ElevenLabs
- 🌌 Dynamic AI Backgrounds triggered by topic
- 🧠 Full Conversational Pipeline from emotion → avatar response

---

## 🧩 Technology Stack

| Component             | Tools / Models Used                          |
|-----------------------|----------------------------------------------|
| Natural Language Gen  | Convai (uses gemini)                         |
| Text-to-Speech (TTS)  | Convai built-in TTS                          |
| Avatar Creation       | Convai Character Creator                     |
| Lip Sync              | Convai built-in Lip Sync                     |
| Background Switching  | Unity Timeline + Trigger-Based Themes        |
| Audio Mixing          | Unity Audio Mixer                            |
| Game Engine	          | Unity 3D (likely URP pipeline)               |
| Deployment	          | Android                                      |
| Voice Input (ASR)	    | Convai built-in Automatic Speech Recognition |        |
| UI/UX Interface      	| Unity UI / TextMeshPro                       |

---

## 👤 AI Leaders

| Name               | Company            | Field         | Tagline                             |
|--------------------|--------------------|---------------|--------------------------------------|
| **Cooper**         | AstroCore          | Space AI      | "Guiding humanity beyond stars."     |
| **Elena Sparks**   | DesigNext AI       | Creative AI   | "Design for everyone, intelligently."|
| **Dr. Aanya Verma**| NeuroPulse AI      | Medical AI    | "Healing at the speed of thought."   |

---

## ⚙️ How It Works

1. **User selects an emotion**
   - Options like `hopeful`, `sad`, `curious`, etc.
   - Sets the tone for the conversation.

2. **Emotion-Matched Speech Generation**
   - The selected emotion is sent to a prompt-engineered GPT (via Convai or OpenAI).
   - GPT generates a **contextual reply** tailored to:
     - The selected AI persona (e.g., Elon Musk).
     - The user's emotion and query.

3. **Voice Synthesis via ElevenLabs**
   - The GPT output is sent to **ElevenLabs** with tone control parameters.
   - ElevenLabs returns a **high-fidelity voice response** that reflects the chosen emotion.

4. **Avatar Playback in Unity**
   - Unity avatar plays the voice with:
     - **Lip sync** animations driven by audio.
     - Matching facial expressions and body gestures.
   - Subtitles displayed using **TextMeshPro**.

5. **Dynamic Background Changes**
   - GPT extracts contextual **themes** (e.g., Mars, Tesla, Twitter).
   - Unity switches **background environments** using:
     - Triggered animations
     - Timeline sequences
     - Shader changes or post-processing volumes.

---

## 🚀 Future Work

- Real-time input via Whisper + GPT + TTS pipeline
- Emotion detection via facial expression / voice tone
- Multi-agent group conversation mode
- Memory-based persistent avatars
- Explainable AI dialogue (ethical alignment questions)

---

## 📝 Submission Info

- **Challenge:** AI Video Generation Challenge – Visionary Leaders Edition  
- **Project Title:** *Symposium: Talking to Virtual Minds*  
- **Duration:** 60–90 seconds  
- **Category:** AI + Conversational Interfaces + Embodied Agents  

---

## 📬 Contact
Team name: SimLink


