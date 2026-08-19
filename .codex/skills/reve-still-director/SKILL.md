---
name: reve-still-director
description: Write shot-specific Reve image prompts from an approved storyboard and continuity plan. Use for still-frame direction only, not historical research, animation motion, or final text overlays.
---

# Reve Still Director

Read `05-shotlist.csv`, `06-continuity-plan.md`, `series/character-bible.md`, and
`series/visual-bible.md`. Write `07-reve-prompts.md`, one block per shot.

Each prompt specifies reference responsibilities, 9:16 framing, subject, one
visible action, period environment, composition, camera angle, lighting, mood,
pixel-art treatment, continuity locks, and safe space for captions. Use additive
descriptions. Generated text, dates, labels, arrows, and subtitles are excluded
and must be added in editing.

## Pixel-art lock

Every individual shot prompt must be self-contained and include the strict
pixel-art requirements from `series/visual-bible.md`; never rely on a shared
heading such as "all shots are pixel art." Require visible square pixels, a
single stable pixel grid, hard stair-stepped edges, clustered shading, limited
color ramps, pixel dithering, and nearest-neighbor enlargement. Explicitly
exclude anti-aliasing, smooth gradients, painterly or photographic texture,
photorealism, 3D/CGI, and vector-smooth rendering.

Use `data/Maltipoo _ More Pixelated 1.png` as the style authority for every
shot. For host shots, also assign the turnaround and expression sheet as
identity references. For no-host shots, use the pixelated image only when Reve
allows style-only reference behavior; if the reference is literal-only, omit it
and carry the complete pixel-art lock in text so the Maltipoo is not copied into
the scene.

Reject and rewrite a prompt if its result could plausibly be a smooth digital
painting viewed at full size. A valid result must show intentional pixel
clusters at normal viewing size, including in faces, hands, props, shadows, and
backgrounds.

For host shots, distinguish anatomical left/right and restate only the identity
features at risk. For historical reconstructions, use only visual details
supported by approved claims or research notes. Do not describe motion through
time and do not change the shot list.
