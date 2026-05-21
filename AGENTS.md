# AGENTS

Guidelines for AI agents working on this repository.

## Core Principle

Preserve legacy intent.

Never optimize away behavior without evidence.

---

## Development Rules

1. Prefer minimal changes.
2. Preserve historical behavior.
3. Avoid destructive rewrites.
4. Generate explanations for all changes.
5. All modifications must be reversible.

---

## Coding Style

- simple
- explicit
- auditable
- testable

---

## AI Responsibilities

AI may:

- analyze source code
- suggest compatibility fixes
- generate patch files
- explain deprecated APIs

AI must not:

- silently rewrite logic
- remove unknown code
- assume behavior without evidence

---

## Priority Order

1. recover
2. preserve
3. isolate
4. modernize
