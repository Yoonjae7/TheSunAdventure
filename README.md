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

The first load takes a few seconds while the characters are sculpted. The game sets its own render resolution to keep the frame rate up. To fix it yourself, add `?scale=` to the address: `?scale=1` for full resolution, or a lower number such as `?scale=0.6` for a slow machine.

## Heroes

Pick your hero on the title screen with the D-pad (left and right).

- **The Sun**: a knight with sword and shield. His ult is Holy Fire. Hold heavy in it to charge, all the way up to Might of God.
- **The Moon**: a Hwarang with a sword and a horn bow on heavy. His ult is Moonlight: his sword becomes a dragon sword with slow, wide, heavy sweeps. Hold the draw in it through Crescent, Half Moon, Full Moon and Moonfall. From Full Moon on you can glide around while you hold it.
- **The Star**: a cyborg gunslinger with a revolver and steel arms.
  - Light attack shoots. The cylinder holds six; he reloads when it runs dry, and tops it up if you stand still a moment. Hold light attack to keep firing.
  - Heavy attack fans the hammer with both hands and empties the cylinder.
  - He blocks and parries on his steel forearms. A shot straight after a parry is a riposte.
  - His ult is Overdrive: power lines light up across his body and boosters fold out of his calves. Tap roll to skid on the boosters, hold roll to fly (slams and stomps cannot reach you in the air). The cylinder never runs dry.
  - Hold heavy in Overdrive to bring out every gun: Spinning up, Hot iron, Full arsenal, Every gun, then Dead Man's Hand at ten seconds. Let go to fire everything. A hit breaks the charge until the second mark (Full arsenal); from there on nothing can touch you.
  - Keep holding past the Dead Man's Hand and it goes quiet: high noon. When the ring has closed on the boss's face, let go and he is executed where he stands.

All three charges reach their top in ten seconds.

## Bosses

The gauntlet runs Fucking Clement, Saleem the Antonio, Fucking Chan, then Fucking Clement, Perfected. Whatever you end him with, "The End" comes up, and then a spear comes through it. Someone has been watching the whole time.

What follows plays out on its own until the last moment: a city, a titan, and the other two heroes. Then the Star has one shot. A ring closes on the Devil's head; once it has closed, shoot (light or heavy attack) before his trident comes down. Too soon or too late and you try it again from the top of his dive. For now it ends there: to be continued.

Once you have met the Devil, he is pick 5 on the title screen, and you can fight him there. Pick 6 plays the ending on its own, from "The End" on.

## Controls

| Action | Pad | Keyboard / mouse |
| --- | --- | --- |
| Move | L stick | W A S D |
| Light attack | R1 | Click / J |
| Heavy attack (Moon: bow, Star: fan the hammer) | R2 | Right click / K |
| Block (hold) / parry (tap) | L1 | Shift |
| Dodge roll (Star in Overdrive: tap to skid, hold to fly) | A | Space |
| Ult (when full) | Y | E |
| Charge in the ult | Hold R2 | Hold K |
| Flask | X | R |
| Lock-on | R3 | Q |
| Pause | Start | Esc |

Execute a kneeling boss with light attack once the prompt appears.
