
## 1. Project Overview
Shiksha Saathi is an AI-powered micro-learning assistant designed for rural and government schools. It delivers voice-based lessons in local languages, adapts to student responses, and helps teachers manage multi-grade classrooms. The system works offline for daily classroom use and uses the internet when available for updates, synchronization, and AI improvements.

---

## 2. Objectives
- Provide personalized learning in low-resource environments
- Reduce teacher workload in multi-grade classrooms
- Enable voice-based interaction in local languages
- Support offline-first learning with optional internet sync
- Provide performance tracking and teacher analytics

---

## 3. Functional Requirements

### FR1 – Voice-Based Interaction
System shall allow students to interact using voice input.
System shall respond in local language voice output.

### FR2 – Speech Recognition
System shall convert student speech to text using offline STT.
System shall support low-bandwidth environments.

### FR3 – Adaptive Learning
System shall adjust lesson difficulty based on student responses.
System shall provide concept reinforcement if student answers incorrectly.

### FR4 – Micro Lesson Generation
System shall generate 5–10 minute micro lessons.
System shall generate worksheets and revision content.

### FR5 – Performance Tracking
System shall store student performance locally.
System shall sync performance data to cloud when internet is available.

### FR6 – Teacher Dashboard
System shall provide student progress visualization.
System shall allow teacher control and monitoring.

### FR7 – Internet Sync
System shall download content updates.
System shall update AI models.
System shall upload anonymized learning data.

---

## 4. Non-Functional Requirements

### Performance
- System must work on low-cost hardware
- Response time < 3 seconds

### Reliability
- Must work fully offline
- Must not lose local data

### Security
- Student data must be encrypted
- Cloud sync must be secure

### Usability
- Must support local language UI
- Must support voice-first interaction

---

## 5. Hardware Requirements
- Raspberry Pi / Low-cost Android Tablet
- Microphone
- Speaker
- Display

---

## 6. Software Requirements
- Frontend: React.js / HTML / CSS / JS
- Backend: Node.js / Express / Python AI
- Database: SQLite (Local), Cloud DB (Optional)
- STT: Vosk Offline
- TTS: eSpeak Offline + Cloud TTS

---

## 7. Stakeholders
- Students
- Teachers
- Schools
- Education Authorities
