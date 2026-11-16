# Shackles

**Download:** [shackles.zip](https://github.com/Virtunerd/Kingdom-Come-Deliverance-2/releases/download/kcd2/shackles.zip)

# Put rusty shackles on NPCs and keep them as prisoners. They sit down on the ground in the vanilla tied-up pose, drop their daily routine and stay where they are, even after saving and loading.

Dev. in combination with my offering mod, so npcs could eat/drink and sit down again.

## How it works

- **Awake NPCs:** crouch and sneak up from behind, the same way you would for a stealth knockout, then press **V**.
- **Sleeping or unconscious NPCs:** walk up to them and press **V**. A knocked-out NPC wakes up at once and sits down in shackles, without checking their pockets first.
- Prisoners use the vanilla tied-up animations (separate ones for men and women) and wear iron shackles on their wrists.

## Freeing a prisoner

- Look at them and press **V**.
- Or pick the dialogue option **Take off the shackles**. You get the shackles back.
- Or take the shackles out of their inventory by pickpocketing or looting.

A freed prisoner forgets what happened while shackled. They won't attack you on sight, and a freed guard won't report you.

## Prisoners

- Don't fight back and don't stagger when hit.
- Can be knocked out and killed, just like at the pillory.
- Can be carried while unconscious (holster your weapon first). They sit down in shackles wherever they wake up.
- Stay shackled through waiting, saving and loading.
- Up to 16 prisoners at a time.

## Getting shackles
You need the vanilla item **Rusty Shackles** in Henry's inventory. General merchants and every bathhouse keeper sell them. To shackle without the item, set NeedItem = 0 in mod.cfg.

## Settings (mod.cfg)

- **Stealth** = 1: awake NPCs can be shackled from behind
- **Sleeping** = 1: sleeping NPCs can be shackled
- **Unconscious** = 1: unconscious NPCs can be shackled
- **NeedItem** = 1: Henry needs Rusty Shackles
- **Reach** = 2.2: how far away the NPC may be, in meters
- **Angle** = 35: how far off your line of sight the NPC may be, in degrees

Changes take effect the next time you load a save.

## Compatibility

- Replaces *AI/npc/basic/switch/switch.xml*. This file already includes the hooks for Silvertongue, Moneylender and Offering, so load Shackles after Offering. Any other mod that replaces this file will conflict. If you use Shouts, load it after Shackles.
- Adds button hints to *Libs/Config/defaultActionHelp.xml*. Load it after Wholesale and Reflex Throw.
- Works with Offering: a prisoner can still drink a potion you hand them. The drinking animation plays out, then they sit back down in shackles.
- Adds shackles to the stock of 14 shops (general merchants and bathhouses). Mods that change the same shop entries may conflict.
- The vanilla rope cuffs of the tied-up pose show up as iron shackles everywhere, vanilla scenes included. To keep the rope, delete Data/shackles_iron.pak.
- Languages: English, German.

Console:

```
wh_cheat_addItem cd61edb8-2674-4c3f-aa3b-c5067e6e2052
```

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3834194095)
