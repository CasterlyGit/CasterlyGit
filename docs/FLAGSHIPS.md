# Flagship Architecture and Readiness Ledger

This ledger explains why six repositories carry the main public engineering
narrative and records what a reader can verify today. Supporting repositories
remain discoverable, but they do not compete with the flagships for the front
door.

## Selection standard

A flagship must contribute a distinct capability, contain public source that
supports its role, state its current limits, and offer a credible setup,
architecture, test, or demo path. Selection does not assert deployment,
adoption, performance, or completion unless the linked evidence establishes
it.

The six projects form a progression from intent, through control and memory,
to application and interaction:

1. Cognitive Development OS structures intent and reviewable plans.
2. Trident makes routing policy and enforcement limits inspectable.
3. Shed retrieves local context and preserves human approval for learning.
4. emergency-ai applies backend and offline-first patterns to a bounded domain.
5. Curby explores local voice interaction and sandboxed task dispatch.
6. agent-harness makes the issue-to-pull-request workflow visible and
   interruptible.

## Capability and evidence matrix

| Flagship | Primary lane | Distinct capability | Source-backed evaluation path |
| --- | --- | --- | --- |
| [Cognitive Development OS](https://github.com/CasterlyGit/cognitive-development-os) | Applied AI / control plane | Typed, append-only intent records; explicit confirmation; restart-safe dependency and conflict planning; bounded dry-run compilation | [Status and limits](https://github.com/CasterlyGit/cognitive-development-os/blob/d2d6e7cfff219f78df6e2cdd324672d7b6f26b70/README.md) · [architecture](https://github.com/CasterlyGit/cognitive-development-os/blob/d2d6e7cfff219f78df6e2cdd324672d7b6f26b70/docs/ARCHITECTURE.md) · [tests](https://github.com/CasterlyGit/cognitive-development-os/tree/d2d6e7cfff219f78df6e2cdd324672d7b6f26b70/tests) |
| [Trident](https://github.com/CasterlyGit/trident) | Developer tools / systems | Budget-aware agent routing with an explicit bright line between routing and correctness | [Status and setup](https://github.com/CasterlyGit/trident/blob/28b8021e2a344abb0d500f51b5685225f43cd3fd/README.md) · [verified mechanics](https://github.com/CasterlyGit/trident/blob/28b8021e2a344abb0d500f51b5685225f43cd3fd/ARCHITECTURE.md) · [tests](https://github.com/CasterlyGit/trident/tree/28b8021e2a344abb0d500f51b5685225f43cd3fd/tests) |
| [Shed](https://github.com/CasterlyGit/shed) | Applied AI / developer tools | Local context retrieval plus queued, human-reviewed memory proposals | [Status, setup, and limits](https://github.com/CasterlyGit/shed/blob/f6c5188975f2bfe0fd88a78d75d15c9326e1714e/README.md) · [design](https://github.com/CasterlyGit/shed/blob/f6c5188975f2bfe0fd88a78d75d15c9326e1714e/docs/DESIGN.md) · [tests](https://github.com/CasterlyGit/shed/tree/f6c5188975f2bfe0fd88a78d75d15c9326e1714e/tests) |
| [emergency-ai](https://github.com/CasterlyGit/emergency-ai) | Backend / platform | Offline-first PWA behavior paired with a FastAPI service, retrieval, caching, metrics, and explicit privacy boundaries | [Status and setup](https://github.com/CasterlyGit/emergency-ai/blob/db22f528c872862b7d25d90f2e291133e87bf10a/README.md) · [architecture](https://github.com/CasterlyGit/emergency-ai/blob/db22f528c872862b7d25d90f2e291133e87bf10a/ARCHITECTURE.md) · [tests](https://github.com/CasterlyGit/emergency-ai/tree/db22f528c872862b7d25d90f2e291133e87bf10a/tests) |
| [Curby](https://github.com/CasterlyGit/curby) | Systems / local interaction | macOS voice interaction for spoken questions and sandboxed coding-agent task dispatch | [Status, setup, and limits](https://github.com/CasterlyGit/curby/blob/45794aad67da17e138acdc29ec18536151d528b5/README.md) · [implementation](https://github.com/CasterlyGit/curby/tree/45794aad67da17e138acdc29ec18536151d528b5/src) · [tests](https://github.com/CasterlyGit/curby/tree/45794aad67da17e138acdc29ec18536151d528b5/tests) |
| [agent-harness](https://github.com/CasterlyGit/agent-harness) | Applied AI / workflow automation | File-based, visible, interruptible automation from a structured local ticket to GitHub review | [Status, setup, and boundaries](https://github.com/CasterlyGit/agent-harness/blob/9b34357f860f1ce83f6c1e637304fecac048557f/README.md) · [skills](https://github.com/CasterlyGit/agent-harness/tree/9b34357f860f1ce83f6c1e637304fecac048557f/skills) · [shell tests](https://github.com/CasterlyGit/agent-harness/blob/9b34357f860f1ce83f6c1e637304fecac048557f/bin/pr-test.sh) |

## Readiness status

This is a dependency ledger, not a quality ranking. `Ready` means the current
public evaluation layer and its checks are complete. Other states name the next
gate rather than hiding it.

Release readiness is tracked separately because a clear evaluation path does
not by itself justify a version tag. See the
[delivery and version ledger](DELIVERY.md) for each project's audited version
stage, next eligible milestone, and evidence gate.

| Flagship | State | Verified current status and next gate |
| --- | --- | --- |
| Cognitive Development OS | Deferred on active implementation | The bounded Layer 4 default branch has passing tests. Flagship evaluation issue [#15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) waits for active control-plane and north-star documentation work to settle so it does not describe moving source. |
| Trident | Ready | The evaluation navigation, verified-mechanics link, test stabilization, and live CI badge are complete through [PR #13](https://github.com/CasterlyGit/trident/pull/13); default-branch CI is passing. |
| Shed | Ready | [PR #37](https://github.com/CasterlyGit/shed/pull/37) restored the Ruff/release-guard baseline; stacked [PR #39](https://github.com/CasterlyGit/shed/pull/39) made memory-aging verification deterministic. [PR #40](https://github.com/CasterlyGit/shed/pull/40) added the bounded evaluation and benchmark path; default-branch CI is passing. |
| emergency-ai | Ready | [PR #13](https://github.com/CasterlyGit/emergency-ai/pull/13) restored the Python 3.11/3.12 verification baseline. [PR #15](https://github.com/CasterlyGit/emergency-ai/pull/15) added an explicit evaluation path and bounded deployment, latency, offline, and domain-validation claims; default-branch CI is passing. |
| Curby | Deferred on active feature work | Public source documents the v0.3 path. Active [PR #41](https://github.com/CasterlyGit/curby/pull/41) overlaps broader presentation work and currently has inherited Ruff failures; the default-branch quality gate is tracked in [#48](https://github.com/CasterlyGit/curby/issues/48). |
| agent-harness | Owner decision blocks guard remediation | Documentation issue [#1](https://github.com/CasterlyGit/agent-harness/issues/1) depends on release-guard remediation [PR #3](https://github.com/CasterlyGit/agent-harness/pull/3). Its GitHub Project sync check requires an owner-controlled Actions token configuration; the check is not bypassed. |

## Supporting repositories

- [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) is focused
  evidence for local Whisper.cpp push-to-talk dictation on macOS, with Linux
  documented as best-effort.
- [Ledge](https://github.com/CasterlyGit/ledge) is focused evidence for native
  AppKit desktop UI work.

Supporting status can change independently. A supporting repository becomes a
flagship only through a new evidence review and a focused roadmap decision.

## Owner-only boundary

This architecture recommends that the six flagships be considered for profile
pins, but it does not change pins, repository metadata, profile fields,
visibility, ownership, archive state, or names. Those decisions remain in
[profile decision #3](https://github.com/CasterlyGit/CasterlyGit/issues/3).
