# Garey Auto Repair — Brief

- Business name: Garey Auto Repair
- City: Pomona, CA
- Address: 2580 N Garey Ave, Pomona, CA 91767
- Phone: (909) 392-6056
- Owner(s): **Josh + Brian** — two on-floor mechanics buying the shop from current owner (Areal De La Rosa). Both younger.
- Founded: 2006 (20 years on Garey Ave)
- Status: in-progress
- Vercel URL: garey-auto-repair.vercel.app *(to deploy)*
- GitHub repo: github.com/donna-ui/demo-garey-auto-repair *(to create)*
- Hours: Tue–Fri 8a–5p · Sat 8a–2p

## The strategic problem
Shares 2580 N Garey Ave with **Garey's Smog / Garey Test Only**. Bad reviews from the smog operation bleed across when customers Google "Garey." The site has to act as a reputation firewall — establish Garey **Auto Repair** as its own operation with its own scope and standard.

**Tactics (no shade, no naming the smog shop):**
- Always full name: "GAREY AUTO REPAIR" — never "Garey's"
- Site is **about the shop**, not the people. Josh + Brian named only as a small "under new hands" credit in the hero ID strip + footer. Not a section. Not a bio. (Donna pivot 2026-04-25.)
- "How we work" 5-step process module replaces the original "Hands" section — shop-process trust, not personality trust.
- Scope panel ("What lives here") names what they do — silence on what they don't.
- LocalBusiness schema with precise legal name + this exact URL
- Reviews labeled `@ GAREY AUTO REPAIR · YELP` — quiet disambiguation, no person-named pulls

## Creative direction
- **Aesthetic:** Garey OS — a 20-year shop running 2026 software. Live operating system aesthetic, telemetry dashboard chrome, warm humans inside the panels.
- **Signature moment:** **The Translator** — interactive symptom chips → mono-typed diagnostic translation. Proves the AI promise without saying "AI."
- **Color palette:** `#0B0E14` deep graphite / `#151A24` panel / `#E8EBF0` pearl / **`#C5FF00` arc-flash chartreuse** / `#FFB845` warm amber (human moments only)
- **Typography:** Space Grotesk display + body · JetBrains Mono data layer · Fraunces *upright* 900 for ONE pull-quote (warmth, no italic-serif default)

## Voice
- **Operational drumbeat:** "The light is a sentence. We translate."
- **Brand-identity line:** "Under new hands."
- Tone: kinetic, mechanical, dryly warm, never corporate. Real Yelp language folded in ("never upsells").
- Bilingual?: no

## Default-pattern audit (per `feedback_break_patterns.md`)
- ✅ No top-right phone (phone is a typographic moment in contact section only)
- ✅ No italic-serif display (Space Grotesk + JetBrains Mono; Fraunces upright only)
- ✅ No grain overlay (scanline + grid as OS texture instead)
- ✅ No dark + brass/gold (graphite + arc-flash chartreuse + amber)
- ✅ No map with city dots (no service-area map at all)
- ⚠️ Mono caps used as legitimate UI labels (MOD.01, STATUS) — load-bearing for OS conceit
- ✅ No three-column stats ribbon (single embedded "20" + Yelp count in copy)
- ✅ No chapter numbers (i./ii./iii.) — module IDs (MOD.01..07) belong to the metaphor

## What we've learned
- Owner Areal originally voiced "we are in the future" — DO NOT put that line on the site (per Donna). Site embodies it; copy never states it.
- Translator demo data is preset/canned (4 symptom chips → 4 hardcoded responses). No real LLM call on the demo.

## Status log
- 2026-04-25: kickoff — research, BRIEF, plan approved, build started
- 2026-04-25: pivot — Donna pulled focus off Josh + Brian. Site is about the shop. "Hands" section replaced with 5-step "How we work" process module. Personal references scrubbed from telemetry, receipts, contact, reviews.
