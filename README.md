# Metal Warfare

A run-and-gun sidescroller built from scratch on HTML5 Canvas with TypeScript: its own game loop, no game libraries, and five levels.

**Play online:** https://morys-new.github.io/My_Portofolio/projects/metal-warfare-v2/play.html

## Controls
| Action | Keys |
|---|---|
| Move | A / D or arrow keys |
| Jump | W or Space |
| Shoot | K, J, or X |
| Continue / restart | R or Enter |

## Run locally
The compiled game is already in `dist/game.js`, so you can open `Metal-Slug-Lite-main/play.html` directly in a browser.

To rebuild from the TypeScript source:
```
cd Metal-Slug-Lite-main
npm install
npm run build
```

## Project structure
```
Metal-Slug-Lite-main/
  src/game.ts     game source (TypeScript)
  dist/game.js    compiled output
  play.html       game page
  index.html      start screen
```

The first version was written in plain JavaScript and later rebuilt in TypeScript (v2) for cleaner code.

Built by [Mourrynes Pasa](https://morys-new.github.io/My_Portofolio/).
