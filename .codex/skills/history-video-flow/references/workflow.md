# Workflow state machine

| State | Skill | Advance condition |
|---|---|---|
| `topic_draft` | `$episode-topic-scout` | brief has one approved angle |
| `research` | `$historical-researcher` | claim ledger and source notes exist |
| `fact_check` | `$historical-fact-checker` | all script-eligible claims approved |
| `script` | `$short-history-scriptwriter` | every factual sentence maps to claim IDs |
| `retention_review` | `$retention-script-editor` | review says `APPROVED` |
| `storyboard` | `$storyboard-director` | every spoken beat has a shot |
| `continuity_plan` | `$maltipoo-continuity-guardian` | each host shot has reference instructions |
| `reve_prompts` | `$reve-still-director` | every shot has a still prompt |
| `awaiting_stills` | human/Reve | referenced still files exist |
| `still_review` | `$maltipoo-continuity-guardian` | review says `APPROVED` |
| `grok_prompts` | `$grok-motion-director` | each animated shot has a motion prompt |
| `awaiting_clips` | human/Grok | referenced clip files exist |
| `clip_review` | `$maltipoo-continuity-guardian` | review says `APPROVED` |
| `voice_handoff` | `$voice-handoff-editor` | timing and pronunciation package exists |
| `final_qc` | `$episode-qc` | report says `APPROVED` |
| `ready_for_voice` | none | terminal state for this flow |

At each transition update `episode.yaml`: `current_stage`, `stage_status`,
`blocker`, `next_owner`, and `next_action`.

