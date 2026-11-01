# Frostfall: Last Fire

A small survival game that runs in the browser. It's a single HTML file with no dependencies.

The world has frozen over. Chop wood, keep the furnace burning, thaw out frozen survivors, build up your camp and hold off wolves until the thaw comes.

## Play

Open `index.html` in any modern browser. It also works on phones: drag anywhere to move.
https://ecwebdev.github.io/survivalgame/

| Control | Action |
|---|---|
| WASD / arrow keys / drag | Move |
| M | Mute or unmute |

## How it works

- **Chop and carry:** walk into trees to chop them. Logs stack on your back.
- **Feed the furnace:** a bigger fire means a wider warm zone. If the fire stays out for 20 seconds, the camp freezes.
- **Rescue survivors:** stand next to people frozen in ice to thaw them. Build shelters so you have beds for them.
- **Build:** drop logs on the build pads. Buildings unlock in a chain: Shelter, Lumber Camp, Scout Post, Sled Workshop, Watchtowers, Great Furnace, Longhouse, Storehouse, Blacksmith, Steam Heaters, Infirmary, Spike Palisade, Eternal Furnace and the Rescue Beacon.
- **Expeditions:** once a day at the Scout Post, steer your group through number gates (+N, ×2, −N, ÷2), dodge ice spikes and beat a wolf pack for rewards.
- **Nights:** wolves attack, and a giant Ice Bear comes on nights 3 and 5.
- **Win:** survive 5 nights, or build the Rescue Beacon to escape early.

## Deploy

Since it's one static file, GitHub Pages works as is: go to Settings → Pages → Deploy from branch → `main` / root.
