## hi — I build small, agentic tools.

→ **[casterlygit.github.io](https://casterlygit.github.io/)** for the curated tour with live demos.

Mostly macOS. Mostly Python and TypeScript. Some Three.js. Mostly AI-augmented dev workflows where one engineer ships at team pace. Each project here ships v0.1 in days — and has a live demo so you don't need to read code to see what it does.

---

### 🐉 Spotlight — playable browser game

#### [realm](https://github.com/CasterlyGit/realm) — dragon-flight combat
Pick one of four distinct dragon archetypes — Crimson King, Sky River, Jade Serpent, Frostbloom — and clear three waves of aerial combat. Three.js, procedural geometry, no asset downloads. Custom shader fire breath, ~700 instanced trees, per-archetype animation.
**→ [play it now](https://casterlygit.github.io/realm/)**

---

### 🌟 Featured — the voice / gesture / agent stack

Three tools, one story: speak a task, gesture to confirm, watch an autonomous Claude Code agent run it.

#### 🎙 [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) — voice in
Hold a hotkey, talk, release. Whisper transcribes locally, pastes into the focused app, presses Enter. True voice interface for Claude Code.
**→ [live demo](https://casterlygit.github.io/laptop-dictation/)**

#### ✋ [hand-signal](https://github.com/CasterlyGit/hand-signal) — gesture in
`handsignal ask "approve?"` pops a focused window. 👍 approves, 👎 denies, ✊ hands control back to you. MediaPipe Hands, all local.
**→ [live demo](https://casterlygit.github.io/hand-signal/)**

#### 🤖 [curby](https://github.com/CasterlyGit/curby) — agent dispatcher
Voice task → autonomous Claude Code agent runs it in a sandbox. Each task gets a neon-cursor puck on the screen edge with live status and pause / cancel / amend controls.
**→ [live demo](https://casterlygit.github.io/curby/)**

#### 🧠 [shed](https://github.com/CasterlyGit/shed) — memory in
Silent shadow layer for Claude Code. Picks the 2-3 most relevant notes from your past and prepends them to every prompt. Watches for corrections, queues them for one-key approval the next morning. Local embeddings, local-only by default.
**→ [live demo](https://casterlygit.github.io/shed/)**

*currently exploring: a unified approver across the stack — when any Claude Code session needs input, attention routes to it and voice or gesture resolves the prompt.*

---

### Also shipped

#### [claude-meter](https://github.com/CasterlyGit/claude-meter) — live token-usage dashboard
Always-on-top widget. Two concentric rings — 5-hour outside, weekly inside. Every visual property encodes information: hue, thickness, pace tick, comet tail, dashed overflow, wall-clock reset times. Collapses to a circular pillar that fills bottom-up by % used, refreshes itself every 10 minutes.
→ [live demo](https://casterlygit.github.io/claude-meter/)

#### [emergency-ai](https://github.com/CasterlyGit/emergency-ai) — multi-tenant emergency response API
RAG + Redis + Postgres + Prometheus, sub-2s at 50 concurrent users. API key auth, rate limiting, pgvector statute retrieval. v0.2 — now a real deployed service.
→ [live demo](https://casterlygit.github.io/emergency-ai/)

#### [neon-stereo](https://github.com/CasterlyGit/neon-stereo) — desktop music client with attitude
Spotify + YouTube Music in one Electron app. Scanline overlays, neon glow, mono readouts — visual identity as a first-class feature.
→ [live demo](https://casterlygit.github.io/neon-stereo/)

#### [agent-harness](https://github.com/CasterlyGit/agent-harness) — the orchestrator behind everything
Skills, pipeline prompts, and inbox watchers that turn ideas into shipped PRs. Obsidian → GitHub issue → branch → PR → merged, with minimal human turns.
→ [live demo](https://casterlygit.github.io/agent-harness/)

#### [neetcode](https://github.com/CasterlyGit/neetcode) — daily DSA grind
Auto-synced solutions with a live stats dashboard. Streak, language breakdown, difficulty mix, recent solves.
→ [live dashboard](https://casterlygit.github.io/neetcode/)

---

### How I work

Each project ships v0.1 in days, not quarters. The pipeline:

> idea → Obsidian note → GitHub issue → `/iterate` → branch → PR → merged → live demo

The harness above is what makes that loop tight. The other projects are real outputs of it.
