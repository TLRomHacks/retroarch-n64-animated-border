# N64 animated border for RetroArch

A Nintendo 64 themed overlay with animated controller buttons, a moving analog
stick, and a two-page menu for RetroArch controls. The alternate version keeps
the border and utility menu without the controller artwork or touch targets.

## Download

| Package | Included preview |
| --- | --- |
| [Standard overlay](n64_animated_border.zip) | `overlay-preview.html` |
| [No-controller overlay](n64_animated_border_no_controller.zip) | `overlay-preview-no-controller.html` |

Download and extract the desired ZIP. Load its CFG in RetroArch, keeping
`img/runtime/` beside it. Open the included HTML locally to try the preview.
The preview simulates utility actions; the CFG executes them in RetroArch.

See [setup and controller mapping](retroarch-setup.md) for overlay settings and
feature requirements. Each ZIP also includes setup notes for its variant.

## Controls

- **Menu** opens the utility panels; **Play** and **A/V** switch pages.
- **Close** or **Menu** returns to the border without changing the pause state.
- **Power** quits RetroArch. **Reset** resets the current game.
- Utility controls include save/load states, slot selection, pause, frame advance,
  rewind, fast-forward, slow motion, screenshots, recording, volume, mute,
  fullscreen, FPS, shaders, RetroArch's menu, and Close Content.

Button feedback is momentary. Features such as rewind, recording and save states
depend on the core and RetroArch configuration. The standard preset uses a common
N64 RetroPad mapping; it does not automatically follow custom core remaps.

![Standard overlay preview](preview-assets/preview-screenshot.png)

![Utility menu](preview-assets/menu-play-screenshot.png)
