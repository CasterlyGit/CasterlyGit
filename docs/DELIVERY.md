# Delivery Evidence and Version Progression

This ledger applies a proportional engineering-delivery benchmark to the six
flagships. It is a public-evidence consumer, not a second delivery framework.
Paver owns the forthcoming Project Delivery Standard health model, mechanical
checks, and durable delivery ledger. This program will link to and consume
those results when they are available; repository-native source, issues, pull
requests, tests, and CI remain the evidence of record in the meantime.

## Proportional delivery benchmark

Every flagship should let a technical reader answer the first four questions.
The last two apply only where the product shape justifies them.

| Evidence dimension | Required public answer |
| --- | --- |
| User, problem, and primary workflow | Who the current artifact is for, what bounded problem it explores, and the shortest representative workflow. |
| Status and limitations | What works now, what is experimental or deferred, and which safety, platform, or domain boundaries remain. |
| Test and CI evidence | The supported verification command and current CI state, or an explicit gap with an issue that owns it. |
| Ownership and verification path | Where architecture, source, tests, issue history, and human decision points can be inspected. |
| Environment, preview, or demo | A reproducible local path or safe public preview when it is representative. A local tool is not required to become a hosted service. |
| Observability, rollback, and recovery | Required for genuinely deployed products: how failures are detected, how a change is reversed, and how state is recovered. For source prototypes, the truthful answer may be "not deployed; repository rollback and local state reset only." |

Application is deliberately proportional:

- **Experiment or bounded prototype:** status, limits, source, and a repeatable
  validation path. No deployment requirement.
- **Local tool:** supported environment, setup effects, local data boundaries,
  failure/recovery path, and tests. A hosted preview is optional and may be
  inappropriate.
- **Public flagship application or library:** all applicable evidence above,
  green supported CI, a deliberate version policy, and release notes for each
  new release.
- **Deployed product:** the public-flagship requirements plus environment
  ownership, observable health, rollback, and state-recovery evidence.

Paver integration is one-way: future Paver health or delivery-ledger results
may satisfy or update a row here, but this repository does not reproduce
Paver's scoring, capability registry, execution receipts, or policy engine.

## Current readiness benchmark

`Gap` is the next missing or stale evidence, not a claim that every repository
should become a deployed service.

