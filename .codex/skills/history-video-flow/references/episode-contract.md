# Episode contract

All episode artifacts live in one directory. File names are stable so each
specialist can discover its inputs without conversation history.

## Invariants

- `02-approved-claims.jsonl` is the only factual source for the script.
- `03-script.md` is the only narration source for the shot list and voice handoff.
- `05-shotlist.csv` is the only shot-order source for prompt directors.
- `series/character-bible.md` is the only source for Maltipoo identity rules.
- Generated text, labels, dates, and subtitles are editor overlays, not part of
  AI-generated stills or clips.

## Approval language

Review files start with exactly one of:

```text
STATUS: APPROVED
STATUS: REVISE
STATUS: BLOCKED
```

`REVISE` must identify the artifact owner, exact item IDs, and acceptance test.
`BLOCKED` is reserved for missing user input or unavailable external media.

