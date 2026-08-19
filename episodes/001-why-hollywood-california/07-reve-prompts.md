# Reve still prompts — strict pixel-art revision

## Как использовать

- Генерировать каждый Shot ID отдельно в режиме Create, не пытаться
  превращать уже получившуюся гладкую картинку через Edit.
- Формат каждого кадра: 9:16, итоговый файл 1080x1920.
- Для S01, S04, S09 и S12 приложить turnaround, expression sheet и final
  pixel-art reference. Turnaround отвечает за анатомию и костюм, expression
  sheet — за эмоцию, pixel-art reference — за фактуру, палитру и свет.
- Для кадров без ведущего использовать final pixel-art reference только в
  style-only режиме. Если Reve предлагает только Literal, не прикладывать его:
  полный стилевой lock уже встроен в каждый промпт и не даст скопировать
  Мальтипу в историческую сцену.
- Сохранять выбранные результаты как `stills/S01.png` ... `stills/S12.png`.

## S01 — вопрос на карте

**References:** все три референса Мальтипу.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Medium frontal three-quarter shot inside a historical detective archive office. The recurring anthropomorphic brown Maltipoo detective wears the same black fedora, brown three-piece suit, white shirt, black tie, and black shoes as the references. Compact body, oversized head, floppy ears, rounded muzzle, black nose. His anatomical left eye is blue; the white marking surrounds that anatomical left eye and continues down the anatomical left cheek. His anatomical right eye is brown. Do not mirror these features. He uses one paw to trace one red thread across a large old map of the United States. Curious focused expression, warm desk lamp, dark wood, evidence board. Keep the upper third visually clean for an editor-added caption. No readable text, dates, labels, logos, arrows, or subtitles. Every face, paw, thread, map edge, shadow, and background object must use the same visible pixel size and grid.
```

## S02 — рождение MPPC

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Close overhead view of a 1908 archive desk. Two neutral old corporate folders lie beside one sealed central folder; a brass seal, fountain pen, and early film reel sit nearby. One visible action only: two historically dressed human hands place the two outer folders beside the central folder. Warm desk-lamp light, dramatic blocky shadows, clean upper area for an editor-added caption. No dog, no detective, no character from the style reference. No readable words, dates, logos, arrows, or subtitles. Hands, paper fibers, film reel, lamp light, desk grain, and shadows must all be constructed from crisp pixel clusters on the same grid.
```

## S03 — сеть лицензий

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Top-down evidence board on a dark charcoal surface. One neutral central seal is connected by tidy red threads to an early hand-cranked movie camera, a film reel, and a simple cinema screen. One visible action only: one thread is being stretched between the seal and the camera. Ordered but oppressive composition, amber pool of light, clean lower quarter for an editor-added caption. No dog or detective. No text, letters, dates, logos, arrows, or subtitles. All thread curves, object contours, highlights, and shadows use hard pixel steps and the same visible pixel density.
```

## S04 — независимый источник

**References:** все три референса Мальтипу.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Medium close-up in the detective archive, character viewed from his right three-quarter angle. The same recurring brown Maltipoo detective opens one plain unlabelled film box with one paw. Preserve the reference anatomy: compact body, oversized head, floppy ears, rounded muzzle, black nose, black fedora, brown three-piece suit, white shirt, black tie, black shoes. Anatomical left eye blue with the white marking around it and down the anatomical left cheek; anatomical right eye brown; never mirror them. Attentive expression, warm lamp, dark wooden desk, clean upper third for a caption. No box markings, readable text, dates, logos, or subtitles. Fur curls, face, paw, box, wood, light, and shadows all share one crisp visible pixel grid.
```

## S05 — зимняя площадка

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Wide historical reconstruction of an outdoor film set in the northeastern United States in the early 1910s during cold winter weather. A simple hand-cranked movie camera stands on a wooden tripod; several technicians wear restrained period winter clothing; a large reflector tilts in the wind. One visible action only: one technician holds the reflector steady. Snow at the set edges, dull winter light, cold blue-gray pixel shadows with a restrained amber accent, clean upper area for an editor-added caption. No dog or detective, no modern equipment, no text or logos. Snow, faces, fabric, camera, sky, and shadows must all use the same coarse intentional pixel clusters.
```

## S06 — уходящий свет

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Wide locked view of an early outdoor movie set in winter: wooden tripod camera, small period set wall, and long dark shadows already covering the working area. One visible action only: the camera operator lowers both hands away from the camera as preparation stops. Low pale sun behind blocky dithered clouds, short cold day, clean upper third for an editor-added caption. No dog or detective, no readable text, clocks, dates, logos, or subtitles. The sky is made from stepped pixel bands and dithering, never a smooth gradient; all objects use the same pixel density.
```

