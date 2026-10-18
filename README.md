# Spatial Field Synthesizer

A playable browser instrument. Notes are "stars" floating in a 3D field, and a sweep plane plays them as it passes:

- **Height** is pitch, snapped to the chosen scale over three octaves.
- **Size** is loudness, brightness and decay.
- **Depth** is time: the field is a 16-step sequencer swept front to back (or back to front, or up and down).

The whole instrument is one file, `index.html` (Three.js and Web Audio, loaded from CDNs). Open it in a browser to play; no build step.

## Using it

- **Play mode:** orbit the field, press **Sweep** to play it, pick a scale, root and tempo, or generate a **New field**.
- **Edit mode:** place, move, resize and delete stars on a depth slice, with undo and clear. Space plays the current slice.
- **Saved fields** are kept in your browser's local storage.

On phones, sound starts on your first tap; if it stays silent, tap the "Sound is off" button.

## Hosting

To get a shareable link, turn on GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).
