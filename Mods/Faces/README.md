# Faces

**Download:** [Faces.zip](https://github.com/Virtunerd/Kingdom-Come-Deliverance-2/releases/download/kcd2/Faces.zip)

**New clothes, new man.**

Committed a crime and the whole town is after you? Slip away, change your clothes where nobody can see you, and walk back in as a stranger. Witnesses and guards forget what you did there. No wanted status, no fine, no jail.

## How it works

- Put on, take off or swap any piece of clothing or armor in your inventory. A short *"Mr. Nobody"* message confirms it.
- **In a town or village** (Kuttenberg or any village), every crime you committed in that place is forgotten.
- **Out in the country**, every crime within 500 m of where you changed is forgotten.
- Crimes in other places stay. Change in one village and your warrant in the next village is still waiting for you.
- NPCs who are searching for you give up and go back to their routine.
- Bodies found later are not blamed on you, and people you knocked out don't know who hit them when they wake up.

## Don't get caught changing
If anyone can see you while you change, it doesn't work. "Seeing" means you are in their field of view (120°, up to 30 m) with nothing in between. Walls, houses and terrain block the view, so a closed room or a quiet spot behind a barn is enough.

## What doesn't count

- Repairing, wear and tear, rings and weapons are not a change of clothes.
- Stolen goods stay stolen. If a guard frisks you, he will still find them.
- Kuttenberg and Trosky are separate maps. Changing on one map doesn't clear crimes on the other.

## Settings
All settings are in *mod.cfg*:

- **Enabled**: turn the mod on or off.
- **RequireUnseen**: if you turn this off, changing works even when someone is watching.
- **SightRange**: how far NPCs can see you change (default 30 m).
- **Notify**: show the "Mr. Nobody" message.

Console command: **faces_purge** clears your crimes in the current place right away.

## Compatibility

- Works with or without The Poisoner, in any load order.
- Changes *AI/crime/forgetCrimes.xml* and the character screen definition *Libs/UI/UIElements/ApseCharacter.xml*. Other mods that replace these files will conflict.
- Other crime mods (stealth, theft, snitching, pickpocket and so on) work alongside it.

## Installation
Install with Vortex, or unzip into *KingdomComeDeliverance2/Mods*.

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3833862451)
