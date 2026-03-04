# AI-Agent Outline: Regional Media Watch for War + Post-War Coalition Support (OSINT-Focused)

> **Scope note:** This is a **policy/analysis** design for monitoring **public** information (regional media and open sources) to surface emerging issues and inform **stabilization + coalition-building**. It is **not** a tactical system for targeting or operational violence.

---

## 1) Mission and outputs

### Mission
Continuously monitor public regional information flows to:
- detect **emerging grievances**, **legitimacy shocks**, and **conflict triggers**
- track **narrative shifts** and **mis/disinformation patterns**
- identify **coalition opportunities** (actors, interests, bridging issues)
- support post-war **governance** and **reconciliation** planning with early warnings

### Core outputs
- **Daily brief** (1–2 pages): key events, narrative shifts, top risks, top opportunities  
- **Real-time alerts:** spikes in hate speech, mobilization rhetoric, rumors, protest signals, humanitarian distress signals  
- **Issue maps:** “what people are talking about” by region, group, and language  
- **Coalition opportunity cards:** shared interests + credible intermediaries + likely spoilers  
- **Verification queue:** items needing human validation (high-impact/low-confidence)

---

## 2) Data coverage and intake

### Source categories (public-only)
- National and local **news sites**
- Regional **TV/radio transcripts** (where legally accessible)
- **Wire services**
- Official government / municipal statements
- Civil society / NGO updates
- Public social platforms and forums (within legal/ToS constraints)

### Source management features
- **Source registry** with metadata:
  - geography, language/dialect, ownership/affiliations, historic reliability
  - bias profiles (editorial line), known propaganda links
  - update frequency, typical topics, past retraction rate
- **Collection policies:**
  - prioritize public information; minimize personal data
  - throttle/rotate to respect site terms and avoid disruption
  - track provenance (URL/time/author) for auditability

---

## 3) Language and cultural NLP layer

### Multilingual + dialect handling
- Language ID and dialect routing (e.g., Arabic varieties, Kurdish dialects, Persian, Turkish, minority languages)
- Domain-adapted translation (preserve **named entities** and culturally loaded phrases)
- Cultural lexicons:
  - honorifics, tribal/clan references, sectarian terms
  - idioms signaling threats, mobilization, or reconciliation cues

### Entity and relationship extraction
- **Entity resolution:** people, parties, armed groups, clerics, tribes, NGOs, municipal offices
- **Relationship graph:** alliances, rivalries, patronage ties, mediation channels
- **Geo-grounding:** link mentions to districts, towns, neighborhoods

---

## 4) Event + narrative detection

### Event detection (what happened)
- Clustering across sources to detect emerging events:
  - protests, strikes, checkpoints, border closures
  - humanitarian shortfalls (water, medicine, salary nonpayment)
  - arrests, assassinations, communal violence indicators
  - reconstruction outages (power, schools, hospitals)
- “Same event, many tellings” stitching:
  - merges duplicates
  - highlights discrepancies across outlets

### Narrative detection (how it’s framed)
- Topic modeling: top issues per region/time window
- Frame analysis:
  - scapegoating, grievance, calls for revenge, reconciliation appeals
  - legitimacy claims (“who has the right to rule/represent”)
- **Rumor/misinfo tracking:**
  - early spread detection
  - source propagation graph (who amplified it)
  - “verification needed” flagging

---

## 5) Risk and opportunity scoring

### Risk signals (examples)
- Hate speech spikes; dehumanizing language trends
- “Mobilization verbs” + specific locations (**without** turning into targeting guidance)
- Supply shortages + anger narratives + leadership blame
- Calls for collective punishment or retaliation

### Opportunity signals (examples)
- Shared-need narratives (services, salaries, safety, schools)
- Cross-group sympathy or joint condemnation of violence
- Trusted mediators mentioned across camps (clerics, municipal technocrats, respected NGOs)
- Positive sentiment toward compromise mechanisms (audits, revenue-sharing, local councils)

### Scoring model approach
Combine:
- **frequency change** (spikes)
- **source credibility weighting**
- **cross-source corroboration**
- **historical precursors** (patterns that previously preceded unrest)

Output:
- **risk/opportunity heatmap** by district + actor + issue

---

## 6) Coalition-support module (decision support, not deal-making)

### “Coalition opportunity card” template
- **Issue:** e.g., salary continuity, water access, school reopening
- **Stakeholders:** who benefits, who loses, who can block
- **Credible conveners:** actors with cross-group trust
- **Likely spoilers:** groups that gain from instability
- **Messaging frames:** what each side finds acceptable (values-based translation)
- **Confidence:** high/medium/low + evidence trail

### Coalition “stress tests”
Evaluate resilience under plausible shocks:
- budget cut
- border closure
- external pressure on one party

Questions:
- does the coalition survive?
- what fails first?
- what mitigation mechanisms help? (transparency triggers, third-party monitoring, phased commitments)

---

## 7) Human-in-the-loop and verification

### Analyst controls
- Adjustable thresholds by region and topic
- “Show your work” mode: every claim links to source excerpts and timestamps
- Contradiction viewer:
  - displays diverging accounts side-by-side
- Triage dashboard:
  - high-impact/low-confidence items bubble to the top for human review

### Verification workflow
1. Confirm event existence (≥2 independent sources or trusted single source)
2. Confirm key attributes (where/when/who affected)
3. Label as **confirmed / probable / unconfirmed**
4. Maintain a correction log if later disproven

---

## 8) Safety, ethics, and governance

### Guardrails
- No personal targeting, doxxing, or operational instructions
- Minimize personal data; focus on public figures and public institutions
- Clear separation between:
  - **analysis products** (strategic/operational planning at a governance level)
  - and **tactical military applications** (explicitly out of scope)

### Auditability
- Immutable provenance records
- Model output logging + analyst override tracking
- Bias monitoring: ensure minority outlets aren’t systematically down-weighted

---

## 9) Implementation sketch (systems view)

### Components
1. **Collector** (feeds + site monitors + transcript ingest)
2. **Normalizer** (dedupe, language ID, metadata enrichment)
3. **NLP pipeline** (translation, NER, relation extraction, sentiment/frame)
4. **Event engine** (clustering, timelines, contradiction detection)
5. **Narrative engine** (topic/frame shifts, rumor propagation)
6. **Risk/opportunity scorer** (heatmaps + alerting)
7. **Coalition recommender** (issue cards + stress tests)
8. **Analyst console** (dashboard, verification queue, reporting)
9. **Governance layer** (access control, audit logs, red-team tests)

### Cadence
- Streaming alerts: **minutes**
- Hourly rollups: “what changed”
- Daily brief: “what matters + why”
- Weekly: “structural trends + coalition windows”
