# `guards/` — Scans that reported clean because they couldn't run

**Live:** <https://mankowkorp.github.io/guards/>
**Linked from:** `/index.html` (card 2, During the day)

## What this page claims

- Permission errors were flowing downstream as empty results, so a scan that was
  never allowed to look reported zero findings — three times.
- Guards now stop the run and name the failure instead of returning a clean result.
- On first execution the guards caught 9 violations in scripts considered finished.
- The test suite was checked by deliberately breaking the code: 8 sabotages, 8
  caught; assertions went from ~22 to 41.
- The change also introduced the repository's first CI.

Every number above is load-bearing. If one changes, change it here in the same
commit, and say where the new figure came from.

## Must not appear here

- What the tool scans for in enough detail to be useful to someone else.
- Which system it runs against, and any repository or pipeline name.

Plus the repository-wide rules in [../README.md](../README.md) — no named
people, employer, industry, location, internal systems, credentials, or code.

## If you edit it

The page links `../style.css`; it has no styles of its own and should not
grow any. Keep the heading order, the back link, and the closing note about
what is unnamed and why — that note is what stops a reader assuming the gaps
are carelessness.
