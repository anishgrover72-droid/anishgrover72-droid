<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0b1f3a,100:1f6feb&height=190&section=header&text=Anish%20Grover&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=I%20build%20AI%20that%20leaves%20the%20notebook%20and%20goes%20to%20work.&descAlignY=58&descSize=18&animation=fadeIn" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2400&pause=800&color=58A6FF&center=true&vCenter=true&width=900&lines=Agentic+AI+%C2%B7+Multi-Modal+Systems+%C2%B7+RL+for+LLMs;%232+in+India+out+of+39%2C000%2B+%E2%80%94+Samsung+Solve+for+Tomorrow+2026;Teaching+small+models+to+think+%E2%80%94+GRPO+%2B+RLVR+on+ONE+GPU;4+hours+of+RFP+work+%E2%86%92+under+5+minutes;Shipping+production+AI+%40+CogNerd+%C2%B7+Founder+%40+Grovell;Pepsi+India+runs+on+a+pipeline+I+built" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anish-grover-686741274/"><img src="https://img.shields.io/badge/LinkedIn-Anish%20Grover-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anishgrover72@gmail.com"><img src="https://img.shields.io/badge/Email-anishgrover72%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Mohali%2C%20Punjab-1f6feb?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=anishgrover72-droid&label=Profile%20Views&color=1f6feb&style=flat-square" />
</p>

---

## ◈ About Me

I'm an **AI/ML engineer** and **ECE undergraduate at Thapar Institute** (Class of 2028) building production **agentic and multi-modal AI systems**.

My work spans **LLM fine-tuning with reinforcement learning (GRPO / RLVR)**, **multi-agent pipelines**, **RAG**, **multimodal anomaly detection** and **full-stack deployment** with FastAPI, Node/TypeScript, PostgreSQL, React Native and Docker. I've shipped production software across **five internships**, automated CRM operations for **Pepsi India**, and finished **2nd of 39,000+** in Samsung Solve for Tomorrow 2026.

> **Most student projects end at a demo video. Mine end with a user.**
> Stroke survivors monitored from a 45-second phone check. Real-estate leads booked in under a minute, in three languages. A distributor reconciling their books in 10 minutes instead of 2 hours.
> I care less about the model and more about the system around it: the alerting logic, the sync layer, the edge case that breaks it at 2 AM.

<table>
<tr>
<td align="center" width="20%"><h3>#2</h3><sub>in India · Samsung Solve for Tomorrow · 39,000+ entries</sub></td>
<td align="center" width="20%"><h3>5</h3><sub>hackathon podiums · India, UK, International</sub></td>
<td align="center" width="20%"><h3>5</h3><sub>internships before 3rd year</sub></td>
<td align="center" width="20%"><h3>~40%</h3><sub>fewer reasoning tokens with AXIOM</sub></td>
<td align="center" width="20%"><h3>48×</h3><sub>faster RFP processing with ProcurenAI</sub></td>
</tr>
</table>

---

## ◈ Education

| Institution | Program | Years |
|---|---|---|
| **Thapar Institute of Engineering & Technology** | B.Tech, Electronics & Communication Engineering | 2024 – 2028 (expected) |
| **GMSSS Sector 46, Chandigarh** | Higher Secondary, Science Stream | 2022 – 2024 |

---

## ◈ Experience

### 🧠 AI/ML Intern · **CogNerd** · *2026 – Present*
- Ship features in the **production Python codebase** for the company's AI products, from requirements through code review and release.
- Building **Content Studio**, an LLM-assisted content generation and search-visibility feature, iterating on model output against live client feedback.

### 🚀 Founder's Office Intern · **Welzin AI** · *2025 – Present*
- Technical and strategy support for an early-stage AI startup: competitor and market analysis of AI products, KPI tracking and process documentation.

### 📈 Business Development & Data Intern · **HITGOC** · *Aug – Oct 2025*
- Built **ML lead-quality scoring models** and SQL-backed pipeline dashboards to rank high-conversion prospects and track metrics week over week.

### 📊 Data Systems & BD Intern · **Orygin AI** · *Jun – Aug 2025*
- Automated recurring reports and built lead-funnel dashboards, cutting manual effort by **~70%**.

