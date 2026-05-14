## I build small, agentic tools.

Mostly macOS. Mostly Python and TypeScript. Mostly AI-augmented dev workflows where one engineer ships at team pace.

Live, interactive demos for everything below — no need to read code.

---

### Currently shipping

#### [curby](https://github.com/CasterlyGit/curby) — voice-driven desktop agent dispatcher
Hold a hotkey, speak a task, watch an autonomous Claude Code agent run it in a sandbox. Each task gets a neon-cursor puck on the screen edge with live status and pause / cancel / amend controls.
→ [live demo](https://casterlygit.github.io/curby/)

#### [emergency-ai](https://github.com/CasterlyGit/emergency-ai) — sub-2-second jurisdiction-aware responses
Long-press SOS → action steps grounded in your city's actual laws. Haiku 4.5 + prompt caching + streaming structured output.
→ [live demo](https://casterlygit.github.io/emergency-ai/)

#### [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) — push-to-talk Whisper
Hold a hotkey, speak, text appears in your clipboard — and as of v0.2, **auto-pastes + presses Enter** so it's a true voice interface for Claude Code. Local Whisper.cpp, no cloud roundtrip.
→ [live demo](https://casterlygit.github.io/laptop-dictation/)

#### [hand-signal](https://github.com/CasterlyGit/hand-signal) — webcam gesture confirmations
`handsignal ask "Approve this?"` pops a focused, always-on-top window. 👍 approves, 👎 denies, ✊ "I'll do it." MediaPipe Hands + a tiny pure-geometry classifier, all local. Designed for hands-free Claude Code prompts; safe-mode advisory by default. Third modality alongside voice + agents.
→ [live demo](https://casterlygit.github.io/hand-signal/)

#### [neon-stereo](https://github.com/CasterlyGit/neon-stereo) — desktop music client with attitude
Spotify + YouTube Music in one Electron app. Scanline overlays, neon glow, mono readouts — visual identity treated as a first-class feature.
→ [live demo](https://casterlygit.github.io/neon-stereo/)

#### [agent-harness](https://github.com/CasterlyGit/agent-harness) — the orchestrator behind all of the above
Skills, pipeline prompts, and inbox watchers that turn ideas into shipped PRs. Obsidian → GitHub issue → branch → PR → merged, with minimal human turns.
→ [live demo](https://casterlygit.github.io/agent-harness/)

#### [neetcode](https://github.com/CasterlyGit/neetcode) — daily DSA grind
Auto-synced solutions with a live stats dashboard. Streak, language breakdown, difficulty mix, recent solves.
→ [live dashboard](https://casterlygit.github.io/neetcode/)

---

### How I work

Each project ships v0.1 in days, not quarters. The pipeline:

> idea → Obsidian note → GitHub issue → `/iterate` → branch → PR → merged

The harness above is what makes that loop tight. The other projects are real outputs of it.