| Flagship and product shape | User, problem, and primary workflow | Verification and environment evidence | Recovery or operations expectation | Current gap |
| --- | --- | --- | --- | --- |
| Cognitive Development OS — bounded prototype | A local operator records typed intent, confirms consequential steps, inspects dependencies, and compiles a dry-run plan. | Architecture, source, and tests cover the bounded default branch; it makes no network calls and cannot merge or deploy. | Repository rollback and resettable local prototype state; production observability is not applicable. | Active implementation and north-star documentation must settle before [#15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) adds a stable evaluator path. |
| Trident — public developer tool | A coding-agent operator evaluates and applies explicit budget-aware routing while preserving separate correctness checks. | README, verified-mechanics documentation, tests, live CI, and a bounded browser demo are linked from the flagship ledger. | Configuration/source rollback and explicit routing fallbacks; it does not own downstream correctness or deployment recovery. | Keep demo, mechanics, and CI evidence current as post-`v0.2.0` behavior changes; no deployment evidence is required. |
| Shed — local tool | A local user retrieves project context and reviews queued memory proposals before applying them. | Isolated local setup, tests, CI, design documentation, and scoped benchmarks are current. First model acquisition may require network access. | Local data can be reviewed and reset; proposed learning remains human-approved. Hosted-service operations are not applicable. | [PR #42](https://github.com/CasterlyGit/shed/pull/42) documents the non-monotonic `v0.2.0`/`v0.3.0` lineage; an explicit prospective-line decision remains before another release. |
| emergency-ai — source application prototype | A developer runs an offline-first PWA and optional FastAPI path to inspect jurisdiction-aware retrieval, cache, and privacy boundaries. | Supported Python CI, tests, architecture, mock-path smoke checks, and local HTTP setup are documented; no public API deployment is claimed. | Cache/offline behavior and local audit fallback are documented. Production rollback and service recovery become required only if a deployment is claimed. | [PR #17](https://github.com/CasterlyGit/emergency-ai/pull/17) documents the unreleased `1.0.0` development line; a deliberate version/stability decision remains before another release. |
| Curby — local macOS tool | A macOS user asks a spoken question or dispatches a sandboxed coding task through a local interface. | Default-branch v0.3 source and tests are public, but the active feature branch is conflicting and supported CI/public-guard work remains unresolved. | Local process/state recovery and macOS permission guidance are appropriate; a hosted preview is not. | Resolve release-line ancestry and [PR #41](https://github.com/CasterlyGit/curby/pull/41), then establish a green supported verification baseline without bypassing project sync. |
| agent-harness — local workflow automation | A maintainer turns a structured local ticket into a visible GitHub issue/branch/PR flow with human review. | The v0.1 source, README, skills, and shell verification path are public; guard remediation is prepared. | Partial-run detection, retry/interruption behavior, credentials, and state cleanup belong in the runnable verification path. | The required Project sync check is blocked on an owner-controlled Actions token; [PR #3](https://github.com/CasterlyGit/agent-harness/pull/3) must not merge around it. |

## Release policy

Version progression is evidence, not decoration.

1. Preserve existing repository conventions when they are coherent.
2. Create a semantic-version tag or GitHub release only for a verified stable
   milestone on the repository's intended release line.
3. Describe unfinished work as an unreleased development, pre-release, or
   milestone state; do not backfill tags or manufacture history.
4. A release is ineligible while supported CI fails, public claims are
   unverified, the candidate branch conflicts with its intended base, or an
   applicable privacy/release/review gate is blocked.
5. Release notes identify user-visible changes, verification performed,
   known limitations, and any migration, rollback, or recovery action. A
   changelog is expected when the repository already maintains one or when
   multiple releases make progression otherwise difficult to inspect.

## Flagship version and delivery ledger

The version facts below were audited against tags, GitHub releases, manifests,
README status, and default-branch ancestry on 2026-08-02. `Next eligible`
describes a gate, not a promised release.

| Flagship | Current truthful stage | Release/version policy | Next eligible milestone | Notes and proof of eligibility |
| --- | --- | --- | --- | --- |
| Cognitive Development OS | Unreleased `0.1.0` prototype; no tags or GitHub releases | Keep the manifest version as a development marker until the bounded control-plane milestone is stable; first SemVer release must be prospective. | `v0.1.0` only after the active stage series settles, the evaluator path in [#15](https://github.com/CasterlyGit/cognitive-development-os/issues/15) is current, supported CI is green, and README limits match source. | First release notes must cover the representative intent-to-dry-run workflow, verification, and explicit non-network/non-deployment boundaries. Proof: manifest, immutable source/tests, green candidate CI, and public-claim audit. |
| Trident | `v0.2.0` is the latest release; default branch contains later unreleased changes | Continue the existing SemVer minor-milestone convention. Documentation or quality cleanup alone does not create a feature release. | `v0.3.0` after one coherent, verified feature milestone beyond `v0.2.0`, with green CI and re-audited mechanics. | Release notes/changelog should separate routing-policy changes from correctness guarantees and list tests. Proof: candidate ancestry, default-branch CI, demo/README consistency, and release checklist. |
| Shed | GitHub marks `v0.3.0` as latest, but that tag is an ancestor of the later `v0.2.0` tag; default-branch package and README metadata report `0.2.0` | Preserve both historical tags/releases. Document the non-monotonic lineage and reconcile the intended prospective line before changing metadata or releasing again. | A next version is assigned only after [Shed #41](https://github.com/CasterlyGit/shed/issues/41) records the intended line; the candidate must add a distinct verified capability with green supported CI and current benchmark/setup claims. | Do not move, recreate, or manufacture chronology for either tag. Future notes identify lineage, setup/data effects, human-review boundaries, measured benchmark scope, migration, and recovery. Proof: candidate ancestry, explicit version decision, manifest/README consistency, tests, CI, guard, and claim audit. |
| emergency-ai | `v0.2.0` is the latest release; default branch and manifest form an unreleased `1.0.0` development line | Do not infer stability from the manifest alone. Reconcile status and version deliberately before the next release. | A release only after the intended version is resolved, supported CI is green, offline/PWA and API deployment claims are verified, and clinical/legal limits remain explicit. | Release notes must distinguish deployed evidence from local source behavior, cover offline/cache recovery and data migrations, and retain domain-validation limits. Proof: version/status decision, representative smoke/tests, CI, guard, and deployment evidence if deployment is claimed. |
| Curby | Default branch documents `v0.3`; historical `v0.4.0` is not an ancestor of default branch; active feature work conflicts with main | Preserve the historical tag; do not move, recreate, or present it as default-branch progression. Resolve the intended release line before assigning another version. | Owner/repository-history decision after [PR #41](https://github.com/CasterlyGit/curby/pull/41) is conflict-free and supported CI plus public guard are green. Only then choose a prospective next version. | Notes must distinguish measured behavior from targets and cover macOS permissions, local state, failure recovery, and rollback. Proof: resolved ancestry, green supported CI/guard, representative local verification, and README consistency. |
| agent-harness | `v0.1.0` tag, release, manifest, and default branch are aligned | Continue prospective SemVer releases after an end-to-end workflow milestone; never release around a required project-sync or public guard. | `v0.2.0` after the owner-controlled Actions token unblocks [PR #3](https://github.com/CasterlyGit/agent-harness/pull/3), readiness documentation and runnable verification are current, and all checks pass. | Release notes cover ticket-to-PR behavior, interruption/retry boundaries, required credentials, and recovery from partial runs. Proof: aligned candidate, shell/end-to-end verification, green CI/guard/sync, and public-claim audit. |

No new release is currently authorized by this ledger. A project becomes
eligible only when the named evidence exists on the intended release line; the
ordinary repository issue, branch, pull-request, review, and release-checklist
workflow still applies.
