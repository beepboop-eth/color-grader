# LUT Builder

A browser-based color grading tool for drone footage. Design a look on a still
frame or video frame, then export it as a `.cube` LUT for DaVinci Resolve,
Premiere Pro, Final Cut, CapCut, etc.

**Live app:** https://beepboop-eth.github.io/color-grader/

Everything runs locally in the browser — footage never leaves your machine.

## Features

- Drag & drop a photo or video (with frame scrubbing) as the grading reference
- Exposure, contrast, saturation, white balance, and shadows/midtones/highlights color wheels
- Bundled film-simulation base looks, a set of custom drone LUTs (`luts/drone/`), + import your own `.cube` or HaldCLUT `.png` LUTs (single files or whole folders; imports are stored in the browser)
- LUT strength control, before/after toggle, luma waveform
- Export the full grade (base LUT + adjustments) as a standard 33-point `.cube`

## Bundled film looks — attribution

The files in `luts/` are film simulation HaldCLUTs from the
[RawTherapee Film Simulation Collection](https://rawpedia.rawtherapee.com/Film_Simulation)
(by Pat David, Pavlov Dmitry, Michael Ezra and contributors), licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), obtained via
[cedeber/hald-clut](https://github.com/cedeber/hald-clut). They are
redistributed here unmodified, under the same license. Film stock names appear
for informational purposes only; no affiliation with or endorsement by the
trademark owners is implied.
