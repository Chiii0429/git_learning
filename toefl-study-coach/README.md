# TOEFL Study Coach · 6.0 Target

An independent, privacy-conscious TOEFL iBT 2026 study dashboard.

## Goal

**Overall TOEFL iBT 6.0 (CEFR C2)**, aiming for **6.0 in each section**. The 2026 scale is **1–6**, in 0.5 increments. A 6.0 total is a target, not an estimated achievement.

## Run

Open `index.html` in a browser. For microphone access, use an HTTPS origin or localhost, e.g. `python3 -m http.server 8000` and open http://localhost:8000/toefl-study-coach/ from the parent repository.

No npm install, cloud account, API key, backend, or third-party script is required.

## Features

- Six original Reading & Listening mini-diagnostic items with explanations
- Browser text-to-speech for sample Listening prompts (synthetic speech; not ETS-standardized listening)
- Writing prompts and browser-local response journal
- Speaking prompt with optional microphone recording for immediate playback (session-only)
- Local practice history, JSON export, and deletion
- Optional local birthdate and study schedule
- Academic extension topics in neuroscience, biomedicine, and engineering
- Mobile-friendly layout with keyboard focus indicators

## Explicit limits

- **Unofficial practice only.** Mini-quizzes do not measure or predict TOEFL section scores.
- The app does not implement official multistage adaptive testing or calibrated scoring.
- Writing and Speaking have no automated scoring.
- Speech synthesis is not equivalent to the official Listening audio conditions.
- Browser localStorage is device-specific and can be deleted by the browser.
- The personal birthdate is **not committed** to a public GitHub repository.
- Bazi is optional cultural reflection; no claim that it predicts cognitive ability.

## 2026 task alignment

| Section | ETS task types |
| --- | --- |
| Reading | Complete the Words; Read in Daily Life; Read an Academic Passage |
| Listening | Listen and Choose a Response; Listen to a Conversation; Listen to an Announcement; Listen to an Academic Talk |
| Writing | Build a Sentence; Write an Email; Write for an Academic Discussion |
| Speaking | Listen and Repeat; Take an Interview |

See [ETS test content](https://www.ets.org/toefl/test-takers/ibt/about/content.html) and [ETS score explanation](https://www.ets.org/toefl/test-takers/ibt/scores/understand-scores.html).

TOEFL is a trademark of ETS. This project is independent and is not affiliated with ETS.

## Development roadmap

1. Add vetted practice banks for all 12 official task types
2. Build audio test fixtures and Speaking self-review rubrics
3. Add spaced repetition with per-concept mastery statistics
4. Add standardized diagnostic tools with known validity limits
5. Support offline import and multi-device synchronization with explicit opt-in
