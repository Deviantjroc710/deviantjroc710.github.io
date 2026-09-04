# `collab-sorter/` — A mail triage service

**Live:** <https://mankowkorp.github.io/collab-sorter/>
**Linked from:** `/index.html` (card 1, At night)

## What this page claims

- Ranks roughly 350 collaboration pitches a week for one person, who uses it daily.
- Holds read-only mail access and cannot send; it drafts, she sends.
- The read-only path was chosen over an easier one that would have required the
  broadest mailbox permission available.
- Runs on a personal machine. No server, no account system. Message bodies are
  not retained after scoring.
- Ranking changes are measured against the full corpus, not against complaints.

Every number above is load-bearing. If one changes, change it here in the same
commit, and say where the new figure came from.

## Must not appear here

- The name of the person whose mailbox it reads, or anything identifying her.
- Real message content, real senders, real figures. The demo runs on invented data.
- Anything about the 24-day feed gap in 2026-08: the earlier draft blamed missing
  monitoring, which is **wrong** — she was not using it during that period. It is
  off the site deliberately.

Plus the repository-wide rules in [../README.md](../README.md) — no named
people, employer, industry, location, internal systems, credentials, or code.

## If you edit it

The page links `../style.css`; it has no styles of its own and should not
grow any. Keep the heading order, the back link, and the closing note about
what is unnamed and why — that note is what stops a reader assuming the gaps
are carelessness.

## One external dependency

Google's OAuth consent screen points its **Application home page** at this page,
and its privacy policy link at `/privacy.html`. Both must keep returning 200.
Renaming this folder breaks a Google configuration — update the console first.
