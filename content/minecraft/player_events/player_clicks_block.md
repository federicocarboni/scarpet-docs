---
params:
  - name: player
  - name: block
  - name: face
name: __on_player_clicks_block
title: player_clicks_block
---

Representing left-click attack on a block, usually signifying start of breaking
of a block. Triggers right after the server receives a client packet, before
anything happens on the server side.

This event can be cancelled by returning `'cancel'`, which stops the player from
breaking a block.
