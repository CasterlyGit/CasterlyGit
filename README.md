## hi — I build small, agentic tools.

> **Recruiter / first-time visitor?** → **[casterlygit.github.io](https://casterlygit.github.io/)** is the curated tour.

Mostly macOS. Mostly Python and TypeScript. Mostly AI-augmented dev workflows where one engineer ships at team pace. Live, interactive demos for everything below — no need to read code.

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

---

### Also shipped

#### [emergency-ai](https://github.com/CasterlyGit/emergency-ai) — sub-2-second jurisdiction-aware responses
Long-press SOS → action steps grounded in your city's actual laws. Haiku 4.5 + prompt caching + streaming structured output.
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
