<!-- HERO BANNER (REFINED DARK LUXURY SVG) -->
<div align="center">
  <img src="./assets/hero.svg" alt="Sujal Vijayvargiya // Software Development Engineer" width="100%" />
</div>

<br/>

<!-- SYSTEM TELEMETRY CARDS (PERSONAL PROJECTS HUD) -->
<div align="center">
  <img src="./assets/telemetry.svg" alt="Personal Projects & Engineering Telemetry" width="100%" />
</div>

<br/>

<!-- LIVE TERMINAL SESSION -->
<div align="center">
  <img src="./assets/terminal.svg" alt="Sujal Vijayvargiya Terminal Session" width="100%" />
</div>

<br/>

<!-- QUICK ACTION TRANSMISSIONS -->
<div align="center">
  <a href="https://linkedin.com/in/sujalvijayvargiya" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:sujalvj121@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-0f172a?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://dsa-interviewer-bot.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/AlgoMentor_Live-0f172a?style=for-the-badge&logo=vercel&logoColor=38bdf8" alt="AlgoMentor Live" />
  </a>
  &nbsp;
  <a href="https://github.com/vjsujal" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

<br/>

---

## 🧑‍💻 Bio

> **SDE @ [Juspay](https://juspay.in)** building high-scale payment infrastructure and distributed state machines.  
> After hours, I architect **voice-interactive AI platforms and intelligent developer tools** (built [AlgoMentor](https://dsa-interviewer-bot.vercel.app)).  
> *Turning caffeine into idempotent distributed systems & clean abstractions.* ☕⚡

---

## 🚀 Featured Personal Projects

### `01` [AlgoMentor](https://dsa-interviewer-bot.vercel.app) — AI Mock Interview Platform
> Real-time voice-interactive platform simulating FAANG-style algorithmic interviews with adaptive questioning and automated evaluation.

* **Adaptive AI Reasoning:** Leverages Groq Llama-3.3-70B for low-latency contextual evaluation, assessing code structure, time/space complexity, and communication clarity.
* **Neural Voice Synthesis:** Integrated AWS Polly for low-latency, natural interviewer voice playback with conversational speech pacing.
* **Stack:** `Next.js` `FastAPI` `Python` `Groq (Llama-3.3-70B)` `AWS Polly` `PostgreSQL` `JWT Auth`
* **Links:** [Live Platform ↗](https://dsa-interviewer-bot.vercel.app) &nbsp;|&nbsp; [GitHub Repository ↗](https://github.com/vjsujal)

---

### `02` AI Minutes of Meeting (MoM) Generator
> End-to-end meeting intelligence pipeline transcribing audio and synthesizing structured, actionable minutes.

* **Audio Intelligence:** Automated speech-to-text pipeline using AssemblyAI to handle multi-speaker meeting recordings.
* **Structured Synthesis:** Uses Google's Gemini API with structured outputs to extract core decisions, key takeaways, and assignable action items.
* **Stack:** `FastAPI` `React.js` `Gemini API` `AssemblyAI` `Python` `JWT Auth`
* **Links:** [GitHub Repository ↗](https://github.com/vjsujal)

---

### `03` LongToShorts — Automated Video Intelligence
> AI-powered pipeline extracting concise, high-engagement short-form videos from long-form content.

* **NLP Hook Extraction:** Analyzes audio transcripts with spaCy and Google Generative AI to identify high-retention moments and viral narrative hooks.
* **Automated Video Processing:** Programmatically cuts, frames, and renders vertical video clips ready for YouTube Shorts and Reels using MoviePy.
* **Stack:** `Python` `Google GenAI` `MoviePy` `spaCy` `AssemblyAI`
* **Links:** [GitHub Repository ↗](https://github.com/vjsujal)

---

## ⚡ Architecture: AlgoMentor Voice & Evaluation Pipeline

```mermaid
sequenceDiagram
    autonumber
    actor Candidate as 🧑‍💻 Candidate
    participant UI as 🖥️ Next.js Client
    participant API as ⚡ FastAPI Gateway
    participant STT as 🎙️ Speech Ingestion (AssemblyAI)
    participant LLM as 🧠 Groq (Llama-3.3-70B Core)
    participant TTS as 🔊 AWS Polly Neural Voice

    Candidate->>UI: Speaks code explanation / complexity walk-through
    UI->>API: Audio Chunk Stream
    API->>STT: Low-Latency Speech-to-Text
    STT-->>API: Transcribed Candidate Response
    API->>LLM: Evaluate Code + Formulate Follow-Up Question
    LLM-->>API: Contextual Feedback & Next Question
    API->>TTS: Stream Text to Neural Speech Synthesis
    TTS-->>UI: Real-Time Audio Feedback Stream
    UI-->>Candidate: Realistic Conversational Voice Playback
```

---

## 🛠️ Engineering Loadout & System Capabilities

```
┌─────────────────────────┬──────────────────────────────────────────────────────────────────┐
│ DOMAIN                  │ TECHNOLOGIES & TOOLING RUNTIMES                                  │
├─────────────────────────┼──────────────────────────────────────────────────────────────────┤
│ ⚡ Core Languages        │ Python 3.12 • TypeScript • JavaScript • Haskell • C/C++ • SQL    │
│ 🛰️ Distributed Systems  │ Apache Kafka • Redis (Caching & Rate Limiting) • PostgreSQL ACID │
│ 🌐 Backend Services     │ FastAPI (Async APIs) • Node.js • Express • Microservices • REST  │
│ 🧠 AI & Speech Systems  │ Groq (Llama-3.3-70B) • Gemini API • AWS Polly • AssemblyAI       │
│ 🖥️ Frontend & UI        │ Next.js (App Router) • React 19 • Tailwind CSS • Flutter / Dart  │
│ 🛡️ DevOps & Cloud       │ Docker • Kubernetes • Linux Administration • Git • GitHub Actions│
└─────────────────────────┴──────────────────────────────────────────────────────────────────┘
```

<div align="center">
  <a href="#">
    <img src="https://skillicons.dev/icons?i=py,ts,js,haskell,cpp,postgres,redis,kafka,docker,kubernetes,fastapi,nodejs,nextjs,react,tailwind,git,linux,postman,aws,gcp" alt="Tech Stack Icons" />
  </a>
</div>

---

## 📊 Activity & Contribution Stream

<div align="center">
  <table border="0" cellspacing="0" cellpadding="0">
    <tr align="center">
      <td>
        <img width="420" src="https://github-stats-extended.vercel.app/api?username=vjsujal&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000" alt="Sujal's GitHub Stats" />
      </td>
      <td>
        <img width="420" src="https://github-stats-extended.vercel.app/api/top-langs?username=vjsujal&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000" alt="Top Languages" />
      </td>
    </tr>
    <tr align="center">
      <td colspan="2">
        <br/>
        <img width="850" src="https://streak-stats.demolab.com/?user=vjsujal&theme=github-dark&hide_border=true&background=00000000" alt="GitHub Streak" />
      </td>
    </tr>
  </table>
</div>

---

## 📡 Dispatch & Communication Protocols

```bash
$ ping -c 1 sujalvijayvargiya
PING sujal (Bangalore, IN): 56 data bytes
64 bytes from local-station: icmp_seq=0 ttl=64 time=0.042 ms

--- Communication Channels Available ---
├── LinkedIn:  https://linkedin.com/in/sujalvijayvargiya
├── Email:     sujalvj121@gmail.com
├── Live App:  https://dsa-interviewer-bot.vercel.app
└── GitHub:    https://github.com/vjsujal
```

<div align="center">
  <sub>⚡ Engineered with precision &amp; architectural resilience by <b>Sujal Vijayvargiya</b></sub><br/>
  <sub><i>"Simplicity is prerequisite for reliability." — Edsger W. Dijkstra</i></sub>
</div>
