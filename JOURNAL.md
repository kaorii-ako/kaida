# Journal

## 2026-07-20

Started laying out the keyboard in KLE (Keyboard Layout Editor)[https://www.keyboard-layout-editor.com/] JSON format — `keyboard-layout.json`. Went with a TKL-ish arrangement but kept a dedicated arrow cluster and a lone `Del` key up top instead of going full 96%.

A few things I settled on:

- Split the F-row into groups of 4 with `0.25u` gaps (F1 | F2-F4 | F5-F8 | F9-F12 | Del) — matches the standard ANSI spacing so stock keycap sets still line up.
- Stacked the arrow cluster instead of using the usual inverted-T: `↑` sits alone on its own row above `← ↓ →`, both offset with negative `y` so they nest into the right side of the board without needing a full extra column.
- `1.75u` Caps Lock, `2.25u` Enter, `2.25u`/`1.75u` split Shifts, `2u` Backspace — pretty standard ANSI stagger, wanted to keep it compatible with common aftermarket keycap kits.
- Bottom row is `1.25u` Ctrl/Win/Alt with a `6.25u` spacebar, using the `a: 7` / `a: 4` alignment flags so the blockers on either side of the spacebar render correctly in KLE.
- Tagged the top-left keys with `sm: cherry` (Cherry-profile stepped modifier) as a placeholder — still need to decide if I'm sculpting the mods or leaving them uniform.

Next up: figure out the actual PCB footprint spacing so this layout maps cleanly to switch positions, and start looking at plate material options.

Time: ~27 min, designing the layout in KLE.
