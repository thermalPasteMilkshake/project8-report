# Project 8 — Self-Review Checklist (Deliverable 3)

**Author:** Abhinav Prajapati · **Date:** 2026-11-09
Status against the produced report (`ASSESSMENT_REPORT.md`).
**Y** = satisfied in the report · **PENDING** = needs your live action (build the
Google Slides deck, record the walkthrough).

| # | Standard | Confirmed |
|---|----------|-----------|
| 1 | Cover page has name, title, date, classification label | **Y** (Section a) |
| 2 | Executive summary ≤200 words and jargon-free | **Y** (Section b, ~165 words) |
| 3 | Scope & methodology lists every tool used | **Y** (Section c) |
| 4 | Master findings table has unique IDs (F-01…F-12) | **Y** (Section d) |
| 5 | Every finding attributed to its source project | **Y** (Section d) |
| 6 | Every finding has a CVSS score + full vector string | **Y** — all 12 vectors inline (Section e) |
| 7 | One detailed page per finding with evidence | **Y** — all 12 inline with live evidence (Section e) |
| 8 | Every risk has a specific, step-by-step remediation | **Y** (Section e) + roadmap (P7) |
| 9 | MITRE ATLAS section has ≥6 technique IDs | **Y** — 7 techniques (Section f) |
| 10 | Each ATLAS ID verified on atlas.mitre.org | **Y** — verified against ATLAS 2026.08; T0053 updated to "AI Agent Tool Invocation", T0040 to "AI Model Inference API Access" |
| 11 | Compliance traffic-light table imported from Project 7 | **Y** (Section g — ASVS 56% Red, NIST 60% Red, EU 67% Amber) |
| 12 | Appendices include raw tool outputs | **Y** (Section h — Nmap, Dirb, Nikto, DVWA, MCP, gates, ZAP) |
| 13 | Risk Priority Matrix ordered by CVSS (highest first) | **Y in report** (Section j) — build Slide 10 from it; order is authoritative |
| 14 | Recommendations include effort + business rationale | **Y in report** (Section k) — build Slide 11 from it |
| 15 | Walkthrough recording is 4.5–5.5 minutes | **PENDING** (record with OBS/Loom from `SLIDE_DECK.md`) |
| 16 | Critical/High counts in summary match findings table | **Y** — 4 Critical / 6 High / 2 Medium = 12 |

**Severity tally (live-confirmed):** 4 Critical — F-01 SQLi, F-02 auth bypass,
F-03 secrets-in-prompt, F-08 MCP RCE · 6 High — F-04, F-05, F-09, F-10, F-11,
F-12 · 2 Medium — F-06 XSS, F-07 headers.

**Outstanding (your live steps):** build the 12-slide Google Slides deck from
`SLIDE_DECK.md` (Slides 10 and 11 come directly from report Sections j and k),
then record the 4.5–5.5-minute walkthrough.
