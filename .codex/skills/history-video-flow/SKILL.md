---
name: history-video-flow
description: Coordinate the complete production flow for a short animated history episode, from topic selection through Reve still prompts, Grok motion prompts, and an ElevenLabs-ready voice handoff. Use when the user wants to create, continue, or audit a full episode rather than one isolated production stage.
---

# History Video Flow

Coordinate the specialist skills without taking over their creative work.

## Start

Read [references/workflow.md](references/workflow.md) and
[references/episode-contract.md](references/episode-contract.md). Also read
`series/editorial-policy.md` and `series/character-bible.md` when present.

For a new episode, create `episodes/<episode-id>-<slug>/` from the files in
`assets/episode-template/`. Ask for a topic only when the user did not provide
one; otherwise proceed with the supplied topic.

## Coordination rules

- Run stages in the workflow order and verify each required artifact exists.
- A review stage either writes `APPROVED` or returns actionable findings to the
  artifact owner. Do not let reviewers rewrite the artifact they review.
- Never let script prose introduce a claim absent from
  `02-approved-claims.jsonl`.
- Stop at external Reve or Grok generation only when the required media files
  are not available. Preserve the exact next action in `episode.yaml`.
- End at the ElevenLabs-ready handoff; do not generate the final voice.
- Keep one source of truth per artifact. Do not create alternative final files.

