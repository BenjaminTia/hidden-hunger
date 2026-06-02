# Hidden Hunger

A narrative-driven decision survival game built as a single-page HTML application. Experience the reality of living under an controlling guardian's roof — where every meal is a risk, every hiding spot matters, and survival is a daily strategy game.

**Play it here:** [benjamintia.github.io/hidden-hunger](https://benjamintia.github.io/hidden-hunger)

---

## Overview

You live with your aunt. Every day is a battle — for food, for privacy, for your sanity. She controls everything you eat, wear, and do. The only peace you get is at night, when she's finally asleep.

Manage your stats, hide your food, dispose of evidence, and find a way out before she breaks you completely.

## Features

- **Stat-driven survival** — Track Hunger, Bladder, Health, Suspicion, Money, Strength, and Trash. Every choice has consequences.
- **Multi-step decision chains** — Events unfold over 3-6+ choices, each with odds and trade-offs. Not a simple click-through.
- **Trash management** — Eating generates trash. Hide it in various spots (under the bed, in the closet, behind the desk) with different discovery risks. Get caught and suspicion skyrockets.
- **Food stash** — Buy food at the convenience store and hide it in your room. Eat from your stash when you're desperate or when she's distracted.
- **Time cycle** — Morning → Afternoon → Evening → Night. Night is your only safe window when she's asleep.
- **24 unique endings** — From quiet escape to grim outcomes. Every playthrough is different.
- **20+ unique events** — Each is a specific narrative incident with branching paths, not a repetitive routine.
- **No WASD movement** — Pure narrative choice mechanics with probability odds displayed on each option.

## Stats

| Stat | Range | Description |
|------|-------|-------------|
| Hunger | 0-100 | Starvation at 0. Eat to survive. |
| Bladder | 0-100 | Infection risk at 100. Use the bathroom. |
| Health | 0-100 | Reaches 0 and you're done. |
| Suspicion | 0-100 | At 100, she kicks you out. |
| Money | $0+ | Save $500 to escape. |
| Strength | 1+ | Gain at the gym. Reach 40+ to unlock endings. |
| Stash | 0+ | Food you've bought and hidden. |
| Trash | 0-10 | Evidence of eating. Must be hidden or disposed of. |

## Gameplay Tips

- **Night is your friend** — She's asleep. This is when you can sneak to the kitchen, eat from your stash, or dispose of trash outside.
- **The gym → store loop** — Work out, then stop at the convenience store on the way back. Stock up while she thinks you're exercising.
- **Hide trash wisely** — Behind the desk is safest (12% discovery). Under the bed is riskier (25%). In your bag is a trap (40%).
- **Save money** — $500 lets you escape. But you'll need to spend on food too. Balance is everything.
- **Build strength** — At 25+ strength with high suspicion after day 20, new paths open.
- **Scholarship is escape** — Study when you can. The library is safer than home.
- **Dispose of trash outside** — If you can get out without waking her, dump everything in the outside bin. Zero risk.

## Endings

24 endings across multiple categories:

- **Death endings** — Starvation, bladder infection, broken body
- **Escape endings** — Runaway, scholarship, independent, moved out
- **Justice endings** — Aunt arrested, truth out, someone believed
- **Growth endings** — Strong enough, self-sufficient, therapy journey
- **Connection endings** — New family, friends saved me, someone believed
- **Grim endings** — The Act (caught, freedom, cover-up, self-defense)
- **Peace endings** — Survived 100 days, peace at last, confrontation

## How to Run

Simply open `game.html` in any modern web browser. No server, no dependencies, no installation required.

```bash
# Clone the repo
git clone https://github.com/BenjaminTia/hidden-hunger.git

# Open the game
cd hidden-hunger
open game.html
```

Or play directly on GitHub Pages: [benjamintia.github.io/hidden-hunger](https://benjamintia.github.io/hidden-hunger)

## Technical

- **Stack:** Pure HTML + CSS + JavaScript (no frameworks, no libraries)
- **File size:** Single ~50KB HTML file
- **Compatibility:** Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **Hosting:** Ready for GitHub Pages — just push and enable

## Disclaimer

This is a work of fiction. Names, characters, places, and incidents are either products of the imagination or used fictitiously. Any resemblance to actual persons, living or dead, events, or locales is entirely coincidental. The story explores themes of family dysfunction, manipulation, and survival. Reader discretion is advised.

---

Built with JavaScript. One file. No dependencies.
