# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository status

As of now, this repository does not contain any source files, build configuration, or test configuration that Warp can detect. The `D:\\MentalHealthApp` directory appears empty.

Future instances of Warp should first re-scan the repository (e.g., using the file searcher or `ls`/`dir`) to pick up any newly added files before assuming the structure described here.

## Commands and workflows

Because there is currently no detectable build system or dependency configuration (no `README.md`, `package.json`, `pyproject.toml`, `.sln`/`.csproj`, etc.), there are no project-specific commands to document yet (build, lint, or tests).

When project files are added, future agents should:

1. Look for language- and framework-specific configuration files (for example: `package.json`, `pyproject.toml`, `requirements.txt`, `*.sln`/`*.csproj`, `build.gradle`, etc.).
2. Prefer any documented commands in `README.md` or other top-level docs over guessing default tool invocations.
3. Once a build/test workflow exists, update this section with concrete commands (e.g., how to run all tests, how to run a single test, how to start the dev server).

## Architecture and structure

There is currently no code to analyze, so there is no existing architecture or module structure to describe.

When code is added, future agents should:

1. Identify the primary entry points (for example: `main` functions, web app entry modules, mobile app projects, etc.).
2. Map out high-level layers or modules (for example: API layer, domain logic, data access, UI components) by scanning directories and key files.
3. Update this section with a short description of the big-picture architecture only (do not enumerate every file), focusing on how major modules depend on each other and how data flows through the application.

## Tooling-specific rules

No CLAUDE, Cursor, Copilot, or other agent-specific rule files were found (e.g., `CLAUDE.md`, `.cursorrules`, `.cursor/rules/`, `.github/copilot-instructions.md`). If such files are added later, future agents should ingest their important project-specific rules and mirror them here in summarized form.