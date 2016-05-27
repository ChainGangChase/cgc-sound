# cgc-sound
_____
This repo contains the source sound for the game. The [ChainGangChase/game](https://github.com/ChainGangChase/game) project build scripts will reference the files from `/package/assets` when building the game.

### Project Overview
```
/
assets/.............source sounds, raw files, multitracks, whatever
package/assets/.....................built textures and .atlas files
package.json...................................for import using npm
```

### Usage
Make sure the final files you want to include in the game are in the `/package/assets` directory and that a release including them has been tagged.

### Changelog
**v0.1.0**
- first version!
- package.json
