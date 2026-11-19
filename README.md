# At Sea

A stylized low-poly sailboat drifting through an endless ocean — a single-file three.js (r170) scene.

**Play it:** https://claude.ai/artifact/MmEERaA4jhKUGVHfe8N1bX

Open `index.html` in a modern browser (it loads three.js from unpkg, so it needs a network connection). Everything else — models, textures, weather and sound — is generated in code.

## Controls

| Button | Key | What it does |
| --- | --- | --- |
| Day / Night | `D` | The clock runs on its own (a day every 14 minutes by default); this jumps to the next dusk or dawn over 3 seconds |
| Weather | `W` | Cycles Clear Skies → Partly Cloudy → Full Clouds → Dark Rain Clouds → Raining → Storming → Heavy Storm |
| Fish | `F` | The captain casts a line (20% chance of a catch, which goes in the bucket) |
| Camera | `C` | Orbit → Deck View (drag to look around) → Sea Life (follows dolphins, whales, turtles…) → Cinematic → Underwater (drag to look around) |
| Kraken | `K` | Summons the kraken (it also turns up on its own by day). When it rises, choose `1` offer it a fish, `2` sound the foghorn or `3` hide |
| Shipwright | `B` | Repaint and dress the boat: name and lettering, hull, stripes, rails, deck, cabin, sails, flag (or draw your own 8×8 emblem for the flag and mainsail), figurehead, lights, themes. The Crew tab dresses the captain (coat, hat, beard, pipe) and Ghost (collar, bandana, raincoat); the Cabin tab changes the quilt, rug, walls and picture |
| Steer | `←` `→` | Turn to port or starboard (the captain takes the wheel) |
| Sea chart | `N` | A chart of everything around the boat. Tap an island to steer for it, or choose which harbour to visit and which to sail past |
| Market | `U` | When tied up at a harbour island: sell fish and treasure, buy provisions and upgrades, hire a deckhand |
| Time | `Space` / `T` | Pause, or cycle 1× → 2× → 5× (also the buttons beside the tools) |
| Photo mode | `P` | Hides the interface; pick a filter, pause time, and take a photo (`Space`) |
| Settings | `O` | Music and effects volume, day length, season, kraken visits, graphics, reduced motion, vibration, new voyage |
| Sound | `M` | Toggle all audio (music and effects) |
| Quality | `Q` | Auto / High / Medium / Low graphics (the FPS chip shows the current rate) |

Drag to orbit, scroll to zoom; the camera slowly auto-rotates when idle. Click the captain or Ghost to see what they're up to, or click any cabin window to slip inside for a view of the whole cabin (`Esc` steps back). Click the title card to collapse it. On touch screens, swipe left or right with two fingers to change camera, or up for photo mode.

Your voyage (day, catch, treasure, gold, upgrades, deckhand, course, discoveries, log) and your boat's and crew's look are saved in the browser.

## On the voyage

- **Adventure:** lighthouse and palm islands, an old shipwreck, a passing schooner and messages in bottles appear on the horizon. The captain spots them with his spyglass and records each discovery in the ship's log.
- **Sea life:** leaping fish and dolphins, breaching whales, sea turtles, gulls that circle and perch on the rigging, and glowing jellyfish and a bioluminescent wake at night.
- **The Kraken:** on rare days its tentacles rise around the boat and its great head surfaces nearby. It never touches the boat, but the captain and Ghost run for cover.
- **Weather:** rain splashes on the deck, heavy seas break over the bow, lightning lights up the clouds and fog banks roll in.
- **Animation:** the crew lean against the boat's roll, look at whatever is happening, fidget, and talk. The captain puffs his pipe; Ghost's ears and tail move with his mood.
- **Crew life:** the captain steers, trims sails, fishes, drinks coffee, coils rope, bails in storms, writes the log, plays harmonica before bed and wears a yellow raincoat in the rain. Ghost fetches, howls at the moon, shakes off the rain, wears a life vest in storms and occasionally steals a fish.
- **The cabin:** a walk-in room below the deckhouse with a bunk, chart table, coal stove, Ghost's bed, a swinging lantern and a clock that keeps ship's time. At night the captain writes the log, reads or warms up by the stove, then sleeps in his bunk while Ghost curls up by the fire.
- **Harbour islands:** islands with a jetty, cottages and villagers. The boat ties up, and the captain and Ghost go ashore to chat with the locals (who give bread, fish and carrots), cook at a beach campfire, nap in a hammock and dig up buried treasure.
- **Crew needs:** Fed and Rest meters for both. A hungry captain cooks in the galley and the two of them eat together on deck; tired crew nap.
- **Seasons:** spring, summer, autumn and winter turn every two days (or hold one in Settings), with snow, ice floes, seasonal island trees and a winter scarf.
- **Sky:** moon phases, rainbows after rain, shooting stars, the aurora and glowing plankton.
- **Ships and sea life:** a pirate ship, a fishing trawler and a ghost ship pass close by, and their crews wave back when the captain hails them. Orcas, manta rays, sea otters and a rare sea serpent join the dolphins and whales.
- **Storms:** green water sweeps the deck, the mainsail is reefed in a gale and lightning sometimes strikes close aboard.
- **The boat:** twice the size it used to be. The hull, mast and sails doubled while the cabin, helm and everything the crew handle stay life-size, so there's room to roam (and for the upgrades).
- **Gold and upgrades:** sell fish (3 gold) and treasure chests (40 gold) at harbour markets, buy bread and vegetables, and fit upgrades. Racing canvas makes the boat 30% faster. A bigger fish tub holds 12. From the crow's nest the captain climbs up to keep a lookout. The saluting cannon answers passing ships. Ghost naps in the ship's dinghy.
- **Steering:** the sea, sky, horizon and camera swing together as the boat turns. Left alone, the captain sets a course for the next harbour island himself; sometimes two islands appear and you choose.
- **Kraken friendship:** feed it fish and it warms to you. Friendly, it stops frightening the crew and brings gifts: fish, pearls and chests. An old friend swims alongside as an escort. The foghorn hurts its feelings.
- **The deckhand:** hire one at a harbour market. They swab the deck, mend nets, keep a lookout, swap stories with the captain, slip Ghost biscuits and sleep on a bedroll on the foredeck.
- **Moods:** a Mood meter for the captain and Ghost, driven by food, rest, weather and fun. A cheerful captain dances a jig; a glum one stoops, slows and sits until Ghost comes to cheer him up.
- **Festivals:** in winter the rigging twinkles with coloured lights, with a wreath by the cabin door and a little fir on the roof. On summer nights, harbour islands float paper lanterns on the water and send more up into the sky.
- **Underwater:** the hull from below, light rays, a reef of coral and kelp sliding past, fish schools, and something enormous watching from the deep.
- **Music:** a procedural sea shanty by day, soft pads at night, a jig in harbour and drums when the kraken rises.
