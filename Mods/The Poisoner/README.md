# The Poisoner

# Why settle for one poison when you can use three?

In vanilla, every item carries only a single poison - applying a second one simply replaces the first. **The Poisoner** lets you stack up to **three poisons on one item**, one of each kind:

- **Bane**
- **Dollmaker**
- **Lullaby**

Every poisoning hit and every bite or sip applies **all of them at the same time** - their effects add up.

## Works on

- Weapons and arrows
- Food and drinks
- Potions

## How it works

- Apply a second or third *different* poison: it is added instead of replacing the first one.
- Apply the same kind in another strength: only that poison is replaced, the others stay.
- The exact same poison cannot be applied twice (as in vanilla).
- Weapon charges after combining: the lower of the remaining and the new charges.
- A grindstone still removes all poisons from a weapon.

## See it at a glance
The poison drops on poisoned items change colour:

- **Green** - 1 poison
- **Blue** - 2 poisons
- **Black** - 3+ poisons with the latest "More Poisons" mod even 5

Shown in the inventory, loot/trade/storage windows, the poison selection dialog, the item description and the character screen. The item description names the combination, e.g. "Bane poison + Dollmaker poison".

## Installation

- Copy **Mods\thepoisoner** into your game's **Mods** folder.
- Copy **ThePoisoner.asi** and **ThePoisoner.ini** into **Bin\Win64MasterMasterSteamPGO**.
- An ASI loader is required (e.g. Ultimate ASI Loader as dinput8.dll).

Set **Enabled=0** in ThePoisoner.ini to turn the mod off.

## Compatibility
Replaces the UI files ApseInventoryList, ItemTransfer, ItemSelection, ApseInventoryInfo, ApseModalDialog and ApseCharacter (.gfx). Other mods that replace the same files will conflict - load order decides which one wins.

## Uninstall
Grind multi-poisoned weapons and use up multi-poisoned food or potions first, then remove both parts of the mod.

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3832890290)
