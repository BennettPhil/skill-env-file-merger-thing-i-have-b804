---
name: env-file-merger-thing-i-have-b804
description: env file merger thing - I have .env.example and .env.local and .env.production and i always mess up which v...
version: 0.1.0
license: Apache-2.0
---

# env-file-merger-thing-i-have-b804

## Purpose

Use this skill to implement and operate: env file merger thing - I have .env.example and .env.local and .env.production and i always mess up which vars are in which. want something that diffs them and shows me whats missing.

## Instructions

1. Run `./scripts/run.sh --help` to inspect supported inputs.
2. Run `./scripts/run.sh "<target>"` to generate an execution plan and recommended checks.
3. Review the emitted checklist and adapt it for your repository or environment.

## Inputs

- A target name or path as the main argument.
- Optional `--context` text to provide extra constraints.

## Outputs

- A structured checklist printed to stdout.
- Exit code `0` on success and non-zero on invalid usage.

## Constraints

- This starter implementation is intentionally minimal.
- Tailor the generated checklist before using it in production workflows.
