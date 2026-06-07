# Peyton Nagle

Software engineering student at the University of Arizona (B.S., grad May 2027, GPA 3.99). I build full-stack web apps and the systems behind them — APIs, databases, deployment, networking. Recently won HackArizona 2026 with a 14-day nuclear derating forecaster.

Looking for software engineering internships and new-grad roles for summer 2026 and beyond.

📍 Tucson, AZ &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/peyton-nagle)

---

## What I work on

Most of my work is full-stack: building the frontend, the API layer, the data store, and getting it deployed and running. At Space4 (undergraduate research) I also do infrastructure work — I built and deployed a 10-node Dask compute cluster with NFS shared storage and Layer 2 static IP networking to parallelize data pipelines, and a full-stack monitoring app for live camera feeds. I've also shipped applied ML in projects, mostly using established models and frameworks to solve a concrete problem.

**Languages:** Python, Java, C/C++, Bash
**Backend:** Flask, FastAPI, Spring, Postgres
**Frontend:** Next.js, JavaScript
**Infra & tools:** Linux/Unix, systemd, Git, Maven, Dask
**ML (applied):** PyTorch, CNNs

---

## Projects

**[SpeakEasy](https://github.com/NateDeMoro/QuackHacksWildcats)**
Browser-based real-time speech practice coach built for the Google Track at QuackHacks. Paste your slides or script, describe your audience, then speak — the app tracks volume, pace, pauses, and pitch on-device while you practice, then generates a Gemini report judging your delivery against your actual material ("too much jargon for this audience," "you skipped your second point"). Also flags tone-content mismatches by comparing Gemini sentiment against acoustic prosody. pnpm TypeScript monorepo: a React/Vite SPA handling on-device audio processing, a Hono API on Cloud Run proxying Vertex AI and writing sessions to Firestore, served from Firebase Hosting with keyless ADC throughout.
React · TypeScript · Hono · Vertex AI · Gemini · Firebase · Cloud Run · Firestore

**[Nuclear Weather-Based Derating Forecaster](https://github.com/NateDeMoro/Team_10_HackArizona)**
🏆 1st place, HackArizona 2026 AI Environmental Sustainability challenge (sponsored by Nuclearn.ai), against 100+ students. A public 14-day nuclear derating forecast, addressing $200M+/year in industry losses. Built and deployed the full pipeline in 24 hours: a Next.js operator dashboard, a FastAPI service, a Postgres artifact store, and daily weather and river data refresh jobs. XGBoost regressors trained on 25+ years of NRC, USGS, and Open-Meteo data.
*Next.js · FastAPI · Postgres · Python · XGBoost*

**[MoodMusic](https://github.com/PeytonNagle/MoodMusic2)**
Full-stack LLM-driven music recommendation system. Takes a user's mood and constraints, generates and filters song candidates, enriches results through the Spotify API, and stores listening history in Postgres. Built while studying abroad in Seoul, leading a 5-country team — I defined the architecture, set weekly plans, and assigned task ownership to ship a working prototype on schedule.
*Full-stack · LLM API · Spotify API · Postgres*

**[Instrument & Genre Classifier](https://github.com/PeytonNagle/InstrumentGenreClassifier)**
Multi-phase PyTorch CNN pipeline for music genre classification. Pre-trained on NSynth (305K samples), fine-tuned on IRMAS, then fused instrument predictions with audio features to improve GTZAN classification. Evaluated with statistical testing (McNemar's) and standard metrics to confirm the instrument features actually helped.
*PyTorch · CNNs · Python*

---

## Currently

Full-stack SWE intern at Nuclearn.ai (June 2026–present), building React/FastAPI software deployed across 60+ nuclear reactors. Previously undergraduate research assistant at Space4, where I built compute and monitoring infrastructure for astronomical observation. Finishing my B.S. in Software Engineering at the University of Arizona (May 2027), then continuing into the Software Engineering AMP for an accelerated M.S. Seeking Fall 2026 and Summer 2027 SWE internships.
