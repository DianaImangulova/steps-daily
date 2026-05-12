# Steps Daily

A lightweight walking route generator. Enter how many steps you have left to hit your daily goal and get a looped route from your location that matches the distance.

Just open the generator in a browser and start your walk!

**[→ Try it live](https://dianaimangulova.github.io/steps-daily)**

---

## How it works

1. Hit **Use my location** to set your start point
2. Enter your remaining steps
3. Pick your stride length
4. Hit **Find Route** — a looped walking route is plotted on the map
5. Not feeling it? Hit **Try Another Route** for a different shape

Routes cycle through six distinct shapes — triangle, square, rectangle, L-shape, pentagon, hexagon — each rotated randomly so you never get the same walk twice.

---

## Stack

- Vanilla HTML, CSS, JavaScript — no framework, no build step
- [Leaflet](https://leafletjs.com/) + [CartoDB](https://carto.com/) tiles for the map
- [OSRM](http://project-osrm.org/) for pedestrian routing on real streets
- Hosted on GitHub Pages

---

## Run locally

No build step needed. Just open the file:

```bash
git clone https://github.com/yourusername/steps-daily
cd steps-daily
open index.html
```

Note: geolocation requires a browser with location permissions enabled. If testing locally, you can also just click the map to set a custom start point (feature coming soon).

---

## License

MIT
