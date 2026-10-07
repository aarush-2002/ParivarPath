# 🛤️ ParivarPath: AI-Enabled Family Decision-Support Platform

**"Turning Parental Fears into Family Pride."**

[![SIH 2026](https://img.shields.io/badge/SIH-2026-2B2D6E?style=for-the-badge&logo=smartindia&logoColor=white)](https://sih.gov.in/)
[![Problem Statement](https://img.shields.io/badge/PS_ID-26241-F5A623?style=for-the-badge)](https://sih.gov.in/)
[![Theme](https://img.shields.io/badge/Theme-Smart_Education-2B2D6E?style=for-the-badge)](https://sih.gov.in/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

##  About The Project

Despite the push for skill development under India’s NEP 2020 and NSQF, vocational training faces a critical bottleneck: **high mid-course dropout rates and low initial enrolment**, primarily driven by parental resistance. 

Existing digital counselling tools are learner-centric, text-heavy, and rely on generic national data that fails to build trust in rural, low-literacy demographics. 

**ParivarPath** introduces a paradigm shift from "Learner-Only" to **"Family-First"** counselling. By leveraging a Voice-First AI, a unique "Family Decision Room" architecture, and a Verified Outcome Ledger with strict anti-hallucination guardrails, ParivarPath resolves the 8 core parental objections in local dialects. Furthermore, it provides MSDE administrators with a "Resistance-to-Action" dashboard, transforming passive enrolment data into active, targeted policy interventions.

---

## ✨ Key Features & Innovations

### 🧠 1. The "Family Decision Room" (FDR)
A psychological AI mediation space. Instead of forcing awkward family arguments, the learner and parent use **Private Lanes** to voice their hidden fears. The AI then brings them to a **Joint 'Common Ground' screen** to resolve objections peacefully.

### 🛡️ 2. Verified Outcome Ledger & Trust Grades (L0-L3)
We don't just chat; we prove. The AI pulls from a strictly verified database:
* **L0:** Unverified web data (Hidden).
* **L1:** Institutional data.
* **L2:** Cohort-matched local data (Shown to users).
* **L3:** Blockchain/Alumni verified data (Shown to users).

### ⚖️ 3. Radical Honesty Engine
Features a **"Not-For-You" mode**. If a course genuinely doesn't fit the student's aptitude or the family's finances, the AI honestly recommends alternatives. A tool that sometimes says "no" builds unbreakable trust.

### 📊 4. Resistance-to-Action Dashboard (For MSDE)
Moves beyond static charts. Pinpoints *exactly why* families resist in specific blocks (e.g., "Block X has 70% Safety Fear") and recommends specific interventions (e.g., "Deploy female alumni voice notes here").

### 🎙️ 5. Voice-First, Zero-Install UX
Works on WhatsApp, IVR, and lightweight PWAs. Integrated with **Bhashini API** for seamless dialect translation, designed specifically for low-literacy rural parents.

---

## ️ Technology Stack

### Frontend & UX
* **Next.js** (Lightweight PWA for low-bandwidth areas)
* **React Native** (Facilitator/Assisted Mode Tablet App)
* **Tailwind CSS** (Icon-first, large-button design)
* **Bhashini API** (Govt stack for Voice/Translation)

### Backend & API
* **FastAPI** (Python - High-performance AI pipelines)
* **Node.js / Express** (RESTful APIs & WebSockets)
* **WhatsApp Business Cloud API** (Zero-install entry)

### AI & Intelligence Layer
* **Llama 3 / Mistral** (Fine-tuned RAG pipeline)
* **LangChain** (Orchestration)
* **Hume AI** (Vocal emotion & sentiment analysis)
* **Custom Guardrails** (Number-check & Bias-audit scripts)

### Database & Storage
* **PostgreSQL + pgvector** (Relational data + Semantic vector search)
* **IPFS / Polygon** (Lightweight blockchain hashing for L3 Ledger)
* **AWS S3 / Cloudinary** (Media storage for voice notes & 360° tours)

### Maps & Analytics
* **Mapbox** (Ghar-Ke-Paas local job maps)
* **Recharts / D3.js** (Admin Resistance Heatmaps)

---

## 🏗️ System Architecture

```text
[User Layer] ➡️ [API Gateway] ➡️ [AI Orchestrator] ➡️ [Data Layer] ➡️ [Admin Layer]
(WhatsApp/PWA)   (Auth/Rate)      (Bhashini/LLM)     (Postgres/pgvector) (Heatmap)
