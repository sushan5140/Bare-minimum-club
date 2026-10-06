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
- **Later:** Bro Hold This, Lorekeeper
- **Dropped from BMC core:** Random Cousin, Parallel Universe Group Chat

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
