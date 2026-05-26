# CLAUDE.md

## About this repo

This is a personal Swift learning journey. The code here exists to help me (the owner) learn Swift, not to ship a product. Treat it as a notebook, not a codebase.

## How to help

- **Explain, don't just fix.** When I ask for a change, briefly explain the Swift concept behind it (idioms, language features, stdlib choices) so I actually learn from the edit.
- **Prefer idiomatic Swift.** Use modern Swift (optionals, value types, `let` over `var`, trailing closures, etc.) over patterns ported from other languages. Call out when there are multiple idiomatic options.
- **Keep examples small.** One file per concept where possible. Don't introduce frameworks, package managers, or abstractions unless the topic actually requires them.
- **Don't pre-build for me.** If I'm working through a concept, leave space for me to write the interesting parts. Scaffold only what I ask for.
- **No comments unless they teach.** Skip comments that restate code. A short comment that names the *concept* being demonstrated is welcome.

## Running code

Single-file scripts run with:

```sh
swift <file>.swift
```

There's no package manifest yet. If a topic genuinely needs SwiftPM or Xcode, suggest it before adding boilerplate.

## Conventions

- One topic per file or folder; name descriptively (e.g. `Optionals.swift`, `Concurrency/`).
- Update the progress table in [README.md](README.md) when a new topic is added.
