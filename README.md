<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Athelesh%20B&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Software%20Engineer%20%7C%20AWS%20APJC%20Regional%20Champion&descSize=18&descAlignY=58" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=4FC3F7&center=true&vCenter=true&width=650&lines=I+build+software+that+ships.;Distributed+Systems+%C2%B7+Agentic+AI+%C2%B7+Deep+Learning;C%2B%2B+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+AWS" alt="Typing SVG" />

<br/>

<a href="https://www.linkedin.com/in/athelesh-balachandran-60a07927a/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="30" alt="LinkedIn"/>
</a>
<a href="https://builder.aws.com/community/@athelesh">
  <img src="https://img.shields.io/badge/AWS_Builder_Center_Profile-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" height="30" alt="AWS Builder Center"/>
</a>
<a href="mailto:atheleshbalachandran14@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="30" alt="Gmail"/>
</a>
<a href="https://leetcode.com/u/Athelesh_B14/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" height="30" alt="LeetCode"/>
</a>

</div>

---

## 👋 About

Final-year **Electrical & Electronics Engineering** student at **PSG iTech, Coimbatore** — building production-ready software systems that solve real problems.

I work across the stack: **distributed, event-driven architectures** on AWS, **Large Language Models** and **multi-agent AI platforms**, **deep learning pipelines** for computer vision, **data science and ML modeling**, and **full-stack applications** that people actually use. I write **C++** for algorithms and data structures, and ground every build in **operating systems, databases, and system design fundamentals**.

One principle holds across all of it: **systems should behave predictably under real conditions.** Deterministic logic where correctness matters. Measured latency. Traceable decisions. Tests that prove the thing works.

I care about building software that works reliably, scales predictably, and solves real problems.

---

## 🏆 International Recognition

🥇 **AWS 10,000 AIdeas — Asia Pacific & Japan (APJC) Regional Champion 2026**
International winner among **10,000+ teams across 115 countries** for building **Veloquity**. Awarded **$15,000 prize support** and **$1,500 AWS credits**; invited to showcase at **AWS re:Invent, Las Vegas** 🇺🇸

📰 **Featured in Business Today** — joint media interaction with **Jeff Barr** *(VP & Chief Evangelist, AWS)*, conducted by Neetu Chandra *(Senior Editor, Business Today)*

---

