# Magic Layer Alt-Tab
Activate a layer of your choice (e.g. with `MO` or `LT`) and then press one of the <kbd>Alt</kbd>-<kbd>Tab</kbd> keys.

Only while you are on that layer, and only after you press one of the two <kbd>Alt</kbd>-<kbd>Tab</kbd> keys, will <kbd>Alt</kbd> be held.

* `LALT(KC_TAB)` will tap `KC_TAB`

* `LSA(KC_TAB)` will tap `S(KC_TAB)`

When you leave said layer, or press another key on that layer, <kbd>Alt</kbd> will be released.

## Installation
1. Follow [**the steps described in the parent README**](../README.md) to add this repository to your QMK or userspace, and this module to your `keyboard.json`.
1. Choose a layer in your keymap. Add `LALT(KC_TAB)` and/or `LSA(KC_TAB)` to it.
1. Add `#define MAGIC_LAYER_ALT_TAB_LAYER ` plus the layer to your `config.h`. (e.g. `#define MAGIC_LAYER_ALT_TAB_LAYER 3`)