# Public Engineering Readiness Program

This document is the execution map for the public GitHub presence. It keeps
the profile readable while making the engineering evidence behind it easier to
inspect. Work proceeds through public issues, focused branches, verified pull
requests, and normal repository review.

## Program standard

Each layer must meet all of these conditions before it is marked complete:

1. Its public statements link to source, tests, or reproducible documentation.
2. Its status and limitations are explicit.
3. Its change is scoped to one repository and verified in proportion to risk.
4. It does not expose private career, contact, employment, application, or
   work-authorization information.

## Execution map

| Layer | State | Scope and acceptance condition | Tracking |
| --- | --- | --- | --- |
| Foundation | Complete | Concise three-lane profile front door, public workflow templates, and evidence boundaries. | [#1](https://github.com/CasterlyGit/CasterlyGit/issues/1) · [PR #4](https://github.com/CasterlyGit/CasterlyGit/pull/4) |
| Evidence baseline | Complete | Every featured-profile claim has an immutable-source audit; one platform qualifier was corrected. | [#2](https://github.com/CasterlyGit/CasterlyGit/issues/2) · [PR #5](https://github.com/CasterlyGit/CasterlyGit/pull/5) |
| Program map | Active | Maintain this dependency-aware execution map and update roadmap state as verified repository layers land. | [#6](https://github.com/CasterlyGit/CasterlyGit/issues/6) |
| Flagship control plane | Deferred on active implementation | Cognitive Development OS gains an evaluator path only after its active Layer 5 and Layer 6 pull requests settle; the result must preserve its bounded dry-run status. | [Cognitive Development OS #15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) |
| Trident developer-tool trust signal | Complete | The live demo now links to the README, verified mechanics, and acceptance gates; CI is live and its badge reflects current status. Release checks and time-dependent tests were stabilized first. | [Trident #5](https://github.com/CasterlyGit/trident/issues/5) · [PR #9](https://github.com/CasterlyGit/trident/pull/9) · [PR #10](https://github.com/CasterlyGit/trident/pull/10) · [PR #12](https://github.com/CasterlyGit/trident/pull/12) · [PR #13](https://github.com/CasterlyGit/trident/pull/13) |
| Shed and agent-harness trust signals | Active | Improve source-backed evaluation paths: current behavior, boundaries, setup, and verification. | [Shed #33](https://github.com/CasterlyGit/shed/issues/33) · [agent-harness #1](https://github.com/CasterlyGit/agent-harness/issues/1) |
| Systems and local interaction | Deferred on active feature work | Reassess Curby and laptop-dictation after their active feature pull requests land; then improve only source-backed setup, status, or verification docs. Ledge is queued for the same evidence review. | [Curby PR #41](https://github.com/CasterlyGit/curby/pull/41) · [laptop-dictation PR #6](https://github.com/CasterlyGit/laptop-dictation/pull/6) |
| Profile metadata and pins | Owner decision | Produce a precise recommendation, but do not change profile fields, pins, external links, or repository metadata without explicit approval. | [#3](https://github.com/CasterlyGit/CasterlyGit/issues/3) |

## Dependency rules

- Documentation that describes active implementation waits for the associated
  implementation pull request to settle if the wording would overlap.
- A repository with an active feature pull request is not changed for broad
  presentation work unless the change is demonstrably non-overlapping.
- Repository descriptions, topics, account fields, pinned repositories,
  visibility, ownership, archive state, and names are owner-controlled state.
- A claim that cannot be verified is removed or rewritten conservatively; it is
  never inferred from intent or a planned feature.

## Decision log

| Decision | State | Boundary |
| --- | --- | --- |
| Public framing uses three engineering lanes, with evidence links rather than achievement claims. | Accepted | [ADR 0001](decisions/0001-public-positioning-boundaries.md) |
| Cognitive Development OS is active and bounded, not a finished autonomous system. | Accepted | Profile and future flagship documentation must retain this distinction. |
| Direct profile metadata, pinned repositories, and external links | Needs owner decision | [#3](https://github.com/CasterlyGit/CasterlyGit/issues/3) |
| Private projects or private material as public evidence | Rejected | Public documentation links only to public, source-verifiable material. |

## Completion condition

The program is substantively complete when each active public evidence
repository has a clear, source-backed evaluation path; the profile is re-audited
against those paths; and the only remaining work is explicitly owner-controlled
account or repository state.
