# 👻 Rashomon of the Dead

> A local, open-model detective game where five haunted ghosts witnessed a single manor death—and each tells a different story.

![Hacktoberfest Project](https://img.shields.io/badge/Hacktoberfest-2026-orange?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 📌 Overview
"Rashomon of the Dead" is an offline-first cross-examination detective game powered by local LLMs (Gemma via Ollama) and speech synthesis. The mystery operates on a **Ground Truth Fact Ledger**—a structured dataset storing the exact true events of the murder. 

Each ghost witness receives only a partial or biased slice of this ledger, allowing players to cross-examine, catch contradictions, and solve the case.

---

## ✨ Key Features
- **Open-Model & Offline First:** Runs 100% locally using Gemma via Ollama (`http://localhost:11434`) with fallback offline logic.
- **5 Ghost Witnesses:** Distinct voices, pitch/rate controls, avatar profiles, and biased perspectives.
- **Ground Truth Fact Ledger Inspector:** Direct view of true case facts vs. ghost-specific knowledge slices.
- **Real-Time Contradiction Engine:** Automatically flags lies against the ledger with visual highlight cards.
- **Accusation Matrix:** Submit culprit, weapon, and motive with instant evaluation and victory sequences.

---

## 🛠️ Quick Start

1. Open `index.html` directly in any modern web browser.
2. (Optional) Connect local Gemma via Ollama:
   ```bash
   OLLAMA_ORIGINS="*" ollama serve
