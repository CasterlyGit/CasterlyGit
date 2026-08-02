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
| [Shed](https://github.com/CasterlyGit/shed) | Applied AI / developer tools | Local context retrieval plus queued, human-reviewed memory proposals | [Status, setup, and limits](https://github.com/CasterlyGit/shed/blob/3a2267a96626ab4d445285b8a28b8fbf5714bbe0/README.md) · [version lineage](https://github.com/CasterlyGit/shed/blob/3a2267a96626ab4d445285b8a28b8fbf5714bbe0/docs/VERSIONING.md) · [design](https://github.com/CasterlyGit/shed/blob/3a2267a96626ab4d445285b8a28b8fbf5714bbe0/docs/DESIGN.md) · [tests](https://github.com/CasterlyGit/shed/tree/3a2267a96626ab4d445285b8a28b8fbf5714bbe0/tests) |
| [emergency-ai](https://github.com/CasterlyGit/emergency-ai) | Backend / platform | Offline-first PWA behavior paired with a FastAPI service, retrieval, caching, metrics, and explicit privacy boundaries | [Status and setup](https://github.com/CasterlyGit/emergency-ai/blob/d2f6a256bc7299ffbec50d345ddaeab693d23eb2/README.md) · [version status](https://github.com/CasterlyGit/emergency-ai/blob/d2f6a256bc7299ffbec50d345ddaeab693d23eb2/docs/VERSIONING.md) · [architecture](https://github.com/CasterlyGit/emergency-ai/blob/d2f6a256bc7299ffbec50d345ddaeab693d23eb2/ARCHITECTURE.md) · [tests](https://github.com/CasterlyGit/emergency-ai/tree/d2f6a256bc7299ffbec50d345ddaeab693d23eb2/tests) |
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
| Cognitive Development OS | Ready for repositioning | [PR #27](https://github.com/CasterlyGit/cognitive-development-os/pull/27) added the source-backed evaluator path and [PR #28](https://github.com/CasterlyGit/cognitive-development-os/pull/28) added conservative private-data and scope defaults; both merged with green CI. Further product execution is separately owned. |
| Trident | Active post-release evidence | The evaluation navigation, verified-mechanics link, test stabilization, and live CI badge are complete through [PR #13](https://github.com/CasterlyGit/trident/pull/13). [PR #15](https://github.com/CasterlyGit/trident/pull/15) records the next release gate and awaits CI. |
| Shed | Ready | [PR #37](https://github.com/CasterlyGit/shed/pull/37) restored the Ruff/release-guard baseline; stacked [PR #39](https://github.com/CasterlyGit/shed/pull/39) made memory-aging verification deterministic. [PR #40](https://github.com/CasterlyGit/shed/pull/40) added the bounded evaluation and benchmark path. [PR #42](https://github.com/CasterlyGit/shed/pull/42) records the non-monotonic release lineage and prospective gate; default-branch CI is passing. |
| emergency-ai | Ready | [PR #13](https://github.com/CasterlyGit/emergency-ai/pull/13) restored the Python 3.11/3.12 verification baseline. [PR #15](https://github.com/CasterlyGit/emergency-ai/pull/15) added an explicit evaluation path and bounded deployment, latency, offline, and domain-validation claims. [PR #17](https://github.com/CasterlyGit/emergency-ai/pull/17) distinguishes the unreleased 1.0 development line from a stable release; default-branch CI is passing. |
| Curby | Active quality-repair stack | Public source documents the v0.3 path. [PR #41](https://github.com/CasterlyGit/curby/pull/41) is conflicted; stacked [PR #50](https://github.com/CasterlyGit/curby/pull/50) and [PR #52](https://github.com/CasterlyGit/curby/pull/52) must settle before new presentation work. The baseline remains tracked in [#48](https://github.com/CasterlyGit/curby/issues/48). |
| agent-harness | Owner-deferred credential gate | Documentation issue [#1](https://github.com/CasterlyGit/agent-harness/issues/1) depends on release-guard remediation [PR #3](https://github.com/CasterlyGit/agent-harness/pull/3). Its GitHub Project sync check requires an owner-controlled Actions token configuration, which the owner has explicitly deferred; the check is not bypassed or counted as program failure. |

## Supporting repositories

- [laptop-dictation](https://github.com/CasterlyGit/laptop-dictation) is focused
  evidence for local Whisper.cpp push-to-talk dictation on macOS, with Linux
  documented as best-effort.
- [Ledge](https://github.com/CasterlyGit/ledge) is focused evidence for native
  AppKit desktop UI work.

Supporting status can change independently. A supporting repository becomes a
flagship only through a new evidence review and a focused roadmap decision.

## Owner-only boundary

The six flagships are now the profile's pinned repositories: Cognitive
Development OS, Trident, Shed, emergency-ai, Curby, and agent-harness. The
approved pin decision does not change repository metadata, profile fields,
visibility, ownership, archive state, or names. Bio and external-link choices
remain in [profile decision #3](https://github.com/CasterlyGit/CasterlyGit/issues/3).
