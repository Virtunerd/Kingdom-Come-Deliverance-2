# Shadowmaker

# Put out the lights and make your own shadows. Candles, lamps, chandeliers, wall torches, hearth fires, and the torches and lanterns other people carry

## How to put a light out

- **Arrows & Bolts**: shoot the flame.
- **Stone**: hit the flame with a thrown stone.
- **E**: stand right in front of a flame and tap E.

The light and the flame go out together. A lamp or chandelier with several candles goes dark as a whole.

## Torches and lanterns carried by others
Guards and townsfolk walking around with a torch or lantern can have it shot out:

- an arrow or pebble that passes close to the flame puts it out,
- an arrow that hits the hand or arm holding the torch puts it out too, even when the guard has noticed you and turns towards you,
- a snuffed torch stays dark when the guard drops it or draws his weapon.

Henry's own torch is never affected.

## Good to know

- Snuffed lights stay out while you are in the area.
- Lights the game lights again, like wall torches at dusk or a hearth someone cooks at, can simply be put out again.
- Snuffed lights are not saved. After loading a save everything burns again.

## Settings
Open *mod.cfg* in the mod folder. Changes take effect the next time a save is loaded.

| Setting | Default | What it does |
|---|---|---|
| Shots | 1 | Arrows and thrown pebbles put out the flame they hit |
| Hand | 1 | Tap E right in front of a flame |
| Fireplaces | 1 | Fireplaces, hearths and alchemy fires can be put out too |
| Carried | 1 | Torches and lanterns carried by others can be shot out |
| OnlyPlayer | 1 | Only Henry's arrows and pebbles count |
| HitRadius | 0.5 | How close to the flame (in metres) a hit has to land |
| HandReach | 2.0 | How far away (in metres) a flame may be for E |
| HandAngle | 12 | How far off your view (in degrees) the flame may be for E |

## Known limitations

- On some chandeliers the light goes out but the candle flames stay visible.
- The glowing body of wall lanterns is part of the level geometry and keeps its lit look. The light itself goes out.

## Compatibility

- Pure Lua and XML, no ASI or script extender needed.
- Replaces one vanilla AI file, the player's arrow-hit handler (*AI/player/switch/handleArrowHitData.xml*), by adding a single call to the mod. Everything the file did before stays.
- A mod that replaces the same file conflicts with this one; whichever loads later wins. If the other mod wins, carried torches can still be shot out by a near miss, just not by hitting the hand that holds them.
- Other mods that listen to hits keep working.

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3834544834)
