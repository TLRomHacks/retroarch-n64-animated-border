# N64 animated border for RetroArch

A Nintendo 64 themed overlay with animated controller buttons, a moving analog
stick, and a two-page menu for RetroArch controls. The alternate 'no controller' version keeps
the border and utility menu without the controller artwork or touch targets.

## Download

Download and extract the desired ZIP. Load its CFG in RetroArch, keeping
`img/runtime/` beside it. Open the included HTML locally to try the preview.
The preview simulates utility actions; the CFG executes them in RetroArch.

See retroarch-setup.md for overlay settings and
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

- <img width="1280" height="720" alt="preview-screenshot" src="https://github.com/user-attachments/assets/95ec44ce-43cd-4f1a-bf23-44612eb6ef6a" />

- <img width="1920" height="1080" alt="no-controller-screenshot" src="https://github.com/user-attachments/assets/62656450-f20b-4fa0-9126-613b17ef33b7" />


