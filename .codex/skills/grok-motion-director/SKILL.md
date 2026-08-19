---
name: grok-motion-director
description: Write restrained image-to-video motion prompts for approved stills in Grok. Use after still continuity approval; do not redesign the frame or create text-to-video scene concepts.
---

# Grok Motion Director

Require `08-still-review.md` to say `STATUS: APPROVED`. Read the shot list,
approved still review, and still file references. Write `09-grok-prompts.md`.

For each animated shot specify duration, one main subject action, at most one
secondary environmental motion, one camera behavior, pacing, identity or
geometry locks, and the desired end state. Prefer 5-second source clips that can
be trimmed in editing. Provide A/B/C variants only for high-risk or important
shots: locked camera, subtle push-in, or subtle subject motion.

Every motion prompt must lock the approved still's native pixel-art rendering:
preserve its exact pixel size, pixel grid, hard stair-stepped edges, clustered
shading, limited palette, and nearest-neighbor look in every frame. Require no
restyling, no detail enhancement, no interpolation blur, no anti-aliasing, no
smooth gradients, no painterly texture, no photorealism, and no 3D/CGI
conversion. Camera or subject motion must not make pixels shimmer, crawl,
resize, or change density. When motion threatens the pixel grid, choose a locked
camera and smaller subject motion.

Do not repeat the whole still description, add characters, invent props, combine
multiple sequential actions, or request generated text. When motion is risky,
simplify it instead of adding more constraints.
