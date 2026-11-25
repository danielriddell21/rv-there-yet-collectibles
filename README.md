# RV There Yet? Collectibles

A collectibles tracker for *RV There Yet?* — every hat, pair of glasses and cassette tape, placed on a road-trip map at the checkpoint or stretch of road where you'll find it.

**Live:** https://danielriddell21.github.io/rv-there-yet-collectibles/

## Using it

Load your save to see which stops still have something for you: drop `PlayerProgression--1.sav` onto the page (or click to choose it). It lives at:

```
%LOCALAPPDATA%\Ride\Saved\SaveGames\<Steam ID>\
```

The save is read entirely in your browser and never uploaded.

## Development

It's a single static page (`index.html`) with no build step. Open it locally or serve the folder with any static server. GitHub Pages serves it from the `trunk` branch root.
