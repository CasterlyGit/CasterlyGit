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
5. Its version state is prospective and traceable: no release is inferred from
   a manifest, branch, commit count, or planned milestone alone.

The evidence dimensions and per-flagship release gates are maintained in the
[delivery and version ledger](DELIVERY.md). That ledger consumes Paver's
forthcoming Project Delivery Standard health results when available; Paver,
not this repository, owns the mechanical health model and durable delivery
ledger.

## Execution map

| Layer | State | Scope and acceptance condition | Tracking |
| --- | --- | --- | --- |
| Foundation | Complete | Concise three-lane profile front door, public workflow templates, and evidence boundaries. | [#1](https://github.com/CasterlyGit/CasterlyGit/issues/1) · [PR #4](https://github.com/CasterlyGit/CasterlyGit/pull/4) |
| Evidence baseline | Complete | Every featured-profile claim has an immutable-source audit; one platform qualifier was corrected. | [#2](https://github.com/CasterlyGit/CasterlyGit/issues/2) · [PR #5](https://github.com/CasterlyGit/CasterlyGit/pull/5) |
| Program map | Active | Maintain this dependency-aware execution map and update roadmap state as verified repository layers land. | [#6](https://github.com/CasterlyGit/CasterlyGit/issues/6) |
| Flagship narrative | Complete | The six projects have distinct lane roles, selection rationale, immutable evidence links, and a current dependency ledger. | [#9](https://github.com/CasterlyGit/CasterlyGit/issues/9) · [flagship ledger](FLAGSHIPS.md) |
| Version progression | Active | Every flagship has an audited current version stage, repository-appropriate release policy, next eligible milestone, release-note expectation, and proof gate. Existing mismatches are repaired without rewriting history. | [#16](https://github.com/CasterlyGit/CasterlyGit/issues/16) · [delivery ledger](DELIVERY.md) |
| Project Delivery Standard adoption | Active | Public readiness uses proportional mature-delivery evidence and consumes future Paver health/ledger results without duplicating Paver's implementation. | [#17](https://github.com/CasterlyGit/CasterlyGit/issues/17) · [delivery ledger](DELIVERY.md) |
| Flagship control plane | Deferred on active implementation | Cognitive Development OS gains an evaluator path only after its active control-plane and north-star documentation pull requests settle; the result must preserve its bounded dry-run status. | [Cognitive Development OS #15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) |
| Trident developer-tool trust signal | Complete | The live demo now links to the README, verified mechanics, and acceptance gates; CI is live and its badge reflects current status. Release checks and time-dependent tests were stabilized first. | [Trident #5](https://github.com/CasterlyGit/trident/issues/5) · [PR #9](https://github.com/CasterlyGit/trident/pull/9) · [PR #10](https://github.com/CasterlyGit/trident/pull/10) · [PR #12](https://github.com/CasterlyGit/trident/pull/12) · [PR #13](https://github.com/CasterlyGit/trident/pull/13) |
| Shed trust signal | Complete | Ruff, release-guard, and deterministic test baselines are green; the README exposes current behavior, local/human-review boundaries, setup effects, verification, and bounded benchmark evidence. | [Shed #33](https://github.com/CasterlyGit/shed/issues/33) · [PR #37](https://github.com/CasterlyGit/shed/pull/37) · [PR #39](https://github.com/CasterlyGit/shed/pull/39) · [PR #40](https://github.com/CasterlyGit/shed/pull/40) |
| agent-harness trust signal | Owner-blocked | Release-guard documentation is prepared, but the required GitHub Project sync check needs an owner-controlled Actions token configuration. | [agent-harness #1](https://github.com/CasterlyGit/agent-harness/issues/1) · [PR #3](https://github.com/CasterlyGit/agent-harness/pull/3) |
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
| Version tags and releases are prospective evidence, never presentation artifacts. | Accepted | [Delivery and version ledger](DELIVERY.md) |
| Paver owns the Project Delivery Standard health model and mechanical ledger; this program consumes its results. | Accepted | [Delivery and version ledger](DELIVERY.md) |
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
evidence, a reproducible validation path where applicable, an explicit current
version stage and next eligible release gate, and an accurate role in the
overall engineering story. Public overview copy may promote a flagship only
after its source evidence and stated limits are current. Deployed products must
also document observable health, rollback, and recovery; local tools and
experiments are not required to manufacture deployment evidence.

## Autonomous dependency queue

Work advances through this ordered queue. After a verified result, select the
highest-value unblocked item in the earliest incomplete phase; do not treat a
merged pull request as a program endpoint.

| Phase | Queue objective | Gate to advance |
| --- | --- | --- |
| 1. Governance | Maintain roadmap, capability matrix, issue/PR workflow, evidence standards, truthful version progression, proportional delivery benchmark, release/privacy checks, and owner-only settings/pins boundary. | The central map names all work and owner decisions and defers mechanical delivery health to Paver. |
| 2. Flagship narrative | Publish the six-project structure, selection rationale, status ledger, and evidence links. | Every promoted statement is source-backed and each candidate passes readiness review. |
| 3. Per-repository readiness | Give every flagship truthful README/status/limitations, architecture/setup, validation, applicable demo evidence, and a repository-appropriate version/release path. | Repository-specific checks pass, claims are re-audited, and any release candidate meets its recorded eligibility gate. |
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