## 🚀 What I've Built

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [Veloquity](https://github.com/Athelesh-7G/Veloquity-showcase)
`AWS APJC Regional Champion`

**Problem** — Enterprise product teams drown in fragmented feedback. There's no traceable path from raw signal to a decision you can defend.

**Built** — Event-driven multi-agent system on AWS. Four-stage serverless pipeline: ingestion → evidence extraction → semantic retrieval → governance, with fault isolation at every boundary.

**Proof** — 857 real records · ~$0.03/run · ~91s latency · **158 automated tests (100% passing)** · full source-to-decision traceability.

`AWS Lambda` `Bedrock` `pgvector` `EventBridge` `Python`

📺 [Demo](https://youtu.be/wEG5jTQxlJ4) · 📰 [Article](https://builder.aws.com/content/3AzrKpJbhJwEP6EZbm87vdxufgi/aideas-finalist-veloquity-the-agentic-evidence-intelligent-platform-turning-raw-feedback-into-evidence-driven-decisions)

</td>
<td width="50%" valign="top">

### ⚡ [Magnivonic](https://github.com/Athelesh-7G/magnivonic)
`H0: Hack the Zero Stack — AWS × Vercel`

**Problem** — Finance sees revenue. Ops sees delivery. Security sees risk. Nobody sees the whole board until it's too late.

**Built** — Two-tier, 6-agent architecture. Four parallel domain agents — **Revenue, Customer, Operations, Security** — via `ThreadPoolExecutor` → Chief of Staff coordinator → General Manager orchestrator.

**Design principle** — All scoring is **deterministic in code**. The LLM narrates. It never invents a number.

`Aurora Serverless v2` `pgvector` `Polly` `GitHub API` `Slack` `Next.js`

📺 [Demo](https://youtu.be/yHm4YSJl2-k) · 📰 [Article](https://builder.aws.com/content/3CPrQNB11R9JUMP9XPZxUvwuUIu/magnivonic-the-organizational-intelligence-layer-for-the-enterprise-or-h0-hack-the-zero-stack-with-vercel-v0-and-aws-databases)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 👁️ [DL-based Computer Vision Model for Human Face Authentication](https://github.com/Athelesh-7G)
`Deep Learning · Computer Vision`

**Problem** — Face authentication is only as strong as its weakest link: a printed photo or a replayed video should never pass as a live human.

**Built** — Multi-stage DL pipeline. **YOLOv8** fine-tuned on **12.5K face images** at 640×640 for real-time detection → **PAD (Presentation Attack Detection)** fine-tuned on **16.5K images** for liveness and anti-spoofing → **FaceNet** recognition using pretrained VGGFace2 embeddings (3.3M images, 9,131 identities) → SQLite verification logging.

**Proof** — **18.23 hours** of fine-tuning across 50 epochs on an RTX 4050 · **~29K images** total · **86% accuracy** under live camera conditions · **40% latency reduction** via ONNX export. **Zero cloud dependency, zero external APIs.**

`YOLOv8` `FaceNet` `MobileNet V2` `ONNX` `PyTorch` `SQLite`

</td>
<td width="50%" valign="top">

### 📊 [LLMs Assemble](https://github.com/Athelesh-7G/llms-assemble)
`Data Science · ML Modeling`

**Problem** — Choosing an LLM means balancing capability, cost, speed, and efficiency. Nobody had quantified that trade-off space.

**Built** — Full data science pipeline evaluating **40 LLMs** across 10 raw metrics and 4 composite scores. **K-Means clustering** into 4 tiers, **PCA** projection, weighted composite ranking across 6 use-case profiles — surfaced through a 9-page interactive React dashboard with live-adjustable weight sliders.

**Scale** — 480 monthly snapshots · 11×11 correlation matrix · CSV export · aggregated from HuggingFace, BigCode, and Artificial Analysis leaderboards.

`Python` `scikit-learn` `pandas` `React 18` `TypeScript` `Recharts`

🌐 [Live Demo](https://llms-assemble.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎛️ [OptiMelon](https://github.com/Athelesh-7G/optimelon)
`Multi-Model Orchestration`

**Problem** — With 10+ viable LLMs available, picking the right one per request is a cost/latency/quality optimization nobody wants to do by hand.

**Built** — Provider-abstracted orchestration layer with adaptive routing across **10+ open-source LLMs** and image generation models — scored on task complexity, cost, and specialization.

**Instrumented** — Real-time telemetry dashboard tracking per-model latency, token throughput, and routing distribution.

`Next.js` `Node.js` `TypeScript` `Multi-provider APIs`

</td>
<td width="50%" valign="top">

### 🔌 [Edge AI Predictive Maintenance](https://github.com/Athelesh-7G/edge-ai-predictive-maintenance)
`Edge ML · Signal Processing`

**Problem** — Industrial motors fail without warning, and cloud round-trips are too slow to act before damage is done.

**Built** — On-device ML inference pipeline. **FFT-based feature engineering** on live vibration and current signatures → hyperparameter-tuned **Random Forest** classifier distinguishing mechanical from electrical fault signatures at **93% accuracy**.

**Closed the loop** — Local alerts (buzzer, LED, LCD, **automatic relay shutdown**) plus a cloud dashboard. It doesn't just predict the fault — it acts on it.

`Python` `scikit-learn` `MQTT` `Signal Processing`

</td>
</tr>
</table>

---

## 🛠️ Engineering Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=cpp,c,python,ts,js&theme=dark" height="55" alt="Languages"/>

`C++` · `C` · `Python` · `TypeScript` · `JavaScript`

<br/>

**Cloud & Backend**

<img src="https://skillicons.dev/icons?i=aws,postgres,nodejs,nextjs,react,vercel&theme=dark" height="55" alt="Cloud and Backend"/>

`AWS` · `PostgreSQL` · `Node.js` · `Next.js` · `React` · `Vercel`

<br/>

**AI / ML & Tools**

<img src="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow,git,github,vscode&theme=dark" height="55" alt="AI ML and Tools"/>

`PyTorch` · `scikit-learn` · `TensorFlow` · `Git` · `GitHub` · `VS Code`

</div>

<br/>

**Core CS** — Operating Systems · Database Management Systems · Object-Oriented Programming

**Cloud (AWS)** — Lambda · Bedrock · S3 · RDS · Aurora Serverless · EventBridge · IAM · Serverless & Event-Driven Architecture

**AI / ML** — LLMs · Agentic Systems · RAG · Vector Search (pgvector) · Deep Learning · Computer Vision · K-Means · PCA · Random Forest · ONNX

---

## 💼 Experience

**AI/IoT Engineering Intern** · *DO365 Technologies* · `Jul 2025 – Jan 2026`

Engineered a deep learning computer vision system for human face verification — YOLOv8 detection, FaceNet recognition, and MobileNet V2 liveness verification via Presentation Attack Detection. Achieved **86% accuracy** on a live multi-user dataset and cut inference latency **40%** through ONNX export and batch optimization. Deployed as a real-time pipeline with zero cloud dependency.

---

## 🎖️ Achievements

- 🌟 **Young Innovator 2026** — Awarded by PSG iTech at the Annual Day Ceremony for outstanding achievement across innovation competitions, hackathons, and technical excellence
- 🥇 **First Place** — Department Project Expo **2025 & 2026** (EEE)
- 🥇 **First Place** — Industry Academia Conclave Expo 2025
- 🏅 **Top 5 + Spotlight Award** — Campus Ideathon (150+ teams); special jury mention for Edge AI Predictive Maintenance

---

<div align="center">

### Open to Software Engineering Roles

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" width="100%"/>

</div>
