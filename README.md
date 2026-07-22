# Globe Tool

An interactive globe for creating background motion clips — built for designers to record smooth globe animations (spin, snap-to-location, intro/outro, 3D terrain) and drop them into prototypes.

It's a single self-contained web page. Open `index.html` in a modern browser (Chrome recommended) — no build step, no install.

## Live version

Once hosted, the tool is available at:
`https://<your-username>.github.io/globe-tool/`

## Features

- Rotating globe with adjustable speed and direction
- Smooth snap-to-location: search any place, presets, or lat/lng
- Intro / outro motion: scale-in (grow), slide-in, slide-out
- 3D tilted terrain view (Andes preset)
- Built-in recorder → exports an MP4 of the phone-framed composition
- iPhone frame sizes, star background, adjustable composition

## Map styles

- **Esri World Imagery** — free, no token, used by default.
- **Mapbox Satellite Streets** — optional. Requires your own Mapbox access token
  (get a free one at https://account.mapbox.com). Paste it into the Map style panel.
  Do not commit a token into this repo.

## Tech

Built on [MapLibre GL JS](https://maplibre.org/) (BSD-licensed). Imagery © Esri / Maxar,
or © Mapbox / Maxar when using the Mapbox style. Keep attribution visible.
