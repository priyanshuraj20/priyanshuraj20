```markdown
# 📟 `priyanshu@root:~$` voxa-ssh -t engineer

```bash
$ connecting to priyanshuraj20.db...
[========================================] 100%
$ status --check
🟢 System Online
🟢 Active Projects: 2 (Dentwise SaaS, Voxa AI Engine)
🟢 DSA Runtime Complexity: O(log N)
```

> **I am a Computer Science Engineer who builds products end-to-end. I don't write scripts to pass classes — I design systems that solve real-world latency, synchronization, and scaling challenges.**

---

## 🛠️ System Architecture & Stack Configuration

```yaml
system:
  runtime: [Java, TypeScript, Python, Node.js]
  frontend:
    framework: Next.js 15 (App Router, Server Actions)
    design_system: TailwindCSS, Glassmorphism, WebGL Shaders
  backend:
    engine: FastAPI (Python), Express (Node)
    protocols: WebSockets (Binary streaming), REST APIs
  storage:
    relational: PostgreSQL, MySQL
    orms: Prisma ORM, SQLAlchemy
  infrastructure:
    orchestration: Docker
    cloud_delivery: Vercel, Railway, Git-based CI/CD
```

---

## 🚀 Systems Under Construction

### 🌍 [Voxa AI — Real-Time Multilingual Speech Translator](https://github.com/priyanshuraj20/Voxa-ai)
> **Engineering Focus:** *Sub-second latency, binary streaming, and offline digital signal processing (DSP).*
* **The Challenge:** Translating audio in real-time without introducing lag or sending massive audio files to APIs.
* **The Architecture:** 
  - **Ingestion:** Browser AudioContext downsamples client microphones to `16kHz Mono`, converts `Float32` frames into `Int16` PCM, and streams binary buffers over persistent WebSockets.
  - **Local Speaker Separation:** Implemented a CPU-only pitch estimation diarizer. Uses Fast Fourier Transforms (FFT) to isolate vocal peak frequencies ($80\text{ Hz} - 300\text{ Hz}$) and attributes text to specific speakers dynamically.
  - **Correction Pipeline:** Sequence pipes raw Whisper transcripts into sequential Llama 3.1 agents for punctuation & grammar correction before executing the NLLB-200 translation model.

### 🦷 [Dentwise — AI-Powered Dental SaaS Platform](https://www.dentwise.live)
> **Engineering Focus:** *Multi-tenant SaaS pipelines, AI integration, and state synchronization.*
* **The Challenge:** Automating booking workflows and dentist scheduling with automated conversational voice assistants.
* **The Architecture:**
  - **Booking Engine:** Implemented a multi-step scheduler synchronized using Next.js Server Actions and PostgreSQL.
  - **AI Voice Agent:** Scaled real-world phone/voice assistant calls integrated with Vapi.
  - **Infrastructure:** Secured using Clerk OAuth/OTP layers, database schemas handled via Prisma, and billing pipelines integrated with Stripe.

---

## 📊 Performance Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=priyanshuraj20&show_icons=true&theme=tokyonight&count_private=true" alt="Priyanshu's Stats" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=priyanshuraj20&layout=compact&theme=tokyonight" alt="Priyanshu's Languages" width="47%" />
</p>

---

## 🔗 Port Mappings (Connect with me)

```bash
$ curl -X GET https://priyanshuraj.net/contact
```
* **LinkedIn:** [/in/your-linkedin-username]()
* **Email:** [your-email@domain.com](mailto:your-email@domain.com)
* **Location:** `Parul University, Gujarat, India`

---

```bash
$ exit
Connection to priyanshuraj20 closed.
```
```
