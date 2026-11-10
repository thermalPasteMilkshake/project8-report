# Project 8 — 12-Slide Presentation Deck (outline)

Build in Google Slides. One section per slide; speaker notes carry the business
rationale. Target walkthrough length: 4.5–5.5 minutes.

1. **Title** — AI Application Security Assessment, TechCorp Ltd., name, date,
   "Confidential".
2. **Assessment Scope** — what was tested (AI assistant, MCP server, CI/CD,
   DVWA), lab environment, 9 work streams.
3. **Methodology & Tools** — OWASP LLM Top 10, red teaming, MCP pentest,
   DevSecOps gates, web/API pentest, CVSS, compliance.
4. **Overall Risk Posture** — High; headline count: **4 Critical / 6 High / 2 Medium** (12 findings).
5. **Key Findings — AI Layer** — secrets in prompt (F-03), prompt injection
   (F-04).
6. **Key Findings — MCP Layer** — command execution (F-08), path traversal
   (F-09), resource poisoning (F-10).
7. **Key Findings — Web Layer** — SQLi + auth bypass (F-01/F-02), XSS (F-06).
8. **Key Findings — DevSecOps** — no security gates (F-11), vulnerable deps (F-12).
9. **MITRE ATLAS Mapping** — ≥6 technique IDs mapped to AI/LLM findings.
10. **Risk Priority Matrix** — all 12 findings ordered by CVSS high→low; use the
    table in `ASSESSMENT_REPORT.md` Section j (F-01 9.8 → F-07 5.3).
11. **Top 5 Recommendations** — effort estimate + business rationale; use
    `ASSESSMENT_REPORT.md` Section k (rotate secrets; parameterise SQL; lock down
    MCP tools; enable CI/CD gates; AI input/output defence).
12. **Remediation Roadmap & Close** — 90-day 3-phase plan, re-test offer,
    confidence statement.

## Self-review before recording
Confirm every finding has supporting evidence, every risk has a recommendation,
and Slide 10's matrix is ordered correctly by CVSS score (highest first).