## S07 — карта преимуществ

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Top-down artistic parchment map of Southern California without labels. Four nearby natural zones are visually distinct: coast with one wave, sandy desert, green hills, and distant mountains. A thin neutral route line connects the zones; a tiny early movie-camera token rests on the line. Warm desk-lamp illumination, paper texture built from blocky pixel clusters, clean lower quarter for an editor-added caption. No dog or detective, no words, dates, labels, arrows, borders, or logos. Coast, sand, hills, mountains, route, paper grain, and shadows all follow one visible pixel grid.
```

## S08 — смена мира фильма

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Wide sunny historical reconstruction of an early Southern California film location. Foreground: a hand-cranked camera and a simple beach set. Behind it, sandy hills and a mountain silhouette clearly show several nearby landscape types. One visible action only: an operator places the camera onto its wooden tripod. Clear warm sunlight represented with stepped color ramps and dithered pixel shadows, optimistic restrained amber palette, clean upper third for an editor-added caption. Period-neutral clothing, no dog or detective, no modern equipment, no text or logos. Every person, landscape edge, cloud, prop, and shadow shares one coarse crisp pixel grid.
```

## S09 — три причины

**References:** все три референса Мальтипу.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Medium shot at a detective evidence desk, recurring Maltipoo detective viewed from his anatomical left three-quarter side. He uses one paw to place three neutral clues beside one another: a closed unlabelled patent folder, a small abstract sunlight token, and a landscape photograph without text. Preserve the exact reference identity and costume: compact brown Maltipoo, oversized head, black fedora, brown three-piece suit, white shirt, black tie, black shoes; anatomical left eye blue with the white marking around it and down the left cheek, anatomical right eye brown. Analytical expression, warm light, clean upper third for a caption. No chase, no readable words, dates, logos, arrows, or subtitles. Character, fur, clues, desk, and lighting all use the same visible square pixels and hard clustered shading.
```

## S10 — сходящиеся факторы

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Close top-down view of a charcoal evidence board. Three objects — one neutral unlabelled folder, one small abstract sunlight token, and one landscape photograph — are connected by three red threads to a tiny anonymous early movie-studio model. One visible action only: the end of one thread touches the studio model. Clear uncluttered composition, amber light, clean lower quarter for an editor-added caption. No dog or detective, no words, dates, labels, logos, arrows, or subtitles. Threads, objects, board texture, highlights, and shadows must be built from crisp blocks on one visible pixel grid.
```

## S11 — концентрация студий

**References:** final pixel-art reference только как style-only; при Literal-only генерировать без изображения-референса.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Wide historical parchment map of Southern California with no geographic labels. Several simple anonymous markers shaped like early studio buildings cluster near the coast and hills; tiny silhouettes of early cameras and filming canopies sit farther away. One visible action only: one new studio marker has just been placed on the map. Restrained palette, warm light, clean upper third for an editor-added caption. No dog or detective, no company names, dates, words, borders, logos, arrows, or subtitles. Map grain, coastline, hills, buildings, cameras, and shadows all share the same crisp visible pixel size.
```

## S12 — закрытое дело

**References:** все три референса Мальтипу.

**Prompt:**

```text
STRICT NATIVE PIXEL ART, vertical 9:16. Render as a 180x320 logical pixel canvas enlarged exactly 6x with nearest-neighbor scaling to 1080x1920. Clearly visible square pixels at normal viewing size, one consistent pixel grid across the whole frame, hard stair-stepped silhouettes, deliberate blocky pixel clusters, limited brown/amber/charcoal/parchment color ramps, and pixel dithering instead of smooth gradients. No anti-aliasing, no smooth shading, no painterly brushwork, no photographic micro-detail, no photorealism, no 3D or CGI, no vector-smooth edges.

Medium frontal three-quarter shot in the detective archive at sunset. The same recurring Maltipoo detective closes one thin unlabelled case folder with one paw and looks toward an illuminated map. Preserve exact reference identity: compact brown Maltipoo, oversized head, floppy ears, rounded muzzle, black nose, black fedora, brown three-piece suit, white shirt, black tie, black shoes. Anatomical left eye blue; white marking around the anatomical left eye continuing down the anatomical left cheek; anatomical right eye brown; never mirror them. Calm satisfied expression, warm amber sunset light, dark wooden desk, clean upper third for an editor-added caption. No readable text, dates, logos, arrows, or subtitles. Fur, face, costume, folder, map, sunset, and shadows all use the same crisp square pixels and stable grid.
```

## Acceptance test before Grok

A still is acceptable only when square pixels and deliberate pixel clusters are
clearly visible at normal 100% viewing size in both foreground and background.
If skin, paper, sky, light, or shadows look smoothly painted, the shot is
`REVISE` even when the composition is otherwise correct.
