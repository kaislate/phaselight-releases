# Phaselight — Beta Releases

**A real-time VJ instrument and livestream visuals engine for Windows & macOS.** Grid-based live visuals — GPU shaders, 3D dioramas, fluid simulation, projection-style shapes, live text, and your camera — mixed on a clip grid with cue/take staging, audio reactivity, and hands-on control from MIDI, TouchOSC, or the keyboard.

![Phaselight live output](media/banner.png)

![Phaselight UI](media/ui-hero.png)

This repo hosts the public beta installers. Phaselight is pre-1.0 and under active development.

## 🔥 New in 0.7.0 — The Livestream Toolkit

The biggest release yet, built for people who perform on camera:

- **Broadcast-grade green-screen keying** on every media clip — two matte engines, despill, feather, matte preview, an eyedropper, and one-click AUTO. Key yourself over your visuals.
- **Face tracking with AR props** — hats, crowns, halos, shades, mustaches, beards, eye recolors, laser eyes — tracking your head in 3D, entirely on your machine, no green screen required.
- **NDI input** (Pro): pull OBS, cameras, or other machines into the grid as clips.
- **TouchOSC + MIDI + keyboard control** over everything, including the new **ACTION macros** — build your own triggered performance buttons with attack/hold/release envelopes.
- **Ableton Link** tempo sync across your whole rig.
- **SHOWS**: save and recall your entire desk in one click. **A full text engine** with live text-from-file. **A named undo history** you can jump through. A guided tour, a smarter starter grid, a full-frame-rate live monitor, and dozens of fixes and polish passes.

Full notes on the [v0.7.0 release page](https://github.com/kaislate/phaselight-releases/releases/tag/v0.7.0).

## Install

**Windows (Pro-capable)**
1. Download the latest `-setup.exe` (NSIS) or MSI from [Releases](https://github.com/kaislate/phaselight-releases/releases).
2. Run it and launch **Phaselight**.

**macOS (Core, Apple Silicon)**
1. Download the latest `.dmg` from [Releases](https://github.com/kaislate/phaselight-releases/releases).
2. Drag **Phaselight Core** to Applications. The build is unsigned — **right-click → Open** on first launch.

Every build from **v0.6.2** onward checks for updates on launch and installs them in-app — you only ever need to install by hand once.

## Get a beta key

Request one at **https://phaselight-beta.iamkaislate-dev.workers.dev/** — enter your email, click the confirmation link, and paste the key into the prompt on first launch (or anytime in **Settings → License**). One key per person; beta keys are valid for all 0.x releases.

The app runs as **Core** out of the box on both platforms. On Windows, a beta key additionally unlocks the **Pro** outputs and inputs: NDI network video (in AND out) and the virtual camera (OBS / Zoom / Discord).

## Feedback & beta diagnostics

The fastest way to reach us is the **⚡ FEEDBACK** button at the top of the app — type your report and optionally attach a snapshot of your output and technical details. You can review exactly what gets sent before sending. You can also open an [issue](https://github.com/kaislate/phaselight-releases/issues).

During the beta the app reports lightweight anonymous usage on its periodic license check (key id, app version, OS) so we can see which builds are actually in use. No personal data, no content, nothing from your machine beyond that — and the in-app notice spells it out.
