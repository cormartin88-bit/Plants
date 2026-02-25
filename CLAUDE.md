# CLAUDE.md — Plants Project

This file provides guidance for AI assistants (Claude Code and similar) working in this repository.

## Project Overview

**Name:** Plants
**Status:** Early experiment / in progress
**Repository:** cormartin88-bit/Plants
**Description:** Currently a blank-slate project. As of the last update (2026-02-25), the repository contains only a README. This file should be updated as the project takes shape.

---

## Repository State

As of the initial commit, the project has:

- `README.md` — one-line description ("Plants / Experiment")
- No source code, dependencies, tests, or configuration files yet

This means there is no established stack, framework, or build system to follow. When adding code, document the decisions made here so future contributors and AI assistants can follow the same patterns.

---

## Development Branch

When working on tasks assigned via the Claude Code integration:

- Develop on the branch specified in the task (typically `claude/<task-id>`)
- Always push to that branch, never to `master` without explicit approval
- Use `git push -u origin <branch-name>` for pushes
- Write clear, descriptive commit messages

---

## Conventions to Follow (once the stack is chosen)

Until a stack is established, apply these general principles:

### Code Style
- Prefer readability over cleverness
- Keep functions small and focused
- Name things clearly and descriptively (no single-letter variables except in tight loops)
- Avoid unnecessary abstraction — solve the problem at hand first

### File Organisation
- Group related files in directories by feature or domain, not by file type
- Keep configuration at the project root
- Put tests adjacent to the code they test, or in a dedicated `tests/` / `__tests__/` directory

### Git Workflow
- Commit early and often with meaningful messages
- Prefer atomic commits (one logical change per commit)
- Do not commit secrets, credentials, or `.env` files

### Dependency Management
- Pin dependency versions where possible
- Document why a dependency was added if it is non-obvious

### Testing
- Write tests before or alongside new features, not as an afterthought
- Aim for fast, isolated unit tests; integration tests for critical paths

---

## How to Update This File

As the project evolves, keep this file current:

1. **Stack chosen** — add the language, framework, and key libraries with a short rationale
2. **Build commands** — document how to install, build, run, and test locally
3. **Environment variables** — list required env vars (without values) and their purpose
4. **Architecture decisions** — note any significant design choices that affect how code should be written
5. **Known issues / gotchas** — things that tripped you up that future contributors should know

---

## Quick Reference (populate as the project grows)

```
# Install dependencies
<command TBD>

# Run the application
<command TBD>

# Run tests
<command TBD>

# Lint / format
<command TBD>
```

---

*Last updated: 2026-02-25 by Claude Code (claude-sonnet-4-6)*
