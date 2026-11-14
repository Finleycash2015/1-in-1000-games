# 1 in 1000 Games — GitHub Pages upload folder

This repository holds the game site and has a `games/` folder for adding standalone HTML games. The built-in games are in `index.html`; extra game files are listed in `games/manifest.json`.

## Add a game

1. Upload your standalone `.html` game file into `games/`.
2. Edit `games/manifest.json` and add an entry like:

```json
{
  "games": [
    { "name": "My Game", "file": "my-game.html", "path": "games/my-game.html" }
  ]
}
```

3. Commit both the game file and manifest. If the game uses images, sounds, or scripts, upload those files too and keep their paths intact.

This repository is private. GitHub Pages publishing would make the site publicly available, so it has not been enabled. The unavailable old game archives are not included; add game files you have permission to use.
