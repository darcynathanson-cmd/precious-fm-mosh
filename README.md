# MOSH — Precious FM datamosh tool

A self-contained, in-browser datamosh / glitch studio. No install, nothing uploaded — everything runs locally in your browser and your images stay on your device.

**Live tool:** https://darcynathanson-cmd.github.io/precious-fm-mosh/

## What it does

- **Load** a photo, GIF, or video and glitch it in real time. You can also load a **second clip** and mosh the first into it for a transition (with optional auto-swap).
- **Style** the whole image — `blend · melt · streak · chaos · random` — or split it into **sections** (cross, X, circle, wedges, or a **shape**), giving each part its own effect. Set a part to `clean` to keep the untouched photo (a crisp window through the glitch) or `channel` for a localized RGB channel-break. Drag on the image to move / resize the split.
- **Shapes** — mask the glitch to a shape so it breaks the pattern. Nine Precious FM graphics are built in (hibiscus, PRECIOUS wordmark, palm badge, bloom, techno-girl, script, bunny, apple, gothic FM), or upload your own SVG. Set the shape's inside / outside to any effect: a wild preset so the shape moshes differently, `clean` for a crisp cut-out window, or `channel` for an RGB channel-break inside the shape. Drag to move, resize, and rotate it; drift-cam can animate it over a recording.
- **✨ Surprise me** — rolls a brand-new **totally random** full look every press (random preset, sliders, colour, and a random mix of the glitch / stack effects), bounded so it stays usable. Hit undo to step back to your previous look.
- **Adjust** — intensity, block size, keep-original, smear, speed, and "crazy from the first frame."
- **Colour FX** — hue / saturation / contrast / invert, plus candy · acid · cool presets.
- **Glitch FX** — pixel sort (horizontal or vertical, ordered by brightness, darkness, or hue) with a threshold; channel delay (RGB time-displacement); glowing trails; and **time-warp (slit-scan)** where each row samples a different moment in time for a liquid ripple.
- **Stack ↻** — nest the image inside itself toward the centre (Droste), with an optional never-ending infinite zoom.
- **Auto-move** — record a video that sweeps the settings through a range of looks (journey, intensity swell, colour trip, pixel-sort sweep, time smear, random drift, or your own saved stops).
- **✨ Variety — never the same twice** — a per-run **seed** reshuffles the underlying motion field, so the same look records differently every take (rolled on surprise / randomize / a 🎲 button, or automatically on each recording — and saved into your look files so a magic run is reproducible). Turn on **keep it moving** for live modulation: **drift** (slow organic wander), **pulse** (breathing), **wind** (the flow direction swings), **bursts** (occasional glitch spikes), and **drift-cam** (the picture slowly pans / the shape or split wanders). Off by default; an Amount dial scales it all.
- **Beat sync** — load a track or use the video's own sound and the glitch pulses to the bass; the music is baked into the recording. No track? It pulses to the BPM. Volume starts off so nothing blares while you work.
- **Export** — record MP4 (webm fallback) at 4–20 seconds in original / 4:5 / 1:1 / 9:16, save the current frame as a PNG, and save / load your looks as JSON.

## Use it

Open the live link above, or open `index.html` in any modern browser (Chrome recommended for MP4 export). Everything is in that one file.

Made for [Precious FM](https://www.mixcloud.com/).
