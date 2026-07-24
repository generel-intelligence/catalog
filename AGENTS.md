# AGENTS.md

## Purpose

This repository owns public, provenance-rich metadata about benchmarks
maintained by third parties.

## Ownership

It will own catalog entries and deterministic catalog exports once they are
introduced. It does not own external benchmark content, Generel Intelligence
benchmark suites, evaluators, or runner adapters.

## Local Contracts

- Record authoritative upstream owners, URLs, versions, and licenses.
- Do not copy datasets or task content without verified redistribution rights.
- Do not store private suites, rubrics, solutions, or evaluators.
- Preserve attribution to both upstream owners and Generel Intelligence.
- Keep adapter status factual; do not claim compatibility without evidence.
- Do not seed benchmark entries during M0.

## Work Guidance

- Prefer primary upstream sources.
- Make corrections narrowly and include supporting provenance.
- Keep generated exports derived from canonical entries once generators exist.

## Verification

- Run `git diff --check`.
- Require the shared `governance` and `security-scan` checks.
- Add catalog validation only when real entries and a declared format exist.

## Child DOX Index

No child `AGENTS.md` files are required at this stage.
