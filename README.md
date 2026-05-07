# WebGL Fluid Simulation

[Play here](https://paveldogreat.github.io/WebGL-Fluid-Simulation/)

<img src="/screenshot.jpg?raw=true" width="880">

## References

https://developer.nvidia.com/gpugems/gpugems/part-vi-beyond-triangles/chapter-38-fast-fluid-dynamics-simulation-gpu

https://github.com/mharrys/fluids-2d

https://github.com/haxiomic/GPU-Fluid-Experiments

## Windows Fullscreen + Sound-Reactive Setup

### Fullscreen autoplay mode

- Open with `?autoplay=1` (or `?present=1`) to run in presentation mode and hide dat.GUI:
  - Example: `https://paveldogreat.github.io/WebGL-Fluid-Simulation/?autoplay=1`
- On desktop, first interaction requests browser fullscreen.
- Press `F` to toggle fullscreen at any time.

### Enable sound reactivity

- Use the **Sound** folder in the GUI:
  - **Enable Sound**: captures microphone/default recording device with `getUserMedia`.
  - **System Audio**: uses `getDisplayMedia` (Chrome/Edge) to capture shared tab/window/screen audio.

### Windows Stereo Mix option (for system-wide audio via microphone capture)

1. Open **Sound settings** in Windows.
2. Set **Stereo Mix** (or equivalent loopback recording device) as the default recording source.
3. Reload the simulation and use **Enable Sound**.

If Stereo Mix is unavailable, use **System Audio** in Chrome/Edge instead.

## License

The code is available under the [MIT license](LICENSE)
