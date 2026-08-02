# Featured Repository Evidence Audit

This audit supports [issue #2](https://github.com/CasterlyGit/CasterlyGit/issues/2).
It checks the projects named in the profile README against public source at the
immutable revisions linked below. It does not assert deployment, performance,
adoption, employment, or future-product claims.

## Results

| Repository | Public profile statement checked | Source evidence | Result |
| --- | --- | --- | --- |
| [Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os) | Active, local-first control-plane work with an early dry-run prototype and explicit operating limits | [README at `d2d6e7c`](https://github.com/CasterlyGit/cognitive-development-os/blob/d2d6e7cfff219f78df6e2cdd324672d7b6f26b70/README.md) documents its current status, no-network/no-service limits, and implemented typed intent/dependency layers. | Verified; profile wording retained. |
| [Shed](https://github.com/CasterlyGit/shed) | Local context retrieval and human-reviewed memory proposals | [README at `7d3d79d`](https://github.com/CasterlyGit/shed/blob/7d3d79d2a662ecf0f61195c0b0620f454b2178ed/README.md) documents local retrieval, proposal queues, and manual approval behavior. | Verified; profile wording retained. |
| [agent-harness](https://github.com/CasterlyGit/agent-harness) | A local workflow harness connecting task files, issues, pull requests, and visible review | [README at `9b34357`](https://github.com/CasterlyGit/agent-harness/blob/9b34357f860f1ce83f6c1e637304fecac048557f/README.md) describes the task-file to issue to pull-request flow and human GitHub review. | Verified; profile wording retained. |
| [Trident](https://github.com/CasterlyGit/trident) | A coding-agent routing control layer that keeps verification and correctness boundaries explicit | [README at `8c28ebe`](https://github.com/CasterlyGit/trident/blob/8c28ebeb46e18ae994e35235eb6a1d7b1974f593/README.md) describes routing controls and states that the system does not trade away correctness or tests. | Verified; profile wording retained. |
| [emergency-ai](https://github.com/CasterlyGit/emergency-ai) | A FastAPI-based service with documented architecture and operational dependencies | [README at `0cadff4`](https://github.com/CasterlyGit/emergency-ai/blob/0cadff488f16dd6900a9bcb17d27584b4caaa4e2/README.md) documents the FastAPI service, offline path, and architecture dependencies. | Verified; profile wording retained. |
| [Curby](https://github.com/CasterlyGit/curby) | A macOS voice-driven desktop companion supporting spoken questions and sandboxed coding-agent tasks | [README at `45794aa`](https://github.com/CasterlyGit/curby/blob/45794aad67da17e138acdc29ec18536151d528b5/README.md) documents the macOS interaction model and sandboxed agent-task mode. | Verified; profile wording retained. |
| [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) | Local Whisper.cpp push-to-talk dictation | [README at `c974e74`](https://github.com/CasterlyGit/laptop-dictation/blob/c974e74242ef8f2d2b1f36f55245778788964256/README.md) documents local Whisper.cpp use, macOS support, and Linux as best-effort. | Corrected the profile wording to preserve the Linux qualifier. |
| [Ledge](https://github.com/CasterlyGit/ledge) | A native macOS AppKit screenshot shelf | [README at `905d3dd`](https://github.com/CasterlyGit/ledge/blob/905d3ddf2dd8412d7d3384f62fc4f221e642ee19/README.md) identifies native AppKit implementation and screenshot-shelf behavior. | Verified; profile wording retained. |

## Follow-up rules

- A source change does not automatically update the profile. Re-audit the
  relevant claim and open a focused pull request first.
- Repository descriptions, topics, pinned repositories, and account settings
  are outside this audit. Any direct metadata change needs an explicit owner
  decision.
- Claims with no source, test, or reproducible documentation should be removed
  or rewritten conservatively rather than inferred from intent.