### 🤝 Business Development Intern · **Glyptika Studios** · *Jan – Apr 2025*
- Funnel analysis and proposal preparation for client outreach. Where I learned to sell what I build.

---

## ◈ Flagship · NeuroTrace

### 🧠 [NeuroTrace](https://frontend-iota-six-b8p5bnee1l.vercel.app): A Stroke Recovery Monitor That Lives in Your Phone
🥈 **Runner-up, Samsung Solve for Tomorrow 2026: 2nd out of 39,000+ applications nationwide** · `2026` · [Live site](https://frontend-iota-six-b8p5bnee1l.vercel.app)

After a stroke, recovery is tracked in clinic visits weeks apart, and decline between those visits goes unseen. **NeuroTrace checks in every day, using only a phone.**

```text
45-sec phone session ─┬─► 🎙  Voice features   ─┐
   (camera + mic)     ├─► 😐 Facial movement   ─┼─► Per-patient baseline ─► Two-modality ─► 📲 WhatsApp alert
                      └─► ⚡ Reaction time     ─┘   (learned over 35 days)   agreement gate    to caregiver (Hindi)
```

- **Personal, not population, baselines:** every patient is compared against *their own* 35-day normal, not a textbook average.
- **Two-modality agreement gate:** an alert fires only when deviations **co-occur in two independent signals**, so one noisy channel can't cry wolf and caregivers don't learn to ignore it.
- **Built for Bharat:** no wearables and no app installs for the family. Alerts arrive **in Hindi on WhatsApp**, where caregivers already are.

---

## ◈ Featured Projects

### ⚡ AXIOM · Reinforcement Learning That Teaches Small Models to Reason · `2026`
Frontier reasoning is locked behind clusters. AXIOM is an RL fine-tuning framework I co-designed that brings it down to **a single GPU**.
- **Training:** GRPO + RLVR (group-relative policy optimisation with verifiable rewards)
- **Reward:** a **5-head process reward model** that grades each reasoning step, not just the final answer
- **Result:** **~40% fewer reasoning tokens.** Less rambling, same destination.

`PyTorch` `HuggingFace` `GRPO` `RLVR` `PRM`

### 🔐 Citadel · Authentication That Never Stops Checking · `2026`
🥉 *3rd Place, University of Derby Cybersecurity Hackathon (International)*

Banks verify you once at login, then trust whoever holds the session. **Citadel verifies you continuously, from the first keypress to logout**, using behavioural biometrics: how you type, tap and move. A hijacked session gets caught, and stolen credentials are useless without the behaviour behind them.

`Behavioural Biometrics` `Anomaly Detection` `Digital Banking`

### 🤖 ProcurenAI · A Multi-Agent Team That Answers RFPs · `2025`
RFP responses eat whole afternoons. ProcurenAI splits the job across **specialised LLM agents** and matches every requested item to the right SKU with **semantic search**, even when the wording doesn't match the catalogue.
**~4 hours → under 5 minutes (~48× faster).**

`LLMs` `Multi-Agent` `Embeddings` `FastAPI`

### ⚖️ [CORTEX](https://github.com/anishgrover72-droid/cortex) · Hiring AI That Has to Show Its Work · `2026`
Black-box hiring models are a liability. CORTEX ranks candidates on **evidence**, writes a **plain-language justification for every decision**, then **audits its own output for fairness** before anyone sees it. AI that's accountable by design, not by apology.

`LLMs` `Explainability` `Fairness Auditing`

### 🏠 [Real Talk AI](https://github.com/anishgrover72-droid/real-talk-ai-site) · The Sales Agent That Never Sleeps · `2026`
In real estate, the first reply wins the lead. Real Talk AI is a **WhatsApp LLM agent** that replies to, qualifies and **books site visits in under a minute**, fluently in **Hindi, Punjabi and English**. A 3 AM enquiry is booked before the broker wakes up.

`LLM Agents` `WhatsApp API` `Multilingual`

### 📦 Distribution CRM · A Sales Ledger That Works Without Internet · `2025`
Built for distributors whose reps work where the network doesn't. An **offline-first React Native** app with a Node/TypeScript + PostgreSQL sync engine.
**Daily reconciliation: ~2 hours → 10 minutes.**

`React Native` `TypeScript` `PostgreSQL` `Offline Sync`

### 🥤 CRM Automation · Pepsi India
Replaced manual CRM data entry and reporting with an **automated pipeline** for Pepsi India. Not a hackathon prototype: a system a real business team depends on.

`Python` `SQL` `ETL` `Automation`

### 🛡 [CyberSentinel](https://github.com/anishgrover72-droid/CyberSentinel) · ML Intrusion Detection · `2025`
Machine-learning intrusion detection and response that flags hostile network traffic with **92%+ accuracy**.

`Python` `Machine Learning` `Network Security`

---

## ◈ Research

🔬 **Battery remaining-useful-life prediction** *(paper in progress)*: physics-constrained generative modelling to predict how much life a battery has left.

---

## ◈ Hackathons & Awards

| Result | Event | Scale |
|---|---|---|
| 🥈 **Runner-up, 2nd of 39,000+** | Samsung Solve for Tomorrow 2026 · *NeuroTrace* | 🇮🇳 National |
| 🏆 **Winner** | Agentic AI Hackathon, University of Ulster | 🇬🇧 UK |
| 🏆 **Winner** | BIOS Hackathon 2025 | 🎓 University |
| 🥉 **3rd Place** | Cybersecurity Hackathon, University of Derby · *Citadel* | 🌍 International |
| 🥉 **3rd Place** | Hackathon, University of Derby | 🌍 International |
| 🏅 **Top 9 All India** | Case Competition, IIM Bangalore | 🇮🇳 National |

---

## ◈ Founder & Leadership

- 🏗 **Founder, [Grovell](https://grovell-website.vercel.app):** software and AI automation studio building custom **ERP, inventory and workflow-automation systems** for manufacturers, distributors and SMEs in India and abroad.
- 👥 **Founder, CollabSphere:** led a student dev team delivering **₹90,000** in paid client projects.
- 🚀 **Ambassador, Innovation Mission Punjab**
- 📋 **McKinsey Forward Program**

---

## ◈ Tech Stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge)

**AI / ML**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)
![LLMs](https://img.shields.io/badge/LLMs-6B21A8?style=for-the-badge)
![GRPO/RLVR](https://img.shields.io/badge/GRPO%20%2F%20RLVR-111827?style=for-the-badge)
![PRM](https://img.shields.io/badge/Process%20Reward%20Models-7c3aed?style=for-the-badge)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent%20Systems-0f766e?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-1d4ed8?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Multimodal](https://img.shields.io/badge/Multimodal-be185d?style=for-the-badge)

**Backend & Infra**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-374151?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Frontend, Mobile & Data**<br>
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Offline Sync](https://img.shields.io/badge/Offline--First%20Sync-0f766e?style=for-the-badge)
![ETL](https://img.shields.io/badge/ETL%20%26%20Dashboards-374151?style=for-the-badge)
![Lead Scoring](https://img.shields.io/badge/ML%20Lead%20Scoring-1d4ed8?style=for-the-badge)

---

## ◈ GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=anishgrover72-droid&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />
</p>

---

## ◈ Where I'm Headed

```text
Agentic AI   →  Agents that don't just chat: they qualify, book, reconcile, respond. Hours of work → minutes.
Multi-Modal  →  Health & security systems that trust no single signal. Voice + face + behaviour, cross-checked.
RL for LLMs  →  Reasoning cheap enough to run anywhere. GRPO, RLVR, process rewards, on one GPU.
Research     →  Physics-constrained generative models for battery remaining-useful-life prediction.
Open Source  →  Contributing to the AI tools I use every day · GSoC-bound.
```

---

<p align="center">
  <a href="https://www.linkedin.com/in/anish-grover-686741274/"><img src="https://img.shields.io/badge/LinkedIn-Anish%20Grover-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anishgrover72@gmail.com"><img src="https://img.shields.io/badge/Email-anishgrover72%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center"><i>"A model is a guess. A system is a promise. I build promises."</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:000000&height=110&section=footer" />
</p>
