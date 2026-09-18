---
name: neon-dodge
description: A small touch-friendly arcade game that runs inside Google AI Edge Gallery. Move the player left and right to dodge falling blocks and survive as long as possible.
---

# Neon Dodge

Run this skill to open and play a small arcade game.

## Execution
Use the Edge Gallery JavaScript skill runner to load:
`bob/scripts/index.html`

The page is self-contained and needs no external libraries or network access.

The JavaScript bridge is:
`window["ai_edge_gallery_get_result"]`

When called, it returns a JSON status object. The game itself is played through the visible HTML UI.

## Game
- Drag or use the left/right buttons to move.
- Avoid the falling blocks.
- Score increases while you survive.
- Tap Restart after a collision.
