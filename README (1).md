# CCNA 200-301 Command Center

An interactive, single-page study companion for the [Free CCNA 200-301 Complete Practical Course](https://www.youtube.com/playlist?list=PLw6kwOJVj3MbMZ8B72ZgUryj8OSETC0ds) by David Bombal.

**[Live site →](https://alphamaxtrix.github.io/CCNA-Study-Guide-/)**

## What's inside

- **Map** — a live network topology diagram of the 6 CCNA exam domains. Nodes light up as you complete topics, and connections between domains "come online" as progress builds.
- **Tracker** — a checklist of ~30 topics grouped by exam domain, each tagged with its exam weight. Progress is saved automatically in your browser.
- **Guide** — expandable cards covering key concepts and a review question for each topic.
- **Flashcards** — 30 flip cards, filterable by domain, with a shuffle option.
- **Quiz** — 20 multiple-choice questions covering all domains, with explanations and a best-score tracker.

## Running it locally

This is a single self-contained HTML file — no build step, no dependencies to install.

1. Clone or download this repo.
2. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.

## Notes

- Progress and quiz scores are saved via `localStorage`, so they're specific to whichever browser/device you use — they won't sync across devices.
- Exam domain weighting and topic coverage follow the official Cisco CCNA 200-301 exam blueprint.
- This is an unofficial study aid, not affiliated with Cisco or David Bombal.
