# SynthMK-Web

The website for [SynthMK](https://github.com/GranusClarvis/SynthMK) — open-source
synthetic monitoring for Checkmk. Fully static (no build step, no framework),
served via GitHub Pages from `main`. All links are relative so the site works
under the `/SynthMK-Web/` subpath.

- `index.html` — landing: hero, three authoring paths, architecture diagram,
  persona feature grid, vs-Robotmk table, quickstart, downloads
- `authoring.html` — the three authoring paths in depth (record / visual builder / code)
- `enterprise.html` — security & operations model, scale evidence, residual-risk table
- `compare.html` — deep vs Robotmk, plus Datadog / Checkly / Grafana SM / Uptime Kuma framing
- `docs/` — install & usage documentation with sidebar navigation
- `css/site.css` — the entire design system (one file)
- `js/site.js` — mobile nav toggle + copy buttons (no dependencies)
- `assets/` — real screenshots captured from the SynthMK test lab

Grep for `TODO(v0.5` before publishing a release — those comments mark
v0.5 syntax details that must be verified against the shipped implementation.
