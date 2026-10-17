# Box Art Zoom (beta)

Guess the game from its box art. Five rounds: a few pixels, then the release year, then the console and publisher, then a wider view, then the whole cover.

- Modern games: Meta Critical's list (OpenCritic top 500). Covers load from [Meta Critical's art folder](https://github.com/bobwulff/MetaCritical/tree/main/art); titles, years, consoles and publishers refresh from Meta Critical's published Google Sheet.
- Retro games: US box art from [libretro-thumbnails](https://github.com/libretro-thumbnails/libretro-thumbnails), publishers from [libretro-database](https://github.com/libretro/libretro-database) (checked by hand).
- Designed by Bob Wulff, coded by Claude

## Files

- `index.html` — the whole game (game list included)
- `packs/retro-0.json` … `retro-11.json` — retro box art, bundled
