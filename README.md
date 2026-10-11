# System Engineering Course

Interactive study course for systems engineering, built around an EV Battery Management System (BMS) capstone and aimed at INCOSE exam preparation.

**Not affiliated with or endorsed by INCOSE, NASA, or ISO.** This is a study aid only — not an exam bank, certification, safety case, or production design.

## Get started

Open **`index.html`** in a browser. It works offline straight from the file, or serve the folder:

```sh
python3 -m http.server
```

Progress, quiz scores, and filled forms are saved in your browser (`localStorage`).

## What's inside

- **18 modules** · 72 topics · 90 practice questions with explanations
- **Capstone:** EV BMS project + 4 transfer projects (C1–C4)
- **Final clearing exam:** random 50-question sample, 80% pass mark
- **19 artifact templates** (requirements, risk, trade study, ConOps, …) — autosaved, printable
- **Document suite:** 7 forms (SEMP, STP, CONOPS, SRD, ICD, …) — fillable, printable
- **Built-in EPUB reader** for the INCOSE handbook (5th ed.) and *Thinking in Systems*
- Light/dark themes

## Course map

0. Orientation — 1. Systems thinking — 2. Life-cycle concepts — 3. Mission analysis, stakeholders, ConOps — 4. Stakeholder needs & requirements — 5. Architecture & design definition — 6. Interfaces & configuration items — 7. Systems analysis & trade studies — 8. Technical planning & measurement — 9. Risk, failure analysis & technical performance — 10. Implementation, integration & transition — 11. Verification, validation & acceptance — 12. Operation, maintenance & retirement — 13. Quality characteristics & specialty engineering — 14. Requirements, configuration & information management — 15. MBSE & digital engineering — 16. Acquisition & organizational enabling — 17. Case studies & exam study

## Files

| File / folder | Purpose |
|---|---|
| `index_2.html` | The course app |
| `chapters/` | Lesson content (`m00.js`–`m17.js`) + `meta.js` (capstone, tools, exam) |
| `assets/` | Handbook EPUBs + reference document-suite page |
| `index.html` | Earlier 5-module version, kept for reference |
| `curriculum.md` | The 18-module curriculum spec |

## Notes

- The EPUB auto-load only works when served over HTTP(S); opening the file directly (or on GitHub Pages from the repo) requires picking the EPUB manually.
- Verify current INCOSE eligibility, handbook edition, and exam format with INCOSE before scheduling.
