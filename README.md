# Victor Stroganov

CompEng grad, Toronto Metropolitan University (May 2026). I build tools I actually want to use.

Five years into language learning. Shipped a sentence mining tool in 2021 (5K YouTube subs), now shipping a full NLP-powered reading app. Also: real-time ASL translation on mobile, a processor built in Verilog, ML APIs on AWS.

Open to SWE and ML engineering roles in Toronto. French bilingual.

---

## Projects

### Auto-Lang

Language learning reader for people who take vocabulary acquisition seriously. Paste any text in your target language and each word gets highlighted by status across five tiers, tracked at the lemma level. Progress persists across texts and series.

Built because no existing tool tracked vocabulary at the lemma level. "Run", "runs", and "ran" are not three different words.

**Stack:** Next.js 16 · TypeScript · Supabase · Drizzle ORM · Transformers.js · TanStack Query · Chart.js

[Live Demo](https://your-url-here.vercel.app) *(deploying May 13, 2026)* | [Repo](https://github.com/amiothenes/auto-language-learning)

---

### AI-Based ASL Translation Application (Capstone)

Real-time American Sign Language translation on mobile. Camera input, live classification across 37 signs (A-Z, 0-9, DEL), 97.7% accuracy.

Classifier: SVM with RBF kernel (C=10, gamma='scale') on 166 engineered features per frame. MediaPipe extracts shoulder orientation, per-hand landmark coordinates, finger direction angles, and inter-fingertip distances. z-score normalization via StandardScaler.

**Stack:** React Native (Expo) · FastAPI · MediaPipe · scikit-learn · Python

[Repo](https://github.com/M4TT905/AI-Based_ASL_Translation_Application)

---

### 1T Sentence Miner

Python tool that finds optimal i+1 sentences in language learning material for Anki flashcard mining. Built in 2021 while studying German. Made a YouTube channel explaining the method, got to 5K subscribers.

[Repo](https://github.com/amiothenes/1T-Sentence-Miner)

---

## Also Built

- **Semi-RISC CPU** (Verilog): custom processor with full instruction set and pipeline stages
- **Pet Image Classifier** (Python, AWS Lambda, API Gateway): CNN deployed serverless on AWS
- **Maze-Solving Robot** (C++, Arduino): autonomous navigation with obstacle detection

---

## Connect

[LinkedIn](https://www.linkedin.com/in/victor-stroganov/) · [Twitter / X](https://x.com/vic_strog)
