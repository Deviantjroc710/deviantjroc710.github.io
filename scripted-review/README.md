# `scripted-review/` — "Console-only," allegedly

**Live:** <https://mankowkorp.github.io/scripted-review/>
**Linked from:** `/index.html` (card 3, During the day)

## What this page claims

- A recurring security review existed only as manual clicking through a console.
- It was said three times to be impossible to script. Most of it was scriptable;
  the genuinely manual remainder turned out to be small and is now written down.
- Checks run against known-good and known-bad inputs every time, so a sweep that
  has broken says so instead of returning green.
- The re-check tool prints what it could **not** verify, as a section beside the
  results.
- Runs are timestamped and kept, so the next run is a comparison.

Every number above is load-bearing. If one changes, change it here in the same
commit, and say where the new figure came from.

## Must not appear here

- **The findings themselves.** Some describe things that are still being fixed.
  This page is about method only — that boundary is the whole reason it can exist.
- The platform reviewed, and the protocols involved.

Plus the repository-wide rules in [../README.md](../README.md) — no named
people, employer, industry, location, internal systems, credentials, or code.

## If you edit it

The page links `../style.css`; it has no styles of its own and should not
grow any. Keep the heading order, the back link, and the closing note about
what is unnamed and why — that note is what stops a reader assuming the gaps
are carelessness.
