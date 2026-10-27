# 🧆 Falafel Run · Sverige

An interactive 3D road trip between ten of the best-rated falafel spots in Sweden, from Malmö to Umeå.
You get there by car, train, tram, tunnelbana, falafel van and, for the last leg, moose.

## Run it

Double-click `index.html`. That's it.

There's no Node and no build step. React 19 + TypeScript are compiled in the browser by Babel standalone.
Tailwind v4 runs from its browser build, and three.js + react-three-fiber load as ES modules from CDNs.
You need an internet connection for those CDNs.

Deep links:

- `index.html#stop=8` opens directly at stop 8
- `index.html#overview` shows the whole map

## Controls

- Drag to orbit, scroll to zoom
- Click a falafel pin, its label, or a row in the route list to drive there
- `←` / `→` drive to the previous or next stop, `O` toggles the overview, `Esc` closes the info panel

## Data

Stops, ratings and review summaries live in the `STOPS` array at the top of the script in `index.html`.
They were researched in Oct 2026, and every claim links to its source (Dagens PS, The Local, HappyCow,
Routes North, Spinach, Wanderlog, Time Out, Thatsup). Review lines are paraphrased, not quoted.
Pins with "pin placed at city level" have approximate coordinates. Opening hours change, so check before you go.
