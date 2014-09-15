TIL3R
=====

TIL3R adds more manual tiling options to KWin. With this script you can divide you screen in thirds, using the full or half screen height.


__Stuff that could be done:__
- multimonitor testing and support [done?]
- maximize windows in certain directions, e.g.
  - Meta+Alt+Left: keep height, but stretch window to left border
  - Meta+Alt+Down: keep width, but stretch window to lower border
  - etc.
- changing the shortcuts to the following:
  - Meta+Alt+[NUMBER]: Tile horizontally, full height
  - Meta+Ctrl+[SOME_KEY]: switch to half height
- saving the window properties (size, pos) and adding a callback to restore the old size when the window gets moved by the user again (like the normal KWin tiling does)
