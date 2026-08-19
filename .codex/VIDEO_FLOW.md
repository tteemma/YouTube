# Production flow

This project turns one approved historical idea into a prompt-complete animated
Short that is ready for voice generation. Invoke `$history-video-flow` to run
the whole process or invoke a specialist skill for a single stage.

```text
topic scout
  -> historical researcher
  -> historical fact-checker
  -> short-history scriptwriter
  -> retention script editor
  -> storyboard director
  -> Maltipoo continuity guardian (reference plan)
  -> Reve still director
  -> [human generates stills in Reve]
  -> Maltipoo continuity guardian (still review)
  -> Grok motion director
  -> [human generates clips in Grok]
  -> Maltipoo continuity guardian (clip review)
  -> voice handoff editor
  -> episode QC
```

## Ownership

| Stage | Owner | Required output |
|---|---|---|
| Topic | `episode-topic-scout` | `00-brief.md` |
| Research | `historical-researcher` | `01-research.md`, `01-claims.jsonl` |
| Verification | `historical-fact-checker` | `02-fact-check.md`, `02-approved-claims.jsonl` |
| Script | `short-history-scriptwriter` | `03-script.md` |
| Retention | `retention-script-editor` | `04-retention-review.md` |
| Storyboard | `storyboard-director` | `05-shotlist.csv` |
| Reference plan | `maltipoo-continuity-guardian` | `06-continuity-plan.md` |
| Still prompts | `reve-still-director` | `07-reve-prompts.md` |
| Still review | `maltipoo-continuity-guardian` | `08-still-review.md` |
| Motion prompts | `grok-motion-director` | `09-grok-prompts.md` |
| Clip review | `maltipoo-continuity-guardian` | `10-clip-review.md` |
| Voice package | `voice-handoff-editor` | `11-voice-handoff.md` |
| Final review | `episode-qc` | `12-final-qc.md` |

## Rework routes

- Unsupported or disputed claim -> `historical-researcher`, then fact-check again.
- Weak hook, pacing, or payoff -> `short-history-scriptwriter`, then retention review again.
- Unfilmable script line -> storyboard reports it; scriptwriter revises only that line.
- Wrong character in a still -> `reve-still-director` revises that shot prompt.
- Wrong character or geometry in a clip -> `grok-motion-director` simplifies that motion.
- Final QC failure -> return only to the owner of the failed artifact.

No downstream agent may silently repair an upstream artifact. It must record the
problem and route it back to the owner.

