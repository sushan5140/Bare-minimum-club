# Bare Minimum Club

A tiny, distraction-first corner of the internet for rough days.

## Core idea

Bare Minimum Club is **not** a period tracker, productivity app, or wellness lecture.

The experience starts with one question:

> rough day? pick what your brain can tolerate.

Then it routes into tiny 30-second to 3-minute interactions:

- rage / smash mode
- soft comfort mode
- no-thoughts mode
- emergency distraction mode
- bare-minimum mode
- leave-me-alone-nicely mode

## Product direction

The locked hybrid model is:

1. **Distraction first**
2. **Personal comfort second**
3. **Friend / sibling / partner helper third**
4. **Period-specific context stays optional**

Planned layers:

- personal packs: inside jokes, photos, notes, voice messages
- "Her Settings": what helps, what annoys, what not to say
- helper missions for friends / siblings / partners
- optional "monthly boss battle" flavor
- more mini-games and low-effort interactions

## Batch 1 work branch

Development branch: `feature/bmc-batch-1`

Implemented without deploying:
- **Bare Minimum Button** — simplified to three human battery states with intentionally tiny randomized tasks
- **Regret Button** — simplified to one human verdict + one next-step response; fake percentage dashboard removed

Current product focus:
- **Core:** Bare Minimum Button, Regret Button, Character Development Tracker, One More Person × You Had To Be There
- **Later:** Lorekeeper
- **Dropped from BMC:** Random Cousin, Parallel Universe Group Chat, Bro Hold This

### Batch 2: Character Development Tracker

Development branch: `feature/bmc-batch-2-character-development`

Implemented:
- one-sentence moment logging
- five lightweight arc types
- playful "character development detected" responses
- local-only history using browser storage
- a tiny season summary based on recurring arc
- no streaks, points, XP, or productivity pressure

### Batch 3: One More Person × You Had To Be There

Development branch: `feature/bmc-batch-3-one-more-person`

Implemented:
- quiet-presence modes instead of a chatbot
- "sit here / fake study / keep me company / say something dumb" companion states
- a tiny memory drawer for low-stakes moments
- random resurfacing of older moments
- local-only browser storage
- no feeds, likes, followers, or social pressure

### Batch 4: Lorekeeper — second brain

Development branch: `feature/bmc-batch-4-lorekeeper`

Implemented:
- a lightweight "remember this" capture flow
- four memory buckets: Me, People, Life, Maybe a Pattern
- random gentle resurfacing of stored memories
- cautious wording for patterns ("could be coincidence")
- local-only browser storage for the MVP
- no folders, dashboards, or clinical-style profiling

The long-term direction is **remember → connect → resurface at the right moment**.

The default `main` branch remains untouched until review.

## v0.1

Current prototype is intentionally lightweight and static:

- responsive single-page interface
- six mood entry points
- tiny interactive cards
- early smash / bubbles / note / chaos / comfort interactions
- no login
- no tracking
- no medical claims

## Principle

> no fixing. just surviving the vibe.


## Design system

The current main branch uses a 2026 soft-tactile BMC design direction:
- asymmetric bento hierarchy
- restrained glass surfaces
- low-stimulus pastel color blocks
- bottom-sheet interactions
- thumb-friendly floating navigation
- purposeful micro-interactions

GitHub Pages deployment is configured through `.github/workflows/pages.yml`.


## BMC V2 — mobile application architecture

Development branch: `v2/mobile-app-shell`

V1 remains unchanged on the current root deployment.

V2 is being built separately under `/v2/` as a focused four-tab personal app:
- **Today** — quick emotional check-in + Bare Minimum + Regret
- **Care** — low-effort comfort tools, optional monthly context, quiet company
- **Memory** — Lorekeeper second brain + tiny memories
- **Me** — Character Development and personal receipts

Design research direction:
- fast home actions and separated deeper views from modern fitness apps
- strong bottom navigation and focused tracking flows from cycle/women's-health apps
- low-friction mood/reflection patterns from journaling and self-care apps
- no overloaded dashboard and no long scrolling marketing page

V2 is not deployed as the main experience yet.
