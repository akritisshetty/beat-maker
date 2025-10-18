# 🎵 Beat Maker - Interactive Music Pad

A web-based music pad, featuring 16 colorful pads that play different synthesized sounds in real-time.

## Features

- **16 Interactive Pads**: Click to play different sounds including drums, bass, leads, synths, and FX
- **Real-time Audio Synthesis**: All sounds are generated on-the-fly using Tone.js
- **Visual Feedback**: Ripple animations when pads are clicked

## Sound Types

- **Pads 1-8**: Drum sounds (Kick, Snare, Hi-Hat, Clap, Toms, Crash)
- **Pads 9-10**: Bass sounds
- **Pads 11-12**: Lead synth sounds
- **Pads 13-14**: Polyphonic synth sounds
- **Pads 15-16**: FM synthesis FX sounds

## How to Use

1. Clone the repo
2. Open the `index.html` file in a web browser
3. Click the "Start Audio" button to initialize the audio engine
4. Click any pad to play sounds
5. Combine different pads to create your own beats and melodies!

## Technical Details

- **Framework**: HTML, CSS, and JavaScript
- **Audio Library**: Tone.js v14.8.49
- **Synthesis Types**: 
  - MembraneSynth (drums)
  - NoiseSynth (snare/clap)
  - MetalSynth (hi-hats/cymbals)
  - MonoSynth (bass)
  - PolySynth (chords)
  - FMSynth (effects)

## Notes

- The "Start Audio" button is required due to browser autoplay policies
- All sounds are synthesized in real-time (no audio files needed)
- Each sound is designed to play once and stop automatically
