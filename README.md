# CasterlyGit

I build practical developer tools, backend control planes, and local-first
systems where automation stays observable and reviewable.

Six flagship projects carry the main engineering story across three connected
lanes:

| Lane | What I explore | Flagships |
| --- | --- | --- |
| Applied AI and developer tools | Human-in-the-loop workflows, context retrieval, and reviewable agent behavior | [Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os), [Shed](https://github.com/CasterlyGit/shed), [agent-harness](https://github.com/CasterlyGit/agent-harness) |
| Backend and platform | Typed state, explicit permissions, service boundaries, and operational guardrails | [Trident](https://github.com/CasterlyGit/trident), [emergency-ai](https://github.com/CasterlyGit/emergency-ai) |
| Systems and local interaction | Local-first desktop interaction, voice input, and sandboxed task execution | [Curby](https://github.com/CasterlyGit/curby) |

## Flagship projects

Each project has a distinct evaluation path. The current evidence and readiness
ledger are maintained in [docs/FLAGSHIPS.md](docs/FLAGSHIPS.md).

| Project | Distinct capability |
| --- | --- |
| **[Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os)** | A bounded, local-first control-plane prototype for typed intent, explicit confirmation, dependency planning, and reviewable dry-run work. It performs no network calls and cannot merge or deploy. |
| **[Trident](https://github.com/CasterlyGit/trident)** | A routing-control layer for AI coding agents that keeps budget policy separate from correctness and verification boundaries. |
| **[Shed](https://github.com/CasterlyGit/shed)** | Local context retrieval and a proposal queue for human-reviewed memory changes. |
| **[emergency-ai](https://github.com/CasterlyGit/emergency-ai)** | An offline-first PWA and FastAPI service showing jurisdiction-aware data, retrieval, caching, and privacy-conscious service boundaries. |
| **[Curby](https://github.com/CasterlyGit/curby)** | A macOS voice interface for spoken questions and sandboxed coding-agent task dispatch. |
| **[agent-harness](https://github.com/CasterlyGit/agent-harness)** | A file-based, visible workflow from structured local tickets to GitHub issues and reviewable pull requests. |

## Supporting evidence

Focused repositories remain useful without carrying the main narrative:
[laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) documents
local Whisper.cpp push-to-talk dictation for macOS, while
[Ledge](https://github.com/CasterlyGit/ledge) demonstrates a native AppKit
screenshot shelf.

## How I work

I prefer small, inspectable changes with explicit boundaries:

- Public claims should be traceable to source, tests, or reproducible documentation.
- Automation should preserve a human decision point for consequential work.
- Each repository documents its own current status and limitations; active work is not presented as finished product.

The public positioning roadmap, active program map, and contribution workflow
live in [docs/ROADMAP.md](docs/ROADMAP.md) and
[docs/PROGRAM.md](docs/PROGRAM.md). Flagship selection, current status, and
source evidence live in [docs/FLAGSHIPS.md](docs/FLAGSHIPS.md). The proportional
delivery benchmark and truthful version progression are maintained in
[docs/DELIVERY.md](docs/DELIVERY.md). The curated project hub is
[casterlygit.github.io](https://casterlygit.github.io/).
