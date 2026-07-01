# assets

## body-map-human.png  (used by the app)

The results screen (`index.html`) loads the body graphic from:

```
assets/body-map-human.png
```

This file is a **transparent, web-optimized** version (760 × 967, alpha
background) of the uploaded source drawing. It was derived from the source
below by knocking the solid near-white background out to transparency — so the
figure sits cleanly on the dark results card — and downscaling for the web.

The three score gauges are drawn in code and overlaid on the figure's central
axis (head, chest, abdomen). Because the artwork's aspect ratio (~0.786) matches
the `.fig-wrap` container (440 × 560), the figure and gauges stay aligned.

If this file is missing or fails to load, the page automatically falls back to a
neutral line-drawing figure, so the results screen never breaks.

## file_00000000432c7243b0e47ae1c73a79f3.png  (source, unused by the app)

The original upload (1112 × 1415, opaque white background). Kept as the source
of truth in case the transparent version needs to be regenerated. Not referenced
by the app; safe to remove if you don't need the source.
