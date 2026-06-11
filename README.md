# io_scene_psk_psa (Fork)

A fork of [DarklightGames/io_scene_psk_psa](https://github.com/DarklightGames/io_scene_psk_psa).

> **⚠️ Not intended for general use.** This fork exists solely to import PSA animation files from *The First Descendant* (via umodel).

## Why this fork?

The original add-on has a hard block on missing bones — for a game like **TFD (The First Descendant)**, that's 4,000+ bones. Most are utility, hair, or compatibility bones we don't care about, but the original add-on prevents applying the animation to the armature regardless.

**This add-on bypasses that block and applies the animation.** That's all it does.

## Caveats

This version will probably **break under general use**. You can try it if you encounter similar issues with other game assets where extra bones block the PSA animation import.

## Roadmap

- [ ] Optional bone trim feature