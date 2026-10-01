# Project State

**The living state of the project: what exists, what is next, and how to verify a change.** Update it
in the same pull request as the work it describes.

- **Last updated:** 2026-10-01
- **Current stage:** S0 · Ground — nothing is built yet; see [ROADMAP.md](ROADMAP.md)
- **Board:** <https://github.com/users/shoraLBRT/projects/4>
- **What gets built:** [SPEC.md](SPEC.md)

---

## What exists

| Part | State | Where |
| --- | --- | --- |
| Specification | Agreed 2026-10-01 | [`docs/SPEC.md`](SPEC.md) |
| Roadmap and backlog | 22 issues in stages S0–S5 on the board, with native *blocked by* relations | [`docs/ROADMAP.md`](ROADMAP.md) |
| Code | None yet | — |
| CI, branch protection | None yet — issue #2 | — |

## Verification

No code yet. Issue #1 sets the commands here; until then a change is documents only and is checked
by reading.

## Known facts already verified

- Native GitHub "blocked by" relations can be **written** through the REST API
  (`POST /repos/{owner}/{repo}/issues/{n}/dependencies/blocked_by`), including across repositories —
  used to set up this backlog. Reading them with Bellboy's tokens is still for #6.

## Open questions for the owner

- The licence (#5).
- The host (#20), in stage S5.
