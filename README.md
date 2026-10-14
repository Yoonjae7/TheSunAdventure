# Saleem the Antonio

A souls-like boss gauntlet that runs in the browser (three.js). The whole game is one file.

## Play

Open `index.html` in Chrome or Edge. It works offline: `three.min.js` sits next to it as a fallback for the CDN.

To use the DualSense adaptive triggers, serve the folder instead of opening the file:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

A controller is recommended. Keyboard and mouse also work.

## Heroes

Pick your hero on the title screen with the D-pad (left and right).

- **The Sun**: a knight with sword and shield. His ult is Holy Fire. Hold heavy in it to charge, all the way up to Might of God.
- **The Moon**: a Hwarang with a sword and a horn bow on heavy. His ult is Moonlight: his sword becomes a dragon sword with slow, wide, heavy sweeps. Hold the draw in it through Crescent, Half Moon, Full Moon and Moonfall. From Full Moon on you can glide around while you hold it.

## Controls

| Action | Pad | Keyboard / mouse |
| --- | --- | --- |
| Move | L stick | W A S D |
| Light attack | R1 | Click / J |
| Heavy attack (Moon: bow) | R2 | Right click / K |
| Block (hold) / parry (tap) | L1 | Shift |
| Dodge roll | A | Space |
| Ult (when full) | Y | E |
| Charge in the ult | Hold R2 | Hold K |
| Flask | X | R |
| Lock-on | R3 | Q |
| Pause | Start | Esc |

Execute a kneeling boss with light attack once the prompt appears.
