# FahSai: smoke map, street by street

A stage prototype for Hack on the Rock 2026, Chiang Mai.

- **Live page:** https://kyonyhk.github.io/hackathon-smoke-map/
- **First version (a 20-second film):** https://kyonyhk.github.io/hackathon-smoke-map/film-v1.html

## What it shows
1. A live 3D map of Chiang Mai.
2. Smoke (PM2.5) as a soft cloud. The cloud is thick over bad streets and thin over clean streets.
3. 300 delivery riders as moving dots. They do real delivery trips: they wait at food areas, then ride the fastest route to a home.
4. Live readings: a rider's street lights up when the rider sends a reading, and the list on the left shows the newest readings.
5. Search a street (for example "Nimman Soi 7"). The map flies to it, shows its number and shows cleaner air nearby.
6. "Clean route from here": choose a place, and the map draws the fastest route (red) and the clean route (green).
7. "Alert me on LINE" and "Send route to LINE" show example alerts.
8. Thai / English switch at the top right.

## Keys for the presenter
- **S**: fly to Nimman Soi 7
- **R**: clean route to Tha Phae Gate
- **A**: send the alert
- **L**: switch Thai / English
- **Esc**: back to the city
- Add `?name=Other` to the address to show a different product name.
- The riders move at real speed. Add `?speed=3` to the address to make them 3 times faster.

## Data
- The streets are real: © OpenStreetMap contributors (ODbL).
- The PM2.5 values and the rider trips are **simulated** for the demo.
- Map tiles: OpenFreeMap. Hills: open elevation tiles.
