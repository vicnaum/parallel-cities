# Parallel Cities

An interactive world map for comparing cities that sit on the same latitude.

Click or drag across the map to move the selected parallel. The app shows the latitude in degrees, draws the selected parallel in red, and mirrors it as a dashed line in the opposite hemisphere. Nearby cities are highlighted, with extra tolerance for very large cities so major places like Tokyo and Los Angeles are easier to notice.

## Run Locally

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000/`.

## Files

- `index.html` - Canvas UI and interaction logic.
- `world-110m.geojson` - Natural Earth country geometry.
- `world-cities-50m.geojson` - Natural Earth populated places.
