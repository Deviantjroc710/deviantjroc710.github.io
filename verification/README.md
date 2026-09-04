# `verification/` — Backup and verification

**Live:** <https://mankowkorp.github.io/verification/>
**Linked from:** `/index.html` (card 3, At night)

## What this page claims

- A verifier compared a tree against a baseline built in the same run, so a PASS
  meant the files matched a snapshot of themselves taken seconds earlier.
- The baseline is now rebuilt from version history at a point ~19 hours earlier.
- The verifier prints the baseline's identity and age and asserts it predates the
  tree, refusing to run rather than passing if it does not.
- It currently reports 2 files missing and 29 changed, each accounted for.
- Backups run unattended, report failures loudly, and a restore has been rehearsed.

Every number above is load-bearing. If one changes, change it here in the same
commit, and say where the new figure came from.

## Must not appear here

- Machine names, paths, or any detail of what is being backed up.
- The specific tooling, which is in a private repository.

Plus the repository-wide rules in [../README.md](../README.md) — no named
people, employer, industry, location, internal systems, credentials, or code.

## If you edit it

The page links `../style.css`; it has no styles of its own and should not
grow any. Keep the heading order, the back link, and the closing note about
what is unnamed and why — that note is what stops a reader assuming the gaps
are carelessness.
