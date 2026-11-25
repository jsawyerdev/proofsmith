# Proofsmith

> Status: concept repository - future work

Independent verification for changes proposed by autonomous coding agents.

## Objective

Determine whether an automated code change fixes the stated problem without suppressing errors, weakening constraints, or manipulating tests.

## Proposed scope

- Derive observable acceptance criteria
- Inspect semantic and behavioural changes
- Use differential and mutation testing
- Execute candidate patches in isolated environments

## Technical direction

Static analysis, mutation testing, differential testing, Tree-sitter, and sandboxed execution.

The technologies above are candidates, not commitments. Selection will follow evidence from the smallest useful prototype.

## Open questions

- What observable result would make the first prototype useful?
- Which assumptions need controlled experiments before implementation?
- What independent oracle can determine whether an experiment succeeded?
- What is the smallest reproducible dataset or workload?

## Repository status

This repository reserves the project identity and records the initial concept. It contains no production implementation, published roadmap, or stable API.
