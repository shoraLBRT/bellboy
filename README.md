# Bellboy

Assistant for a developer whose GitHub projects are built by Claude Code agents.

- **It offers work.** When your Claude usage window resets, Bellboy tells you how much usage you
  have and what the next tasks are in each of your projects.
- **It starts work.** Pick a project, a task and a mode with buttons — one task, a loop that keeps a
  reserve, or a loop to the limit — and Bellboy starts a Claude Code cloud session on it.
- **It reports work.** When a task ends you get the PR, the CI result, what was merged, what the task
  cost in usage, and any questions the agent left for you.

Bellboy does not decide what to work on — each project's backlog does — and it does not do the work —
Claude Code does, in Anthropic's cloud. It carries messages and reports back. It has no language model
inside: everything is buttons.

Projects it works with follow the [habze](https://github.com/shoraLBRT/habze) standard: a GitHub
Projects backlog, a protected `main` with required CI, and the shared session skills.

## Status

Specified, not yet built. See [docs/SPEC.md](docs/SPEC.md), [docs/ROADMAP.md](docs/ROADMAP.md) and
the [board](https://github.com/users/shoraLBRT/projects/4).
