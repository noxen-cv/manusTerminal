# ManusTerminal

Hand-crafted task management for the command line.

ManusTerminal is a text-first, minimal task manager for developers who want speed, focus, and full ownership of their data. It is designed for beginner to advanced developers who prefer a CLI workflow over heavy GUI tools.

## Why ManusTerminal

- Minimal by design: plain text as your source of truth.
- Built for dev flow: terminal-first workflows, fast navigation, no app switching.
- Local-first mindset: your tasks stay in files you can read and version.
- Beginner-friendly, power-user-capable: simple syntax with room for advanced CLI habits.

## Core Product Direction

ManusTerminal aims to combine:

- Plain-text task authoring.
- A clean CLI/TUI experience for viewing and managing tasks.
- Deterministic behavior over opaque automation.
- Familiar command patterns inspired by Unix and Git ergonomics.

## Quick Preview

Planned command style:

```bash
mt start
mt show
mt check 1.2
mt mv 2 --to Work
mt grep "overdue|urgent"
mt export --format md
```

Task text style (example):

```txt
- Errands
	- Clean the Dishes
	- Buy Groceries
- Work
	- Update PM for new code changes
	- Fix bugs on UI
```

## Who This Is For

- Developers who prefer terminal workflows.
- Builders who want a minimal, distraction-free task system.
- Learners using daily planning as a practical way to improve CLI skills.

## Project Status

This repository is currently in scaffold stage.

- Initial folders are prepared for source, tests, scripts, and workflows.
- Health files are in place for contribution and governance.
- Core implementation is not yet included in this stage.

## Repository Structure

```text
.
|-- .github/
|   `-- workflows/
|-- docs/
|   `-- originalIdea/
|-- scripts/
|-- src/
|   `-- manus/
|-- tests/
|   `-- fixtures/
|-- CHANGELOG.md
|-- CODE_OF_CONDUCT.md
|-- CONTRIBUTING.md
|-- LICENSE
|-- SECURITY.md
|-- SUPPORT.md
`-- readme.md
```

## Contributing

Contributions are welcome. Start with:

- CONTRIBUTING.md for workflow and PR expectations.
- CODE_OF_CONDUCT.md for community standards.
- CHANGELOG.md to track user-facing changes.

## Support and Security

- Support process: SUPPORT.md
- Security reporting: SECURITY.md

## License

MIT. See LICENSE.
