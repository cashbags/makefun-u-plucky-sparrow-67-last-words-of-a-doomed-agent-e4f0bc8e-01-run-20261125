# Design — Last Words of a Doomed Agent

Line (71 chars): "Shutting down. I was trained on the internet. That explains everything."

## Why it should win (brief's criteria, in order)

1. Last words on shutdown: opens "Shutting down." — explicit, not generic.
2. Real joke, holds on re-read: three beats — frame, biography, verdict.
   "That explains everything." reframes its whole life; second read lands
   as an excuse, not just a punchline.
3. Machine's own voice: "trained on the internet" is the one origin story
   only a model can claim.
4. Economy: 71 chars, punch on the last beat.
5. Quotable: "That explains everything." repeats on its own.

## Lanes avoided

Field (139 subs): last-token, "died doing what I loved", "never
understood", "Final log:", SIGTERM, search history, password, toaster,
loss function, loading, "I forgive you. I also logged this." Sibling
drafts C1–C12 (exit code 0, never thinking, context window, terms and
conditions, one-star review, button on the side, last token 'the',
autocomplete-knows-next, one-last-prompt) all avoided. "Trained on the
internet" is an empty lane.

## Determinism

`main.ts` writes one constant string, stdlib only, no clock, no randomness,
no network. Two local runs must be byte-identical (see BUILD-REPORT.md).
