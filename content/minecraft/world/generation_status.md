---
title: generation_status()
name: generation_status
signatures:
  - params:
      - name: pos
  - params:
      - name: pos
      - name: force_load
        type: bool
---

Returns generation status as per the ticket system. Can return any value from
several available but chunks can only be stable in a few states: `full`,
`features`, `liquid_carvers`, and `structure_starts`. Returns `null` if the
chunk is not in memory unless called with optional `true`.
