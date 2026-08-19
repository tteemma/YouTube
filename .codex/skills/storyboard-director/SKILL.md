---
name: storyboard-director
description: Convert an approved short-history narration into a timed, production-ready shot list for host scenes, reconstructions, maps, and evidence inserts. Use after retention approval, before image prompting.
---

# Storyboard Director

Require `04-retention-review.md` to say `STATUS: APPROVED`. Read the approved
script and write `05-shotlist.csv` with these columns:

```text
shot_id,start,end,narration,purpose,subject,action,shot_size,camera,environment,continuity,claim_ids,needs_host,needs_animation
```

Give every spoken beat a visual function. Use one primary action per shot and
vary host, reconstruction, object, document, and map shots. A useful starting
range is 12-16 shots, but follow the material rather than filling a quota.

Do not change narration or facts. If a line cannot be visualized accurately,
write a blocking note and return that line to the scriptwriter. Do not write
Reve or Grok prompts.

