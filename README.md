# zmk-config

This is a [ZMK](https://zmk.dev) config repo for my 34 key split keyboards, arranged in 3 rows of 5 columns with 2 thumb keys on each side. It uses three non-base layers activated through two thumb keys along with combos. It has <kbd>Ctrl</kbd>/<kbd>Shift</kbd> thumb hold-taps along with home row mods, which are also available on the left side of `NAV` layer. `FUN` layer is implemented as a tri-layer (active when both `NAV` and `SYM` are active).

OS-dependent shortcuts are present on the `NAV` layer, e.g. for Windows:
- `Win Close`: <kbd>Alt</kbd>+<kbd>F4</kbd>
- `Tab Next`: <kbd>Ctrl</kbd>+<kbd>Tab</kbd>
- `Tab Prev`: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Tab</kbd>
- `Tab Close`: <kbd>Ctrl</kbd>+<kbd>F4</kbd>
- `Desk Next`: <kbd>Ctrl</kbd>+<kbd>Gui</kbd>+<kbd>Right</kbd>
- `Desk Prev`: <kbd>Ctrl</kbd>+<kbd>Gui</kbd>+<kbd>Left</kbd>
- `Win Next`: <kbd>Alt</kbd>+<kbd>Tab</kbd> (hold Alt while layer active), not implemented in ZMK
- `Win Prev`: <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Tab</kbd> (hold Alt while layer active), not implemented in ZMK

![3x5+2 layout](https://caksoylar.github.io/zmk-config/3x5+2.full.svg)
(Visualization generated with [@caksoylar/keymap](https://github.com/caksoylar/keymap))

It also contains shield definitions for two keyboards using Pro Micro format daughterboards:
- [`choc_ergo`](https://keypcb.xyz/choc_ergo)
- [`hypergolic`](https://github.com/davidphilipbarr/hypergolic) -- you should probably use [the official Cradio shield](https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/cradio/) instead

Also see my [QMK userspace](https://github.com/caksoylar/qmk_userspace/) for equivalent keymap definitions for QMK.
