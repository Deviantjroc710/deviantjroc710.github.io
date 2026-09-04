# `migration/` — A migration with no undo

**Live:** <https://mankowkorp.github.io/migration/>
**Linked from:** `/index.html` (card 1, During the day)

## What this page claims

- 91,649 tickets, 254,574 comments, ~99,000 attachments, 31 GB moved.
- Source access ended on a fixed date and nothing could be re-fetched after it.
- Extraction was cursor-based, checkpointed, and resumable.
- A long run once produced nothing usable because a checkpoint was written in
  one shape and read in another; checkpoints are now versioned and validated.
- Reconciled against the source **before** access closed: zero tickets missing.

Every number above is load-bearing. If one changes, change it here in the same
commit, and say where the new figure came from.

## Must not appear here

- The vendors on either side of the migration, and the function whose data it was.
- The organisation, and anything that narrows it.

Plus the repository-wide rules in [../README.md](../README.md) — no named
people, employer, industry, location, internal systems, credentials, or code.

## If you edit it

The page links `../style.css`; it has no styles of its own and should not
grow any. Keep the heading order, the back link, and the closing note about
what is unnamed and why — that note is what stops a reader assuming the gaps
are carelessness.
