# Gesture Synth

A camera-based musical instrument that lets you control chords, tone, and expression using hand gestures.

## Demo

🎥 Watch the Gesture Synth tutorial on Instagram:
https://www.instagram.com/p/DbH1BACxNCG/

## Features
- Left hand controls chord selection
- Right hand controls voicing and expression
- Real-time hand tracking with MediaPipe
- Sampled instrument sounds (piano, strings, harp, organ and more) played from a SoundFont

## Built With
- JavaScript
- SpessaSynth (SoundFont player)
- MediaPipe Hand Landmarker
- Web Audio API
- Vite

## Run it locally
1. Install [Node.js](https://nodejs.org) 18 or newer.
2. `npm install`
3. `npm run dev`, then open http://localhost:5173
4. Click the start button (it loads about 23 MB of sounds), then allow the camera when asked.

Localhost counts as a secure origin, so the camera works without HTTPS. Use Chrome or Edge.

Pick an instrument from the dropdown. Hand tilt still sweeps the tone filter.

## Sounds
The instrument samples are FluidR3Mono_GM (MIT licence, see `public/sound/FluidR3Mono_License.md`).

## License
Gesture Synth is free to use, modify, and share for educational and non-commercial purposes.
If you build upon this project, please credit the original creator.
