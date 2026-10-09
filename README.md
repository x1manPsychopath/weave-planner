# Weave Route Planner

A fan-made team planner for **Fire Emblem: Fortune's Weave**.

**Use it:** https://x1manpsychopath.github.io/weave-planner/

## Features

- **Team Planner**: plan each Flame Lord's path (Cai, Dietrich, Theodora, Leda) plus the Part III timeskip. Set every unit's certification route, track who you've recruited, see Renown/Support recruitment gates, and count the licenses and special items a path needs.
- **Deploy**: pick who to field on a map and check coverage: weapon types, healers, ranged attackers, tank roles, fliers, chest openers. Save multiple named lineups per path.
- **Compare Units**: up to four units side by side in any class, with final growth rates.
- **Class Routes**: recommended route for all 63 characters, growth rates at each step, and recruitment requirements on every path.
- **Classes**: all 60 classes, sortable by growth modifier.

Plans are saved in your browser. Use **Copy plan code** / **Load code** in the Team Planner sidebar to move them between devices.

## Install as an app

- **Phone (Android/Chrome):** open the site, then menu → *Add to Home screen* / *Install app*.
- **iPhone (Safari):** Share → *Add to Home Screen*.
- **PC (Chrome/Edge):** click the install icon in the address bar, or the *Install app* button on the page.

After the first visit it works offline.

## Data sources

- Class data: [Marigold](https://marigoldfe.com/fortunes-weave/classes)
- Personal growth rates: [KeenGamer growth table](https://www.keengamer.com/articles/guides/fire-emblem-fortunes-weave-growth-rates-for-all-characters-and-classes/)
- Recommended class routes: [KeenGamer best-class guide](https://www.keengamer.com/articles/guides/fire-emblem-fortunes-weave-best-class-for-every-character/)
- Recruitment: [KeenGamer recruitment guide](https://www.keengamer.com/articles/guides/fire-emblem-fortunes-weave-all-characters-recruitment-guide/), cross-checked against [Marigold's planner](https://marigoldfe.com/fortunes-weave/planner)

## How it's built

A single `index.html` with no build step or dependencies (Google Fonts only). `sw.js` adds offline support and `manifest.webmanifest` makes it installable. The PNG icons are rendered from `icons/*.svg` by the GitHub Actions workflow on each push to `main`.

Fan-made tool. Not affiliated with Nintendo or Intelligent Systems. Fire Emblem and all related names are trademarks of their respective owners.
