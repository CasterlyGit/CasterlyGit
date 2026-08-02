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
| Flagship narrative | Complete | The six projects have distinct lane roles, selection rationale, immutable evidence links, and a current dependency ledger. | [#9](https://github.com/CasterlyGit/CasterlyGit/issues/9) · [flagship ledger](FLAGSHIPS.md) |
| Flagship control plane | Deferred on active implementation | Cognitive Development OS gains an evaluator path only after its active control-plane and north-star documentation pull requests settle; the result must preserve its bounded dry-run status. | [Cognitive Development OS #15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) |
| Trident developer-tool trust signal | Complete | The live demo now links to the README, verified mechanics, and acceptance gates; CI is live and its badge reflects current status. Release checks and time-dependent tests were stabilized first. | [Trident #5](https://github.com/CasterlyGit/trident/issues/5) · [PR #9](https://github.com/CasterlyGit/trident/pull/9) · [PR #10](https://github.com/CasterlyGit/trident/pull/10) · [PR #12](https://github.com/CasterlyGit/trident/pull/12) · [PR #13](https://github.com/CasterlyGit/trident/pull/13) |
| Shed and agent-harness trust signals | Active | Improve source-backed evaluation paths: current behavior, boundaries, setup, and verification. | [Shed #33](https://github.com/CasterlyGit/shed/issues/33) · [agent-harness #1](https://github.com/CasterlyGit/agent-harness/issues/1) |
| emergency-ai trust signal | Complete | Supported Python CI is green; status, setup, architecture, verification, latency evidence, deployment state, and domain limits are explicit. | [emergency-ai #12](https://github.com/CasterlyGit/emergency-ai/issues/12) · [PR #13](https://github.com/CasterlyGit/emergency-ai/pull/13) · [PR #15](https://github.com/CasterlyGit/emergency-ai/pull/15) |
| Systems and local interaction | Deferred on active feature work | Reassess Curby after its active feature pull request settles and its inherited verification baseline is green. laptop-dictation and Ledge remain supporting evidence. | [Curby PR #41](https://github.com/CasterlyGit/curby/pull/41) · [Curby #48](https://github.com/CasterlyGit/curby/issues/48) |
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
| Six flagships carry distinct roles; laptop-dictation and Ledge remain supporting evidence. | Accepted | [Flagship architecture](FLAGSHIPS.md) |
| Direct profile metadata, pinned repositories, and external links | Needs owner decision | [#3](https://github.com/CasterlyGit/CasterlyGit/issues/3) |
| Private projects or private material as public evidence | Rejected | Public documentation links only to public, source-verifiable material. |

## Completion condition

The program is substantively complete when each active public evidence
repository has a clear, source-backed evaluation path; the profile is re-audited
against those paths; and the only remaining work is explicitly owner-controlled
account or repository state.

## Final definition of done

CasterlyGit is complete when its public overview is organized around these six
flagship projects, with supporting repositories discoverable as evidence rather
than presented as a flat list:

1. **Cognitive Development OS** — bounded local-first planning and review
   control-plane work.
2. **Trident** — developer-tool systems work with explicit routing and
   verification boundaries.
3. **Shed** — local context retrieval and human-approved learning proposals.
4. **emergency-ai** — backend/platform architecture with documented operating
   limits.
5. **Curby** — local desktop and voice-driven interaction work.
6. **agent-harness** — reviewable workflow automation from structured task to
   pull request.

Each flagship must have verified current status, credible setup or architecture
evidence, a reproducible validation path where applicable, and an accurate role
in the overall engineering story. Public overview copy may promote a flagship
only after its source evidence and stated limits are current.

## Autonomous dependency queue

Work advances through this ordered queue. After a verified result, select the
highest-value unblocked item in the earliest incomplete phase; do not treat a
merged pull request as a program endpoint.

| Phase | Queue objective | Gate to advance |
| --- | --- | --- |
| 1. Governance | Maintain roadmap, capability matrix, issue/PR workflow, evidence standards, release/privacy checks, and owner-only settings/pins boundary. | The central map names all work and owner decisions. |
| 2. Flagship narrative | Publish the six-project structure, selection rationale, status ledger, and evidence links. | Every promoted statement is source-backed and each candidate passes readiness review. |
| 3. Per-repository readiness | Give every flagship truthful README/status/limitations, architecture/setup, validation, and applicable demo evidence. | Repository-specific checks pass and claims are re-audited. |
| 4. Quality repair | Repair inherited documentation, lint, CI, workflow, release-guard, and test-baseline defects in separate narrow changes. | The underlying verification gate passes; no gate is weakened or bypassed. |
| 5. Presentation and evidence | Strengthen verified demos, diagrams, examples, tests, and contribution surfaces. | Added presentation is representative and reproducible. |
| 6. Final review | Audit each flagship against overview claims and record exact profile/pin recommendations. | Only explicit owner-controlled settings or irreversible actions remain. |

### Self-healing rule

When a technical check blocks a queued item, record the exact failure in a
narrow remediation issue, repair it through a focused branch and pull request,
verify the original gate, then return to every dependent item. Continue
independent queue items in the meantime. CI, release guards, tests, privacy
checks, review gates, and repository policy are evidence, not obstacles to
work around.
