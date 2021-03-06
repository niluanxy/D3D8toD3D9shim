# Supported Products

`
Add entries to this list if they run at all using the D3D8 to D3D9 shim and remain playable/usable without crashing (crashes are okay if you note them as known issues and they either have good workarounds or are not required to get the full playability/usability out of the product).
`

- Advent Rising (2005)
- The Elder Scrolls III: Morrowind (2002)
- Unreal II: The Awakening (2003)
- Unreal Tournament 2004 (2004)

# Known Issues

## Advent Rising (2005)

No known issues for this game.

## The Elder Scrolls III: Morrowind (2002)

- ~~In the inventory, your character's paper doll model is rendered semitransparently where it shouldn't be, and the background is red instead of black~~
  - Fixed in [this commit](https://github.com/code-tom-code/D3D8toD3D9shim/commit/1362e8f7c4c4cff8920943c41d6e21d7462cf052#diff-645ba7daff8853ad6961c42181db1579).
- ~~The minimap renders all black in "local map" mode, but the map does render correctly in "world map" mode~~
  - Fixed in [this commit](https://github.com/code-tom-code/D3D8toD3D9shim/commit/1362e8f7c4c4cff8920943c41d6e21d7462cf052#diff-645ba7daff8853ad6961c42181db1579).

## Unreal II: The Awakening (2003)

- ~~Character shadows seem to flicker (looks like some sort of Z or Stencil fighting).~~
  - Fixed with [this commit](https://github.com/code-tom-code/D3D8toD3D9shim/commit/d5c4db265d6afd99274b3ca88de5f9aa8b419f3d#diff-645ba7daff8853ad6961c42181db1579).
- Crash in game when changing resolutions.
  - Workaround: You can simply set the desired resolution without the shim, and the game will remember that resolution the next time you load up the game with the shim again.

## Unreal Tournament 2004 (2004)

No known issues for this game.
