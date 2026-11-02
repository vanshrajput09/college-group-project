# 🎓 Academic Transcription Practice Platform

> A specialised web application built to improve students' listening and communication skills. It provides a controlled environment, called **"The Playground"**, where students transcribe audio files at different difficulty levels. The platform also reports each student's accuracy, speed, and overall compliance.

---

## 📌 1. WHAT

### Key Features

**🔒 1. The Secure Playground (Anti-Cheat Engine)**
* **Disabled copy-paste:** Clipboard actions and right-click menus are disabled inside the workspace.
* **Focus monitoring:** If a student switches tabs or minimises the window, the system flags the activity or pauses the timer.
* **Keystroke validation:** Text input is standardised to prevent automated macro injection or virtual keyboard tampering.

**📊 2. Dynamic Difficulty Tiering**

| Tier | Audio Characteristics | Purpose | 
| :--- | :--- | :--- | 
| **Easy** | Slow pace, clear pronunciation, single speaker, minimal background noise | Beginners building baseline confidence | 
| **Medium** | Standard conversational speed, mild regional accents, occasional overlapping dialogue, basic academic or industry vocabulary | Students progressing in skill | 
| **Difficult** | Fast dictation, multiple speakers, faint background noise, heavy technical, medical or legal terminology | Simulates high-pressure exam environments | 

**📈 3. Performance Analytics and Accuracy Engine**
* **Timing metrics:** Words Per Minute (WPM), total time elapsed and speed pacing.
* **Accuracy metrics:** Word Error Rate (WER), highlighting insertions, omissions and substitutions against a master reference transcript.

**🤖 4. Integrated AI Learning Bot**
* **Contextual explanations:** Explains complex or unfamiliar vocabulary from the audio.
* **Grammar and punctuation support:** Tips on formatting, syntax rules and transcription guidelines.
* **Motivational coaching:** Personalised tips based on the student's difficulty level and recent error trends.

---

## 💡 2. WHY

Listening and communication skills need regular, honest, and measurable practice. This platform is built to bridge that gap by giving students a controlled space to practise, and by giving immediate and useful feedback on their results.

### Purpose of Each Part

| Feature | Why it is needed | 
| :--- | :--- | 
| **Anti-Cheat Engine** | To maintain academic integrity and ensure genuine skill assessment. | 
| **Difficulty Tiering** | To match audio to the student's progress, from beginner to exam level. | 
| **Analytics & Accuracy** | To give immediate, actionable metrics on speed and accuracy. | 
| **Student Dashboard** | To show long-term trends and the areas where the student consistently loses points. | 
| **AI Learning Bot** | To guide students like an on-demand tutor without compromising the test environment. | 

### Target Use Cases

* 🎯 **Skill development:** Continuous daily practice for students in secretarial, journalism, stenography or language courses.
* 📝 **College examinations:** A secure environment for professors to conduct controlled transcription practical exams.
* 💼 **Placement readiness:** Preparing students for real-world employment tests where speed and absolute accuracy are mandatory.

---

## ⚙️ 3. HOW

The platform will be built with the following suggested technology stack:

| Layer | Technology | Role in the project | 
| :--- | :--- | :--- | 
| **Frontend** | `React.js` / `Next.js` or `Vue.js` | Responsive, component-driven user interface | 
| **Backend** | `Node.js` (`Express`) | Application logic and secure routing to the AI service | 
| **Database** | `MongoDB` or `PostgreSQL` | Securely stores user performance records and audio metadata | 
| **AI Integration**| `OpenAI API` or `Anthropic API`| Powers the learning assistant bot, accessed through secure backend routing | 

---
*Note: This is a college team project.*