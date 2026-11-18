# Theory Desk

A single-page music theory companion: pick a root and scale, see and hear every chord in the key on a piano keyboard and guitar fretboard, play progressions, and connect a MIDI keyboard to have your chords named and explained.

Live page: https://balbinot.github.io/theory-desk/

## MIDI

Web MIDI works in Chrome and Edge on a computer. Safari on iPad has no Web MIDI, so open the page there in a browser app that adds it. The touch keyboard works everywhere.

## Sound

The grand piano uses the Salamander Grand Piano samples by Alexander Holm (CC BY 3.0), loaded from the Tone.js audio host. If they cannot be loaded, a synthesised piano is used.

Everything else is in `index.html`, with no build step and no external dependencies.
