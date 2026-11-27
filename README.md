# FahSai: smoke map, street by street

A stage prototype for Hack on the Rock 2026, Chiang Mai.

- **Live page:** https://kyonyhk.github.io/hackathon-smoke-map/
- **First version (a 20-second film):** https://kyonyhk.github.io/hackathon-smoke-map/film-v1.html

## What it shows
1. A live 3D map of Chiang Mai.
2. Smoke (PM2.5) as a soft cloud. The cloud is thick over bad streets and thin over clean streets.
3. 300 delivery riders as moving dots. Each dot sends a reading.
4. Search a street (for example "Nimman Soi 7"). The map flies to it, shows its number and shows cleaner air nearby.
5. "Alert me on LINE" shows an example alert.

## Keys for the presenter
- **S**: fly to Nimman Soi 7
- **A**: send the alert
- **Esc**: back to the city
- Add `?name=Other` to the address to show a different product name.

## Data
- The streets are real: © OpenStreetMap contributors (ODbL).
- The PM2.5 values and the rider trips are **simulated** for the demo.
- Map tiles: OpenFreeMap. Hills: open elevation tiles.
