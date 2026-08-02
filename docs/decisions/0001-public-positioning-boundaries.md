# ADR 0001: Keep public positioning evidence-based and capability-focused

- **Status:** Accepted
- **Date:** 2026-08-01

## Context

This profile repository is a public engineering front door. It needs to make
the relevant work easy to evaluate without publishing private career-search,
application, contact, work-authorization, or employment material.
Several projects are actively evolving, so their descriptions must distinguish
implemented behavior from future direction.

## Decision

Organize the profile around three engineering lanes: applied AI/developer
tools, backend/platform systems, and systems/embedded/AI-adjacent interaction.
Link only to public repositories and write descriptions that can be checked in
their source, tests, or documented status.

Cognitive Development OS is described as actively being built and as a bounded
early dry-run prototype. Direct GitHub profile settings and pinned repository
changes stay outside repository pull requests and require a separate owner
decision.

## Consequences

- The profile can evolve through normal issues, branches, reviews, and pull
  requests without exposing personal search activity.
- Unverified metrics, deployment assertions, and achievement claims are not
  used as positioning copy.
- Every future public-facing change needs evidence and validation notes.
