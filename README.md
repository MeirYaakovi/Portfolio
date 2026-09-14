# תיק עבודות — Meir Yaakovi Project Portfolio

QA & Automation Engineer who builds the tools their own testing work needs — Jira/TestRail sync, report generation, evidence processing, and full-stack apps. Most of these live in private repos; this page collects real screenshots, architecture, and write-ups for each one in a single place.

**Contact:** [LinkedIn](https://www.linkedin.com/in/meir-yaakovi) · Live QA portfolio: [meiryaakovi.github.io/MY-QA](https://meiryaakovi.github.io/MY-QA/)

---

## Projects

| Project | What it does | Stack | Code |
|---|---|---|---|
| [STDimport](projects/stdimport) | Syncs a QA results spreadsheet with Jira + TestRail in both directions — creates/updates/closes bugs, upserts test cases, uploads evidence | Python, PySide6, Jira/TestRail REST APIs | Private — samples here |
| [STR Builder](projects/strbuilder) | Generates a full Software Test Report (.docx) from a results spreadsheet + a live Jira pull — charts, color-coded tables, per-defect pages | Python, PySide6, python-docx, matplotlib | Private — samples here |
| [QA Evidence Auto-Watermark](projects/qa-evidence-watermark) | Stamps bug screenshots/videos with metadata (ID, severity, summary) pulled automatically from the results spreadsheet | Python, CustomTkinter, MoviePy | [Public repo](https://github.com/MeirYaakovi/QA-Evidence-Auto-Watermark) |
| [ClAuSy](projects/clausy) | Desktop UI to manage which folders Claude Code / Claude Desktop are allowed to access, without hand-editing JSON | Python, Tkinter | [Public repo](https://github.com/MeirYaakovi/ClAuSy) |
| [BugRange](projects/bugrange) | A manual-QA training simulator — five small apps seeded with real bugs, a timer, a bug-report panel, and a scored results breakdown at the end | React, Flask, SQLAlchemy | Private — samples here |
| [HealthTracker](projects/healthtracker) | Full-stack nutrition/fitness tracker — meal photo & voice logging via Claude, macro targets, an AI coaching chat | React, TypeScript, FastAPI, Claude API | Private — samples here |
| [MyMentor](projects/mymentor) | A daily AI interview-prep coach, driven from a Claude Code skill, that tracks technique coverage and progress over time | Node.js, SQLite/Turso | Private — samples here |

---

## Notes

- Projects marked **Private** have their source kept out of this repo (client-related data, credentials scaffolding, or just not cleaned up for a public read) — each folder here has a real README, screenshots, and an architecture diagram instead of the code itself.
- No credentials, client names, or proprietary data appear anywhere in this repo.
