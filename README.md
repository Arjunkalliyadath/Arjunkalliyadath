<div align="center">

# Arjun K

**I build systems that figure out what people actually mean —**
**whether that's a tweet, a scanned tax form, or a hand sign.**

[![Email](https://img.shields.io/badge/Email-arjunkalliyadath2001%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:arjunkalliyadath2001@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arjun--k-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arjun-k-062298211/)
[![Credly](https://img.shields.io/badge/Credly-Badges-FF6D00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/go/qs2sCLyH)
[![Location](https://img.shields.io/badge/Kozhikode-Kerala%2C%20India-555?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

### About

Most of the projects below share one habit: take something messy and
human — a tweet, a Google review, a YouTube comment thread, a scanned GST
form, a hand gesture on a webcam — and turn it into something a computer
can reliably act on. Five different dashboards ask some version of "what is
this data actually saying." One pipeline reads real government paperwork so
a person doesn't have to type it out by hand. One turns sign language into
speech. Same instinct, different targets.

I'm a Computer Science engineer with a Data Science specialization, a year
of hands-on systems administration experience, and a habit of shipping
projects end-to-end — model, backend, frontend, and deployment — rather
than stopping at a notebook.

🔭 **Currently:** just wrapped a 3-month AI/ML internship at Ladder7
Solutions, and looking for my next role — Data/ML, backend, or general
software engineering. I'm early-career and genuinely not precious about the
title; I want to build things and get better at it.
📍 Kozhikode, Kerala, India · 📫 arjunkalliyadath2001@gmail.com

---

### Experience

**AI/ML Intern — Ladder7 Solutions** · Thiruvananthapuram · Jun 2026 – Sep 2026
Three-month internship with Ladder7's applied-AI / digital engineering
practice, working on AI/ML-driven automation. *(Write-up coming once my
completion certificate is in hand.)*

**Graduate Apprentice, System Administrator (AI & Data Systems) — Keltron**
*(Kerala State Electronics Development Corporation Ltd.)* · Kozhikode · Jun 2024 – Jun 2025
Ran IT infrastructure for the **Safe Kerala AI Camera Project** for the
Motor Vehicles Department — 100+ AI surveillance cameras at the District
Enforcement Control Room, kept at **99.5% uptime**. Handled server and
network administration, real-time camera health monitoring, and built
automated reporting pipelines for MVD certification and billing.

**WordPress Developer Intern — Stalza Technologies** · Jun 2022 (15 days)
Built and deployed a live production website with custom PHP plugins and
performance optimization.

---

### Featured work

#### 🔍 Making sense of what people say
Same core pipeline — scrape → clean → score with a fine-tuned RoBERTa
sentiment model → visualize — pointed at five different sources.

- **[TrustLens](https://github.com/Arjunkalliyadath/TrustLens)** — turns
  platform trust & safety transparency reports (Meta, X, WhatsApp, and
  others) into unit-normalized analytics, with anomaly detection, per-org
  forecasting, and an offline Q&A assistant. `Python · Streamlit · Isolation Forest`
- **[StarSense](https://github.com/Arjunkalliyadath/StarSense)** —
  point it at a business name and it fully automates Google review
  collection and sentiment breakdown into a live animated dashboard.
  `FastAPI · Playwright · RoBERTa`
- **[PulseScope](https://github.com/Arjunkalliyadath/PulseScope)** — scrapes
  a YouTube video's comments and scores them for sentiment, curated into a
  dashboard instead of a wall of raw data. `FastAPI · Playwright · HuggingFace`
- **[Tweet-Pulse](https://github.com/Arjunkalliyadath/Tweet-Pulse)** — pulls
  the replies on a tweet/X post and lays out how the conversation actually
  reacted, with the highest-confidence comments per sentiment surfaced
  first. `FastAPI · Playwright · HuggingFace`
- **[MoodRing](https://github.com/Arjunkalliyadath/MoodRing)** — a general-
  purpose sentiment reader for any text, single or batch (up to 200 lines),
  with a dial-style live gauge. `Flask · PyTorch · RoBERTa`

#### 📄 Document AI & automation
- **[GST2A Document AI Pipeline](https://github.com/Arjunkalliyadath/GST2A-Document-AI-Pipeline)**
  — the most technically involved thing here. A dual-path system that
  routes clean digital PDFs through direct extraction and routes scanned
  photos through a **triple-OCR ensemble** (PaddleOCR + Tesseract +
  EasyOCR) with auto-rotation and shadow correction, refined by a
  fine-tuned **LayoutLMv3**, cross-checked by a local offline LLM, and
  set up to **auto-retrain** as corrected documents accumulate.
  `React · Django · FastAPI · LayoutLMv3 · Celery/Redis · PostgreSQL`
- **[Browsebrief](https://github.com/Arjunkalliyadath/Browsebrief)** — point
  it at any URL and it scrapes the page with Playwright and hands back an
  LLM-generated summary. `Python · Playwright · LangChain · Groq`

#### 🤟 Accessibility & computer vision
- **[Sign Language to Text](https://github.com/Arjunkalliyadath/Sign-Language-to-Text)**
  — a real-time ASL fingerspelling reader: webcam → hand segmentation → CNN
  → sentence-building with word-completion → text-to-speech. Co-authored a
  paper on it at **IEEE ICCCI 2023** and won **Best Paper** at KARE's
  Project Expo. `Python · TensorFlow/Keras · OpenCV · MediaPipe`

#### 🧰 Also shipped
- **[Car-Price-Prediction](https://github.com/Arjunkalliyadath/Car-Price-Prediction)**
  — Random Forest regressor (R² 0.93) estimating used-car resale value,
  deployed as a Flask app. `Flask · Scikit-learn`
- **[Netflix-Tudum](https://github.com/Arjunkalliyadath/Netflix-Tudum)** —
  a full Netflix-style browsing experience from scratch: real auth, a
  seeded catalog, live search, a watchlist. `Django · Bootstrap · PostgreSQL`
- **[PMSS — Password Manager](https://github.com/Arjunkalliyadath/PMSS)**
  — salted SHA-1 password storage on top of a hash table I implemented
  from scratch (linear probing, dynamic rehashing). Presented at ICCES
  2022. `Java · Swing`
- **[Calculator_Neon](https://github.com/Arjunkalliyadath/Calculator_Neon)**
  — a cyberpunk-themed calculator with full keyboard support and an
  animated glowing UI. `HTML · CSS · JavaScript`

*(Live demo links are in each repo's README — Render's free tier spins
down when idle, so give a demo ~30–50s to wake up on first load.)*

---

### Skills

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / AI**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)

**Data & Visualization**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

**Backend & Web**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Infra & Tools**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)

Also comfortable in Tableau outside of code — a sales-performance dashboard
on the classic Superstore dataset and a restaurant-analytics dashboard on
Zomato data, both built in Tableau Desktop.

---

### Certifications

- 🎓 Certified Specialist in Data Science and Analytics (375 hrs) — ICT Academy of Kerala, 2026
- 🎓 IBM Data Science Graduate — IBM, 2023
- 🎓 Python for Data Science (Elite) — NPTEL, IIT Madras, 2025
- 🎓 Tableau 2024.1 Essential Training — LinkedIn Learning, 2025
- 🎓 Complete Guide to Apache Kafka for Beginners — LinkedIn Learning, 2025

### Education

**B.Tech, Computer Science & Engineering** (Data Science specialization, built in partnership with IBM)
Kalasalingam Academy of Research and Education — 2019 – 2023

---

<div align="center">

*If any of this looks like a fit for a role you're hiring for, my inbox is open.*

[![Email](https://img.shields.io/badge/Say%20hello-arjunkalliyadath2001%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arjunkalliyadath2001@gmail.com)

</div>
