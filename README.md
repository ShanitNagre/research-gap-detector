# 🔍 Research Gap Detector

> An AI-powered tool that analyses research abstracts and surfaces what's missing — gaps, citation opportunities, and open questions. Built as a concept extension of [Trinka AI](https://www.trinka.ai) by Crimson Interactive.

**Live Demo → [shanitnagre.github.io/research-gap-detector](https://shanitnagre.github.io/research-gap-detector)**

---

## What it does

Paste any research abstract and get back a structured intelligence report in seconds:

- **Novelty Score** — rates your abstract's completeness on a 1–10 scale with an animated ring chart
- **Research Gaps** — 3–5 specific gaps (methodological, conceptual, or empirical) with type tags
- **Citation Recommendations** — 4 research areas you should be referencing, with rationale
- **Open Research Questions** — questions your paper leaves unanswered that future work could address

---

## Why this exists

Trinka AI helps researchers write better. This tool extends that vision **upstream** — into the thinking and scoping phase *before* writing begins.

Most researchers don't know what they're missing until a reviewer tells them. This tool surfaces those gaps early, so researchers can strengthen their work before submission.

This is a working prototype exploring what a **Research Intelligence** feature layer could look like inside Trinka's product suite.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML / CSS / JS — single file, zero dependencies |
| AI Model | Llama 3.3 70B via Groq API |
| Backend Proxy | Cloudflare Workers (API key secured server-side) |
| Hosting | GitHub Pages |

---

## Features

- 4 preloaded example abstracts (ML Fairness, Climate Science, Neuroscience, NLP/LLMs) — demo ready instantly
- Animated loading steps with real-time progress
- Animated score ring with color coding (green / amber / red)
- Gap tags: `methodology`, `field`, `urgent`
- Citation type labels: `Foundational Theory`, `Methodological`, `Empirical`, `Comparative`
- Fully responsive, dark theme UI
- No login, no setup — just open and use

---

## Local Development

```bash
# Clone the repo
git clone https://github.com/shanitnagre/research-gap-detector.git
cd research-gap-detector

# Open directly in browser — no build step needed
open index.html
```

To run with your own Groq API key, update the Cloudflare Worker with your key at [console.groq.com](https://console.groq.com).

---

## Product Vision

This prototype demonstrates one possible direction for Trinka's roadmap:

```
Current Trinka          →     Research Gap Detector adds
─────────────────────         ──────────────────────────
Grammar correction            Gap identification
Tone improvement              Citation mapping  
Consistency checks            Open question generation
Style guide adherence         Novelty scoring
                              Pre-writing intelligence
```

The goal: reduce cognitive load at the **discovery** phase, not just the writing phase.

---

## Built by

**Shanit Nagre** — Senior Product Manager, IIT Jodhpur  
[Portfolio](https://shanitnagre.github.io) · [LinkedIn](https://www.linkedin.com/in/shanit-nagre-b1060917b) · [Email](mailto:shanitnagre@gmail.com)

---

*Prototype built to demonstrate product thinking for Trinka AI × Crimson Interactive.*
