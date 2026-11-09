# Area Hit Vials

# Throw your potions, poisons and spirits as vials. The vial shatters on impact and **everyone within the radius gets exactly what drinking it would do** - including poisons mixed in with The Poisoner. Nobody notices who threw it.

## How it works
- **Hold Ctrl** - a radial menu shows every potion, poison and spirit you carry, with its icon, quality and count. Point at one with the mouse and release Ctrl to pick it. More than 8 kinds? The mouse wheel or the small arrows below the ring turn pages.
- **Hold E** while looking at nothing - a small display at the bottom shows the picked vial. Release E to throw it where you look. The mouse wheel changes the vial on the fly.
- **E + right mouse** - cancel the throw.
- Standing or crouched does not matter.

## On impact
- The vial breaks with the vanilla shatter sound and splash.
- Every NPC within the radius (2.5 m by default) drinks it: potions give their effect, poisons their poison, spirits get them drunk.
- Poisons inside a potion splash too: a potion carrying Bane, Dollmaker and Lullaby from The Poisoner hits with all three.
- The throw is silent - nobody notices it was you.

## Radial menu for your other mods
The arrows at the top of the ring switch between tabs. Other mods can add their own tabs to the same ring. If **Virtunerd Radial** (separate mod) is installed, Area Hit Vials uses that ring and only adds its Vials tab; without it, the built-in ring is used. No mod depends on the other.

## Install
[olist]
[*]Copy **AreaHitVials.asi** from the mod folder into *Bin\Win64MasterMasterSteamPGO*. **It needs an ASI loader there.** Without it, potions splash without the poisons inside them; everything else works.
[/olist]

## Settings
mod.cfg in the mod folder (takes effect the next time a save is loaded):
- Radius - splash radius in metres (0.5 - 10)
- Speed, Lift - throw speed and upward speed
- LifeSec - the vial breaks at the latest after this time
- Radial - 1 = radial menu on Ctrl, 0 = off (pick with the mouse wheel while holding E)
- Display - 1 = show the picked vial while holding E, 0 = off

## Compatibility
- Replaces no vanilla files: own scripts, own UI files and its own key bindings. The game's bindings stay untouched.
- E only throws when you look at nothing. Doors, items, NPCs and other interactions keep their vanilla E.
- Left Ctrl is only used by the game to slow down a horse; the menu does not open while riding, in dialogs, sitting, on ladders or with a menu open.
- Works with The Poisoner (stacked poisons) and with Virtunerd Radial.
- Menu and throw display in German and English (other game languages show English), item names in every game language.

v1.0.2
