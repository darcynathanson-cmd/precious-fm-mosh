# MOSH — Precious FM datamosh tool

A self-contained, in-browser datamosh / glitch studio. No install, nothing uploaded — everything runs locally in your browser and your images stay on your device.

**Live tool:** https://darcynathanson-cmd.github.io/precious-fm-mosh/

## What it does

- **Load** a photo, GIF, or video and glitch it in real time. You can also load a **second clip** and mosh the first into it for a transition (with optional auto-swap).
- **Style** the whole image — `blend · melt · streak · chaos · random` — or split it into **sections** (cross, X, circle, or wedges), giving each section its own effect. Set a section to `clean` to keep that part as the untouched photo (a crisp window through the glitch). Drag on the image to move the split.
- **✨ Surprise me** — one button cycles eight hand-tuned full looks (Cotton candy melt, Acid rain, Liquid time, Chrome smear, Droste dream, VHS bleed, Rainbow shred, Ghost echo). Great for fast promo iterations; hit undo to step back.
- **Adjust** — intensity, block size, keep-original, smear, speed, and "crazy from the first frame."
- **Colour FX** — hue / saturation / contrast / invert, plus candy · acid · cool presets.
- **Glitch FX** — pixel sort (horizontal or vertical, ordered by brightness, darkness, or hue) with a threshold; channel delay (RGB time-displacement); glowing trails; and **time-warp (slit-scan)** where each row samples a different moment in time for a liquid ripple.
- **Stack ↻** — nest the image inside itself toward the centre (Droste), with an optional never-ending infinite zoom.
- **Vignette + channel split** — a soft oval vignette whose edges peel into red / green / blue while the centre stays true.
- **Auto-move** — record a video that sweeps the settings through a range of looks (journey, intensity swell, colour trip, pixel-sort sweep, time smear, random drift, or your own saved stops).
- **Beat sync** — load a track or use the video's own sound and the glitch pulses to the bass; the music is baked into the recording. No track? It pulses to the BPM. Volume starts off so nothing blares while you work.
- **Export** — record MP4 (webm fallback) at 4–20 seconds in original / 4:5 / 1:1 / 9:16, save the current frame as a PNG, and save / load your looks as JSON.

## Use it

Open the live link above, or open `index.html` in any modern browser (Chrome recommended for MP4 export). Everything is in that one file.

Made for [Precious FM](https://www.mixcloud.com/).
