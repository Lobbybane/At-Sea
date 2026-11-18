# At Sea

A stylized low-poly sailboat drifting through an endless ocean — a single-file three.js (r170) scene.

Open `index.html` in a modern browser (it loads three.js from unpkg, so it needs a network connection). Everything else — models, textures, weather and sound — is generated in code.

## Controls

| Button | Key | What it does |
| --- | --- | --- |
| Day / Night | `D` | 3-second transition; stars, moon and boat lanterns come out, the captain and Koda go to sleep |
| Weather | `W` | Cycles Clear Skies → Partly Cloudy → Full Clouds → Dark Rain Clouds → Raining → Storming → Heavy Storm |
| Fish | `F` | The captain casts a line (20% chance of a catch, which goes in the bucket) |
| Explode | `E` | Splits the boat into labelled floating layers; press again to reassemble |
| Sound | `M` | Toggle the procedural audio |

Drag to orbit, scroll to zoom; the camera slowly auto-rotates when idle.
