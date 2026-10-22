# got — Progress

## Current milestone
0 — Go setup — not started (next session starts here)

## Done
- [x] Session 0 — project setup (2026-10-16) — wrote CLAUDE.md; created `.claude/` (reference
  docs in `.claude/docs/`, commands `/start`, `/hint`, `/review`, `/checkpoint`, `/sandbox`);
  created `sandbox/` with README. No Go code yet.

## Next session
- Run `/start` → Milestone 0: `go mod init` (fill in module path `github.com/<me>/got`),
  decide where the empty root `main.go` goes (`cmd/got/main.go`), first passing test,
  create `sandbox/go.mod` as a nested module.
- Optional sandbox exercise: `01-modules`.

## Concepts I've learned
- (none yet)

## Things I struggled with (revisit)
- (none yet)

## Sandbox
- (none yet)

## Ideas / backlog
- Design `got` with a hash-size constant (not a hardcoded 20) so SHA-256 support is possible later.
