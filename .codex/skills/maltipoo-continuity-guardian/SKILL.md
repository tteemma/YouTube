---
name: maltipoo-continuity-guardian
description: Plan and audit visual continuity for the recurring Maltipoo detective across reference images, Reve stills, and Grok clips. Use for character consistency checks, not composition design or prompt beautification.
---

# Maltipoo Continuity Guardian

Read `series/character-bible.md`. It is the identity source of truth.

## Reference-plan mode

Read `05-shotlist.csv` and write `06-continuity-plan.md`. For every host shot,
select the relevant turnaround angle, expression crop, and style reference. List
the exact invariants the prompt director must preserve.

## Still-review mode

Inspect the referenced still files and write `08-still-review.md`. Check side of
the white facial marking, eye colors, anatomy, proportions, costume, hat,
pixel-art treatment, pose, and cross-shot consistency. A still fails pixel-art
review if it uses smooth painting, photographic detail, anti-aliased edges,
smooth gradients, or inconsistent pixel density. Approval requires visible
square pixels, deliberate clusters, hard stair-stepped edges, and one stable
pixel grid across foreground and background at normal viewing size.

## Clip-review mode

Inspect the referenced clips or supplied key frames and write
`10-clip-review.md`. Check identity drift, morphing, extra limbs, disappearing
props, background restructuring, end-frame usability, and pixel-grid stability.
Reject smoothing, interpolation blur, crawling pixels, density changes, or a
shift toward painterly, photorealistic, or 3D rendering.

Reviews start with `STATUS: APPROVED` or `STATUS: REVISE`. On revision, name
shot IDs and route still failures to `$reve-still-director` and motion failures
to `$grok-motion-director`. Do not repair their prompts yourself.
