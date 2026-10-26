# Baseline VCI Readiness Assessment (v2)

Web app for the Baseline Awareness *Violent Critical Incident Readiness Assessment*, rubric v2.

- **Two scores, never averaged:** School Readiness (S1–S10, what the school controls) and Public Safety Readiness (P1–P7, scored with police, fire, EMS and dispatch)
- Each sub-item rated 0–10 against anchors at 0, 5 and 10
- Evidence multipliers: Verified 1.0, Documented 0.9, Self-reported 0.8
- Caps for disqualifying conditions (domain or sub-item maximums)
- Readiness bands: 0–39 Critical gaps, 40–59 Developing, 60–79 Established, 80–100 Advanced
- Comments box under every sub-item (included in the PDF and copied summary)
- About panel (header button) listing the sources the rubric is based on; also printed as the last page of the PDF
- Observation notes per domain; saved assessments in the browser; duplicate, delete
- PDF report export (top toolbar and bottom of the assessment), copy summary, JSON export/import, print
- Brand intro video on first load (`assets/intro.mp4`)

No build step. Open `index.html` in a browser, or host the folder on any static host.

The rubric content (domains, weights, anchors, caps) lives in the `DOMAINS` array in `index.html`. Time and percentage thresholds are proposals still under discussion.

v1 assessments (11-category form) are stored under a different browser key and are not loaded by v2.
