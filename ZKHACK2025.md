# 🚀 Hackathon Guide & Idea Validation Template

*Copy this markdown into Notion, Obsidian, or your repo and fill in the blanks.*

---

## 🔖 TL;DR
- **Pick a hard, user‑visible problem** that matches the host’s theme.
- **Score every idea** (impact × judge fit × difficulty × feasibility) before committing.
- **Plan hour‑by‑hour**, then demo with a clear story—no random pivots.

---

## 0️⃣  Context Snapshot  *(≈30 min)*
- **Hackathon name & dates:** `ZKHACK 2025 20 - 22 JUNE (48 Hours)`
- **Hosts / sponsors:** `ZKHACK`
- **Judging criteria (weight %)**: `JUDGES.md & CRITERIA.md`
- **Mandatory tech / bounties:** `TECH_BOUNTY.md`
- **Team strengths & gaps:** `<fill>`

---

## 1️⃣  Problem Hunt  *(≈60 min)*
Brain‑dump 5–8 problems that align with the host or judges. Prioritize end‑user pain points.

| #  | Working Title                          | One‑line Problem Statement                                                             | Why It’s Hard                                                                  | Target Users                           |
|----|----------------------------------------|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|----------------------------------------|
| 1  | ZK Zone Compliance for Rental & Insure | Prove vehicle stayed within authorized area & speed limits, without exposing location   | Requires real-time zk proof generation + resistant to GPS spoofing             | Car rental firms, usage-based insurers |
| 2  | ZK Content Moderation AI               | Enforce platform tone guidelines without storing or seeing raw user messages            | Proving “toxicity” or violations from transformed input is noisy & indirect    | Forums, community platforms            |
| 3  | ZK Remote Work Attendance              | Let employers verify you worked at an approved location without revealing when or where | Time/location aggregation without trace logging or employee surveillance       | Remote-first companies, contractors     |
| 4  | ZK Access Control for Restricted Zones | Prove a user or drone did *not* enter forbidden areas without live tracking             | Negative spatial proof is hard over complex geofences with no GPS retention    | Airports, event venues, drone operators|
| 5  | ZK Fitness Rewards Proof               | Prove gym attendance or movement goals met without GPS leaks or time logs               | Requires interval presence proof, private step counts, tamper-resistant input  | Health apps, wellness programs, gyms   |
| 6  | ZK Delivery Zone Confirmation          | Prove a gig worker delivered *within* allowed zone without leaking customer address     | Need strong location containment proof + protection against false claims       | Delivery apps, courier services         |


> **Tip:** If you can’t name a user persona, it’s not a problem—keep digging.

---

## 2️⃣  Idea Scoring Matrix  *(≈15 min / idea)*
Rate each idea **1 = low → 5 = high**, multiply by weight.


| Idea                                     | User Impact (×3) | Judge Fit (×2) | Tech Difficulty (×2) | Feasible ≤48 h (×1) | Total | Grade |
|------------------------------------------|------------------|----------------|----------------------|---------------------|--------|--------|
| ZK Zone Compliance for Rental & Insure   | 3×3 = 9         | 4×2 = 8        | 4×2 = 8              | 3×1 = 3             | **25** | B      |
| ZK Content Moderation AI                 | 3×3 = 9          | 5×2 = 10       | 4×2 = 8              | 2×1 = 2             | **29** | B+     |
| ZK Remote Work Attendance                | 4×3 = 12         | 5×2 = 10       | 3×2 = 6              | 4×1 = 4             | **32** | A-      |
| ZK Access Control for Restricted Zones   | 3×3 = 9         | 4×2 = 8        | 5×2 = 10             | 2×1 = 2             | **29** | B+     |
| ZK Fitness Rewards Proof                 | 5×3 = 15         | 4×2 = 8        | 3×2 = 6              | 4×1 = 4             | **33** | A      |
| ZK Delivery Zone Confirmation            | 5×3 = 15         | 4×2 = 8        | 4×2 = 8              | 4×1 = 4             | **35** | A      |

- **Tier Definition**
  - **S (>38)** — green‑light
  - **A (32‑38)** — strong
  - **B (26‑31)** — backup
  - **C (<26)** — park

---

## 3️⃣  Pick the Winner
- **Primary idea:** `<fill>`
- **Plan B (fallback):** `<fill>`

---

## 4️⃣  Spec Blueprint  *(≈1 h)*
- **Problem statement:** `<fill>`
- **Target persona & pain:** `<fill>`
- **Value proposition (1 sentence):** `<fill>`
- **User journey storyboard:** `<sketch / bullets>`
- **Demo‑day success metric:** `<e.g., “approve a loan in 2 clicks”>`

---

## 5️⃣  Technical Architecture  *(≈1 h)*
- **Core stack:** `<frontend / backend / smart contract / ZK / infra>`
- **Key risks & mitigations:**
  - `<risk>` → `<mitigation>`
- **Stretch goals (only if time permits):** `<fill>`

---

## 6️⃣  Rapid Validation  *(same day)*
- [ ] **3 user interviews / Discord polls** — results: `<fill>`
- [ ] **Competitor sweep** — links: `<fill>`
- [ ] **Judge feedback ping** — notes: `<fill>`

---

## 7️⃣  Build Plan  *(Gantt / checklist)*
```
| Time (UTC+7) | Milestone | Owner | Status |
|--------------|-----------|-------|--------|
| T‑48 h       | Repo scaffold & CI          | <name> | ☐ |
| T‑36 h       | MVP backend / contract      | <name> | ☐ |
| T‑24 h       | Front‑end integrates APIs   | <name> | ☐ |
| T‑12 h       | E2E demo works              | <name> | ☐ |
| T‑6 h        | Polish, bug bash, slides    | All    | ☐ |
| T‑0 h        | Live demo & submission      | <name> | ☐ |
```

---

## 8️⃣  Demo Narrative  *(5 min)*
1. **Hook (15 s)** — show the pain.
2. **Why now (30 s)** — tech or timing unlock.
3. **Live demo (2 min)** — narrate while clicking.
4. **Tech flex (45 s)** — share numbers: proof size, gas cost, TPS.
5. **Impact & roadmap (30 s)** — next steps.

---

## 9️⃣  Fallback Protocol
If blocker hits before **T‑24 h**, switch to Plan B. Reuse as much code as possible.

---

## 🔟  Post‑Hack Viability
- **Path to first 100 users:** `<fill>`
- **Funding / grants:** `<fill>`
- **3‑month roadmap:** `<fill>`

---

> **Reminder:** *Luck = preparation × opportunity.* Keep thinking deliberately.
