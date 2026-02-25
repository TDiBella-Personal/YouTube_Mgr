# CLAUDE.md — YouTube_Mgr

## Project Overview

**YouTube_Mgr** is a YouTube management application. The repository is in early-stage setup and does not yet contain application code.

- **Repository**: TDiBella-Personal/YouTube_Mgr
- **Default branch**: `master`
- **Current state**: Initial scaffolding — no source code, build system, or tests yet

## Repository Structure

```
YouTube_Mgr/
├── .git/
├── CLAUDE.md        # This file — guidance for AI assistants
└── README.md        # Project overview (placeholder)
```

## Development Workflow

### Branching

- The default branch is `master`.
- Feature branches should be created off `master` for all new work.
- Use descriptive branch names (e.g., `feature/add-auth`, `fix/upload-bug`).

### Commits

- Write clear, descriptive commit messages.
- Use imperative mood in commit subjects (e.g., "Add upload endpoint", not "Added upload endpoint").
- Keep commits focused — one logical change per commit.

### Testing

- No test framework is configured yet. When one is added, update this section.
- All new features should include tests once a framework is in place.

### Linting / Formatting

- No linter or formatter is configured yet. When one is added, update this section.

## Key Conventions

- **Language / Framework**: Not yet chosen. Update this section once the tech stack is decided.
- **Package manager**: Not yet chosen. Update this section once determined.
- Keep the README.md up to date as the project evolves.

## For AI Assistants

- Read this file before making changes to understand the current project state.
- Do not assume a tech stack — check what actually exists in the repo.
- When adding new tooling (linter, test framework, build system), update this file to reflect the change.
- Prefer editing existing files over creating new ones unless new files are clearly needed.
- Do not introduce unnecessary dependencies or over-engineer solutions.
- If the project gains a `package.json`, `requirements.txt`, `Cargo.toml`, or equivalent, document the relevant commands (install, build, test, lint) in this file.
