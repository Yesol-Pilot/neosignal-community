# NEOSIGNAL — community

Discussions for **[NEOSIGNAL](https://neosignal-ai.vercel.app/)**, which tracks every
AI model's price, context window and shutdown date and tells you what changed.

- **Site:** https://neosignal-ai.vercel.app/
- **Going away:** https://neosignal-ai.vercel.app/gone.html — announced shutdowns,
  plus models removed with no announcement at all
- **Free JSON:** https://neosignal-ai.vercel.app/api/models.json — no key, no signup
- **RSS:** https://neosignal-ai.vercel.app/feed.xml, or one feed per vendor
- **한국어:** https://neosignal-ai.vercel.app/ko/

This repository holds no code. It exists so the site can have a comment section
without asking anyone to make an account it doesn't already have.

## What to post

[Open a discussion](https://github.com/Yesol-Pilot/neosignal-community/discussions/new/choose)
for any of these:

- **A change we missed.** A price move, a context window change, a shutdown date
  that went out somewhere we aren't reading.
- **A source we should watch.** Right now this reads the OpenRouter catalog, a
  set of vendor feeds and status pages, and a short list of accounts. If something
  useful is published somewhere else, say so.
- **Something that broke** when a model was deprecated. That is the failure this
  exists to prevent, and the concrete stories are what tell us where the gaps are.

Threads and questions appear on the site's [community page](https://neosignal-ai.vercel.app/c/).

## What it reads

The catalog and vendor feeds are public metadata, checked once a day. Every change
is written to an append-only log, which is why each model page can show its own
history — that history only exists because something was watching on the day it
changed, and it cannot be backfilled.

Two honest limits, stated here rather than discovered later:

1. **It is not an independent source of truth.** If a vendor's own page is stale,
   this is stale in the same way. Verify before you migrate.
2. **The silent-removal list starts empty.** It only contains what was observed
   vanishing, so it fills as time passes rather than arriving complete.

## Who runs it

[Neo Genesis](mailto:help@neogenesis.app). Built and maintained with AI assistance;
the data is read from vendors, not generated.
