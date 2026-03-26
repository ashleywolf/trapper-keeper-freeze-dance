# Trapper Keeper Freeze Dance

Dance for 6 seconds. Freeze for 2.5. Your frozen pose becomes a Lisa Frank sticker.

**[Play it](https://ashleywolf.github.io/trapper-keeper-freeze-dance/)**

The music plays and you dance. When it stops, hold perfectly still -- MediaPipe is tracking every joint. If you move during the freeze, you fail. If you hold it, your pose gets captured and printed as a neon sticker in a Trapper Keeper collage.

Play enough rounds to fill the page, then download your sticker sheet as a PNG.

## How it works

- MediaPipe PoseLandmarker for body motion detection
- Joint velocity tracking to detect movement during freeze
- Canvas capture for sticker snapshot
- Lisa Frank aesthetic: magenta-to-cyan gradients, neon borders, sparkle effects
- Collage builder with downloadable PNG export
- Web Audio API for phase transitions
- Single HTML file, pure browser
