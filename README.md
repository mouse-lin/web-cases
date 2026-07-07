# web-cases

A running collection of standalone web design/UI case studies — landing pages, brand sites, and similar demo builds. Each case lives in its own folder and can be opened directly as a static site (no build step).

## Cases

| Case | Description |
|------|-------------|
| [`trajet-education-brand`](./trajet-education-brand) | Brand landing page for a fictional high-end study-abroad consultancy — Canvas 2D global-network hero engine, runtime light/dark theme switcher, scroll-driven motion (horizontal-pin gallery, 3D card fly-ins, curtain wipe, scan-line sweep) |

## Running a case locally

Each case is a self-contained static folder. Serve it with any static file server, e.g.:

```bash
cd trajet-education-brand
python3 -m http.server 8935
# open http://localhost:8935/index.html
```

## Notes

- These are design demos, not production sites — copy, names, and any "team" bios/testimonials are fictional placeholder content unless a case's own README says otherwise.
- Stock photography credit: [Unsplash](https://unsplash.com) (Unsplash License — free for commercial use). See each case's README for details.
