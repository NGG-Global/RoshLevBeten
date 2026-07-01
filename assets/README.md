# assets

## body-map-human.png

The results screen (`index.html`) expects a transparent human-body PNG here:

```
assets/body-map-human.png
```

Guidelines for best alignment with the score gauges:

- **Transparent background** (PNG with alpha).
- **Portrait proportions close to 440 × 560** (the `.fig-wrap` aspect ratio).
  The figure is centered with `object-fit: contain`, so a matching ratio keeps
  the head / chest / abdomen aligned with the overlaid gauges.
- **Front-facing, vertically centered figure** on the image's central axis —
  the three gauges sit on that axis (head, upper chest, abdomen).

If the file is missing or fails to load, the page automatically falls back to a
neutral line-drawing figure, so the results screen never breaks.
