# MOSH — Precious FM datamosh + shapes tool

A self-contained, in-browser glitch studio. No install, nothing uploaded — everything runs locally in your browser and your images stay on your device. Two modes: **datamosh** (square block glitch) and **shapes** (rebuild the picture from shapes — solid blooms or glitch portals).

**Live tool:** https://darcynathanson-cmd.github.io/precious-fm-mosh/

## Datamosh mode

- **Load** a photo, GIF, or video and glitch it in real time. You can also load a **second clip** and mosh the first into it for a transition (with optional auto-swap).
- **Style** the whole image — `blend · melt · streak · chaos · random` — or split it into **sections** (cross, X, circle, wedges, or a **shape**), giving each part its own effect. Set a part to `clean` to keep the untouched photo (a crisp window through the glitch) or `channel` for a localized RGB channel-break. Drag on the image to move / resize the split.
- **Shapes as masks** — mask the glitch to a shape so it breaks the pattern. Nine Precious FM graphics are built in (hibiscus, PRECIOUS wordmark, palm badge, bloom, techno-girl, script, bunny, apple, gothic FM), or upload your own SVG. Set inside / outside to any effect (`clean` = crisp cut-out window, `channel` = RGB channel-break). Drag to move, resize, rotate.
- **✨ Surprise me** — a brand-new totally random look every press. Undo steps back.
- **Adjust / Colour FX / Glitch FX** — intensity, block size, keep-original, smear, speed, "crazy from the first frame"; hue / saturation / contrast / invert (+ candy · acid · cool); pixel sort, channel delay, glowing trails, **time-warp (slit-scan)**.
- **Stack ↻** — nest the image inside itself toward the centre (Droste) + infinite zoom.
- **Auto-move** — record a video that sweeps the settings through a range of looks.
- **✨ Variety — never the same twice** — a per-run seed reshuffles the motion field so the same look records differently every take; turn on **keep it moving** for live drift / pulse / wind / bursts / drift-cam.
- **Beat sync** — the glitch pulses to a loaded track (or the video's own sound, or a BPM).

## Shapes mode

Rebuild the picture out of shapes instead of blocks. Toggle **shapes ✿** at the top of Step 2.

- **Two styles** — **solid bloom** (coloured shapes reconstitute the image, pointillist) or **glitch portals** (the shapes are windows onto a churning, chromatic glitch that resolves back to the image).
- **Shapes** — circle · heart · star · flower · 🦋 butterfly · 🎲 mix, plus the Precious FM SVG shapes (apple / bunny / hibiscus / …) or your own uploaded SVG.
- **Controls** — size, motion (bloom + arc / gentle drift / rain), swim, dark peak (portals), colour from the photo or a palette (candy / rainbow / sunset / mint / mono), background (candy / white / cream / ink / black / transparent), and a 🎲 surprise button.

## Export

- **🎬 Festival export** — a clean **1080×1920, 25fps, 10-second, silent MP4** (Design in Motion Festival spec), from either mode.
- Also: record MP4 (webm fallback) at 4–20s in original / 4:5 / 1:1 / 9:16, save the current frame as a PNG, and save / load your looks as JSON (works in both modes).

## Use it

Open the live link above, or open `index.html` in any modern browser (Chrome recommended for MP4 export). Everything is in that one file.

Made for [Precious FM](https://www.mixcloud.com/).
