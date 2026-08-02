# CasterlyGit

I build practical developer tools, backend control planes, and local-first
systems where automation stays observable and reviewable.

This profile highlights work across three connected engineering lanes:

| Lane | What I explore | Selected evidence |
| --- | --- | --- |
| Applied AI and developer tools | Human-in-the-loop workflows, context retrieval, and reviewable agent behavior | [Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os), [Shed](https://github.com/CasterlyGit/shed), [agent-harness](https://github.com/CasterlyGit/agent-harness) |
| Backend and platform | Typed state, explicit permissions, dependency-aware planning, and operational guardrails | [Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os), [Trident](https://github.com/CasterlyGit/trident), [emergency-ai](https://github.com/CasterlyGit/emergency-ai) |
| Systems, desktop, and AI-adjacent interaction | Local-first desktop interaction, voice input, and systems-aware tooling | [Curby](https://github.com/CasterlyGit/curby), [Trident](https://github.com/CasterlyGit/trident), [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) |

## Selected work

### Applied AI and developer tools

- **[Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os)** — actively being built as a local-first control plane for turning conversational intent into dependency-aware, reviewable work. Its current implementation is an early dry-run prototype with no network calls, background services, integrations, or authority to merge or deploy.
- **[Shed](https://github.com/CasterlyGit/shed)** — a developer-tool hook layer that retrieves locally indexed context before a prompt and queues proposed memory changes for human review.
- **[agent-harness](https://github.com/CasterlyGit/agent-harness)** — a local workflow harness that connects structured task files to GitHub issues, reviewable pull requests, and visible human review.

### Backend and platform systems

- **[Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os)** — public work on typed intent records, explicit confirmation boundaries, and a restart-safe dependency/conflict graph.
- **[Trident](https://github.com/CasterlyGit/trident)** — a control layer for AI coding-agent routing that separates budget policy from verification and correctness boundaries.
- **[emergency-ai](https://github.com/CasterlyGit/emergency-ai)** — a FastAPI-based service for jurisdiction-aware emergency guidance, with its architecture and operational dependencies documented in the repository.

### Systems and local interaction

- **[Curby](https://github.com/CasterlyGit/curby)** — a macOS voice-driven desktop companion that supports spoken questions and sandboxed coding-agent tasks.
- **[laptop-dictation](https://github.com/CasterlyGit/laptop-dictation)** — local push-to-talk dictation built around Whisper.cpp for macOS, with Linux documented as best-effort.
- **[Ledge](https://github.com/CasterlyGit/ledge)** — a native macOS screenshot shelf built with AppKit.

## How I work

I prefer small, inspectable changes with explicit boundaries:

- Public claims should be traceable to source, tests, or reproducible documentation.
- Automation should preserve a human decision point for consequential work.
- Each repository documents its own current status and limitations; active work is not presented as finished product.

The public positioning roadmap, active program map, and contribution workflow
live in [docs/ROADMAP.md](docs/ROADMAP.md) and
[docs/PROGRAM.md](docs/PROGRAM.md). The curated project hub is
[casterlygit.github.io](https://casterlygit.github.io/).
