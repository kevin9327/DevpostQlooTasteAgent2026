# Devpost — `Qloo Agentic Hackathon: Agents, but with taste.` Submission Package (`$25,000 USD` Cash + `$25,000 USD` Bonus Investment)

![Banner](banner.png)

## 1. Competition Overview & Live Cash Verification
- **Hackathon:** `Qloo Agentic Hackathon: Agents, but with taste.`
- **Official Portal:** `https://qloo.devpost.com/`
- **Deadline:** **October 30, 2026 @ 11:45pm EDT**
- **Cash Prize Pool:** **`$25,000 USD in Cash`** (`1st Place: $15,000 Cash`, `2nd Place: $6,000 Cash`, `3rd Place: $4,000 Cash`) **+ `$25,000 USD` Jason Calacanis Bonus Investment (`$50,000` Total Pool)**
- **Eligibility:** Open globally to all adults (`Above legal age of majority in country of residence. All countries/territories, excluding standard exceptions`).
- **No Demo Video Required:** Per the official Devpost rules: *"NOTE: Demo videos are not required. Instead of asking for a recording, we're requiring something judges can actually use."*

---

## 2. Official Qloo Hackathon API Integration (`https://hackathon.api.qloo.com`)
Per the [Qloo Agentic Hackathon Developer Guide](https://docs.qloo.com/reference/qloo-llm-hackathon-developer-guide), `QlooTasteWeaver` targets the dedicated hackathon gateway **`https://hackathon.api.qloo.com`** using `/v2/insights`, `/search`, `/entities`, and `/analysis/compare` (and strictly blocks legacy `/recommendations` and `/recs` endpoints).

### 3 Lateral Cultural-Intelligence Workflows Implemented
1. **Senior Medication-Aware & Texture-Safe Culinary Concierge (`urn:entity:place`):**
   - Grounds senior dining and meal delivery in personal cultural nostalgia (e.g., Bill Evans jazz, mid-century cinema) while enforcing **IDDSI Level 6 soft-bite texture**, **low sodium (`< 480 mg`)**, and **CYP3A4 / Warfarin clinical interaction guardrails**.
2. **Electrician & Architectural Room-Mood Lighting Taste Designer (`urn:entity:brand`):**
   - Translates a homeowner's film, music, and aesthetic affinities into concrete electrical engineering specifications (**Kelvin CCT `2400K–2700K`**, **CRI `97` / `R9 = 94`**, **DALI-2 Warm-Dim curves**, **UGR `< 14.5` glare bounds**, and matched fixture brands).
3. **Rare-Disease Empathetic Community, Podcast & Literature Navigator (`urn:entity:podcast`, `urn:entity:book`):**
   - Pairs patients and caregivers on rare-disease journeys with culturally aligned science-storytelling podcasts, memoirs, and clinical-trial preparation checklists.

---

## 3. Package Files & Deterministic Verification (`exit code 0`)
- [`qloo_taste_agent.py`](qloo_taste_agent.py) — Official `https://hackathon.api.qloo.com/v2/insights` agent engine & verifier (`exit code 0`).
- [`qloo_taste_verification_report.json`](qloo_taste_verification_report.json) — Machine-verifiable JSON report (`SHA-256: 4e6770c37eaae4b95691a2b67139d2ddf1acffee201f5424e506391d776451e7`).
- [`index.html`](index.html) — Live interactive web application for judges.
- [`LICENSE`](LICENSE) — Open-source MIT License (required by submission checklist item #5).
- [`banner.png`](banner.png) — `1200x630` submission banner.

```bash
python DevpostQlooTasteAgent2026/qloo_taste_agent.py
```
