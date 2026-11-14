<!-- HERO BANNER (REFINED DARK LUXURY SVG) -->
<div align="center">
  <img src="./assets/hero.svg" alt="Sujal Vijayvargiya // SDE @ Juspay" width="100%" />
</div>

<br/>

<!-- SYSTEM TELEMETRY CARDS (METRIC MODULES) -->
<div align="center">
  <img src="./assets/telemetry.svg" alt="Telemetry & Engineering Metrics" width="100%" />
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

## ⚡ System Architecture & Execution Pipelines

### 1. Multi-Region Fintech & Payment Orchestration Engine
> *High-concurrency distributed payment infrastructure engineered at Juspay Technologies, powering enterprise merchant transactions across Singapore, Hong Kong, and India.*

```mermaid
flowchart LR
    subgraph INGRESS ["Ingress & Validation"]
        REQ["Merchant Checkout Request"] --> IDEM["Idempotency Filter & Tokenizer"]
    end

    subgraph ORCHESTRATOR ["Payment Orchestrator"]
        IDEM --> STEP1["01 // Authorization"]
        STEP1 --> STEP2["02 // 3DS Authentication (FPS / WeChat / Alipay)"]
        STEP2 --> STEP3["03 // Capture & Settlement"]
    end

    subgraph MESH ["Multi-Region Mesh"]
        STEP1 -.-> SG["🇸🇬 Singapore Stack (Euler / Morpheus)"]
        STEP2 -.-> HK["🇭🇰 Hong Kong Stack (PaymentPage)"]
    end

    subgraph FABRIC ["Event & Audit Fabric"]
        STEP3 --> KAFKA["Apache Kafka Event Bus"]
        KAFKA --> RECON["Automated Ledger & Reconciliation (PostgreSQL)"]
    end

    classDef primary fill:#0b1329,stroke:#3b82f6,stroke-width:1.5px,color:#f8fafc;
    classDef accent fill:#0f172a,stroke:#6366f1,stroke-width:1.5px,color:#f8fafc;
    classDef success fill:#064e3b,stroke:#10b981,stroke-width:1.5px,color:#f8fafc;
    class REQ,IDEM primary;
    class STEP1,STEP2,STEP3 accent;
    class SG,HK,KAFKA,RECON success;
```

---

### 2. Neural Audio & Adaptive Evaluation Pipeline (`AlgoMentor`)
> *Real-time FAANG-style DSA mock interview platform orchestrating speech streaming, LLM question synthesis, and automated scoring.*

```mermaid
sequenceDiagram
    autonumber
    actor Candidate as 🧑‍💻 Candidate
    participant UI as 🖥️ Next.js Client
    participant API as ⚡ FastAPI Gateway
    participant STT as 🎙️ AssemblyAI / Whisper
    participant LLM as 🧠 Groq (Llama-3.3-70B)
    participant TTS as 🔊 AWS Polly Neural

    Candidate->>UI: Speaks DSA solution / code walk-through
    UI->>API: WebRTC / Audio Stream Chunking
    API->>STT: Low-latency Audio Transcription
    STT-->>API: Synthesized Transcript Stream
    API->>LLM: Contextual Prompt (Code, Complexity, Communication)
    LLM-->>API: Adaptive Feedback + Dynamic Follow-up Question
    API->>TTS: Neural Voice Synthesis Stream
    TTS-->>UI: Real-Time Audio Feedback Stream
    UI-->>Candidate: Realistic Conversational Voice Playback
```

---

## 📋 Production Audit & Impact Ledger

An audited log of production initiatives, scale breakthroughs, and open-source systems:

| Ledger ID | System / Domain | Operation & Focus | Status | Impact & Guarantees |
|:---:|---|---|:---:|---|
| `#JUS-SG01` | **Singapore Regional Stack** | Automated blueprint infrastructure codification | `🟢 PRODUCTION` | Slashed new market rollout from **6 weeks ➔ 15 days (-75%)** |
| `#JUS-WL02` | **Native Wallet SDKs** | Shipped WeChatPay, Alipay & FPS intent checkout | `🟢 PRODUCTION` | Seamless native Android/iOS wallet payments across SG & HK |
| `#JUS-OR03` | **3-Step Orchestration** | Decoupled Authorization, 3DS Authentication & Capture | `🟢 PRODUCTION` | Modular state machine lifecycle with 100% idempotency |
| `#DEV-AM04` | **AlgoMentor** | Real-time AI mock interview platform with neural voice | `🚀 LIVE SYSTEM` | Sub-second voice synthesis & adaptive evaluation (`Groq` + `AWS`) |
| `#DEV-MM05` | **Meeting Intelligence** | Automated audio transcription & action item extraction | `🚀 LIVE SYSTEM` | End-to-end meeting summaries using `Gemini API` & `FastAPI` |

---

## 🛠️ Engineering Loadout & System Capabilities

```
┌─────────────────────────┬──────────────────────────────────────────────────────────────────┐
│ DOMAIN                  │ TECHNOLOGIES & TOOLING RUNTIMES                                  │
├─────────────────────────┼──────────────────────────────────────────────────────────────────┤
│ ⚡ Payment & Core        │ Haskell (Pure FP) • Python 3.12 • TypeScript • C/C++ • SQL       │
│ 🛰️ Distributed Fabric   │ Apache Kafka • Redis (Distributed Caching & Limiters) • Postgres │
│ 🌐 Backend & Services   │ FastAPI (Async APIs) • Node.js • Microservices • Webhooks • REST │
│ 🧠 AI & Speech Systems  │ Groq (Llama-3.3-70B) • Gemini API • AWS Polly • AssemblyAI       │
│ 🖥️ Interface & Mobile   │ Next.js (App Router) • React 19 • Tailwind CSS • Flutter / Dart  │
│ 🛡️ DevOps & Infra       │ Docker • Kubernetes • Linux Server Administration • Git • Actions│
└─────────────────────────┴──────────────────────────────────────────────────────────────────┘
```

<div align="center">
  <a href="#">
    <img src="https://skillicons.dev/icons?i=py,ts,js,haskell,cpp,postgres,redis,kafka,docker,kubernetes,fastapi,nodejs,nextjs,react,tailwind,git,linux,postman,aws,gcp" alt="Tech Stack Icons" />
  </a>
</div>

---

## 📊 Telemetry, Activity & Contribution Stream

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
PING sujal (12.9716° N, 77.5946° E [Bangalore, IN]): 56 data bytes
64 bytes from juspay-hq: icmp_seq=0 ttl=64 time=0.042 ms

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
