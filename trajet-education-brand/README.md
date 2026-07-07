# 轨迹 TRAJET — Education Brand Landing Page

A brand landing page demo for a fictional high-end study-abroad / admissions-consulting company, built with the [finesse-ui](https://github.com/mouse-lin/finesse-skill) design skill.

## Preview

```bash
python3 -m http.server 8935
# open http://localhost:8935/index.html
```

## Highlights

- **Hero engine** — Canvas 2D abstract "global admission network": a live constellation of arcs connecting a central node to named partner universities, with traveling light pulses and pointer-parallax.
- **Runtime theme switcher** — 5 fully coordinated themes (bg/surface/ink/accent all move together, not just a recolored highlight): 2 light registers (ivory, platinum) + 3 dark jewel-tones (brass, sapphire, wine). Default is the light ivory + rust theme.
- **Scroll motion** — sticky-rail process steps, horizontal-pin campus gallery with per-card fly-in, 3D-tilt team card entrances, a curtain-wipe reveal, an accent scan-line sweep across the data section, split-character heading reveals, and magnetic CTA buttons.
- Fully respects `prefers-reduced-motion` (every animated element freezes/hides rather than half-playing).

## Content disclaimer

This is a **design demo**, not a real business. All copy is fictional:
- The brand name "TRAJET / 轨迹", its team member names (陈廷, 林薇, 周景行), bios, testimonial, and case-distribution stats are made up for demonstration purposes.
- The 3 "advisor" headshots in `images/` are real stock photographs of real people, used here only as generic placeholder portraits — they are not actually employed by, or in any way affiliated with, this fictional brand. **Swap these before ever using this template for a real, publicly-facing site.**

## Image credits

All photography in `images/` is sourced from [Unsplash](https://unsplash.com) under the [Unsplash License](https://unsplash.com/license) (free for commercial use, no attribution required). Listed here anyway for transparency:

| File | Unsplash photo ID |
|------|--------------------|
| `campus-heritage.jpg` | photo-1591019052241-e4d95a5dc3fc |
| `gallery-us-ivy.jpg` | photo-1780817612650-4b4569f0a00b |
| `gallery-uk-gothic.jpg` | photo-1774214458548-06dc5dc5237b |
| `gallery-library-modern.jpg` | photo-1764213077313-41b4dc822d8c |
| `gallery-library-historic.jpg` | photo-1741699428519-d43b778f4d3c |
| `gallery-asia.jpg` | photo-1773640692786-70e944f64129 |
| `advisor-chen.jpg` | photo-1652471943570-f3590a4e52ed |
| `advisor-lin.jpg` | photo-1701096374092-bb70915fdc5c |
| `advisor-zhou.jpg` | photo-1600878459138-e1123b37cb30 |

## Stack

Single self-contained `index.html` — vanilla JS, GSAP + ScrollTrigger (CDN), Google Fonts (Petrona / Hanken Grotesk / JetBrains Mono). No build step, no dependencies to install.
