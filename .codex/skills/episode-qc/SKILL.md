---
name: episode-qc
description: Perform the final cross-artifact quality gate for a short animated history episode before voice generation. Use to verify completeness, traceability, continuiчty, timing, rights notes, and handoff readiness; do not rewrite failed artifacts.
---

# Episode QC

Read every numbered episode artifact plus the series policies. Write
`12-final-qc.md`.

Verify:

- every factual narration sentence maps to approved claim IDs;
- the retention and visual reviews are approved;
- script, shot list, still prompts, motion prompts, and voice timing agree;
- every host shot follows the Character Bible;
- historical uncertainty is preserved;
- generated text is reserved for editing overlays;
- source, licensing, and synthetic-content notes are recorded when applicable;
- no required external still or clip is missing.

Start with `STATUS: APPROVED` only when the episode is ready for ElevenLabs.
Otherwise use `STATUS: REVISE`, identify the owning skill and exact artifact or
item ID, and define the acceptance test. Never fix another owner's artifact.
