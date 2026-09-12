<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,100:243B55&height=200&section=header&text=Arjun%20K&fontColor=ffffff&fontSize=52&fontAlignY=38&animation=fadeIn&desc=Software%20Engineer%20%E2%80%A2%20Data%20%2F%20ML%20%E2%80%A2%20Full-Stack%20%E2%80%A2%20Systems&descAlignY=58&descSize=17&descAlign=50" width="100%"/>

**I build systems that figure out what people actually mean —**
**whether that's a tweet, a scanned tax form, or a hand sign.**

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1200&color=4C9BE8&center=true&vCenter=true&width=680&lines=Open+to+Software+%2F+Data+%2F+ML+%2F+IT+Systems+roles;13%2B+projects+shipped+end-to-end+%E2%80%94+not+just+notebooks;Currently+interviewing+%E2%80%94+let%27s+talk)](https://www.linkedin.com/in/arjun-k-062298211/)

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
can reliably act on. Several dashboards ask some version of "what is this
data actually saying." One pipeline reads real government paperwork so a
person doesn't have to type it out by hand. One turns sign language into
speech. Same instinct, different targets.

I'm a Computer Science engineer with a Data Science specialization, a year
of hands-on systems administration experience running real infrastructure
(not lab exercises), and a habit of shipping projects end-to-end — model,
backend, frontend, and deployment — rather than stopping at a notebook.

🔭 **Currently:** interviewing for my next role. Genuinely open to
Software Engineering, Data/ML, or IT Systems positions — I'm early-career
and not precious about the title; I want to build things, keep real
infrastructure running, and get better at both.
📍 Kozhikode, Kerala, India · 📫 arjunkalliyadath2001@gmail.com

<div align="center">

| 🎓 B.Tech CSE + IBM Data Science specialization | 🛠️ 13 end-to-end projects shipped | 🖥️ 1 yr production IT systems — 100+ cameras, 99.5% uptime | 📜 IEEE-published + Best Paper award |
|:---:|:---:|:---:|:---:|

</div>

---

### Experience

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

Grouped by the kind of problem, not the tech — the stack repeats
(FastAPI/Flask + Playwright + a fine-tuned RoBERTa model shows up five
times below) because the same pipeline shape turns out to answer a lot of
different questions: scrape → clean → score → visualize.

**A 20-second look at the most complete one** — point it at a company
website and it discovers their products, pulls customer reviews from
five different platforms in parallel, scores sentiment, and hands back a
dashboard plus a downloadable PDF report:

https://github.com/user-attachments/assets/5a446b86-50bf-4410-a17f-a2a6eede409c

#### 🔍 Making sense of what people say

- **[Manobhava-AI](https://github.com/Arjunkalliyadath/Manobhava-AI)** —
  discovers a company's products straight from its website, then collects
  and analyzes customer feedback across Google, Twitter, Instagram,
  YouTube, and Reddit in parallel, scores it with RoBERTa, and generates
  an interactive dashboard plus a PDF report. The widest-scope thing here.
  `FastAPI · Playwright · HuggingFace · ReportLab`
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

- **[GSTVision-AI](https://github.com/Arjunkalliyadath/GSTVision-AI)**
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

- **[Sign-Language-Translator](https://github.com/Arjunkalliyadath/Sign-Language-Translator)**
  — a real-time ASL fingerspelling reader: webcam → hand segmentation → CNN
  → sentence-building with word-completion → text-to-speech. Co-authored a
  paper on it at **IEEE ICCCI 2023** and won **Best Paper** at KARE's
  Project Expo. `Python · TensorFlow/Keras · OpenCV · MediaPipe`

#### 🧰 Also shipped

- **[Car-Price-Prediction](https://github.com/Arjunkalliyadath/Car-Price-Prediction)**
  — Random Forest regressor (R² 0.93) estimating used-car resale value,
  deployed as a Flask app. `Flask · Scikit-learn` · [🌐 live demo](https://car-price-prediction-1-wjcu.onrender.com)
- **[Netflix-Tudum](https://github.com/Arjunkalliyadath/Netflix-Tudum)** —
  a full Netflix-style browsing experience from scratch: real auth, a
  seeded catalog, live search, a watchlist. `Django · Bootstrap · PostgreSQL` · [🌐 live demo](https://netflix-tudum.onrender.com)
- **[Password-Manager](https://github.com/Arjunkalliyadath/Password-Manager)**
  — salted SHA-1 password storage on top of a hash table implemented
  from scratch (linear probing, dynamic rehashing). Presented at ICCES
  2022. `Java · Swing`
- **[Calculator_Neon](https://github.com/Arjunkalliyadath/Calculator_Neon)**
  — a cyberpunk-themed calculator with full keyboard support and an
  animated glowing UI. `HTML · CSS · JavaScript` · [🌐 live demo](https://calculator-app-dw4t.onrender.com)

*(The three 🌐 live demos run on Render's free tier, so give them ~30–50s
to wake up on first load. Everything else is a local run — most have a
short demo video right in the repo's own README.)*

---

### Skills

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Web**
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

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

**Systems & IT Infra**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Networking](https://img.shields.io/badge/Networking%20%26%20Server%20Admin-4B5563?style=flat-square)

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,100:243B55&height=100&section=footer" width="100%"/>

</div>
