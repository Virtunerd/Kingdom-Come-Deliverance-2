# Shouts

[h1]The vanilla battle cry finally does something. Use it on frightened witnesses and they give up, use it in a brawl and your enemies turn on each other.[/h1]


[h2]Witnesses[/h2]
- Witnesses who saw Henry commit a crime and now run off to report him, go to fetch help against him or flee from him react to the battle cry.
- People who report something without a known culprit, such as a body they found, are not affected.
- Men drop to their knees and beg for mercy. This uses the vanilla surrender behaviour, quick chat and mercy dialogue.
- The game has no surrender animation for women, so female witnesses cower in fear instead (vanilla cower animation). Like men, they get the vanilla quick chat, so you can release them.
- Outside of combat, and also right after a fight, the battle cry only shows up in the chat while such a witness is within range (30 m by default). Surrender and taunt stay combat-only, as in vanilla.

[h2]Turncoats[/h2]
- In a fight against two or more foes, the battle cry turns every foe except the one you are locked on into an ally.
- They attack the remaining foe.

[h2]Settings[/h2]
Edit **mod.cfg** in the mod folder. Changes take effect the next time a save is loaded.
- **Witnesses** = 1: witnesses kneel or cower (0 = off, the battle cry then behaves as in vanilla)
- **Convert** = 1: foes switch sides in a fight (0 = off)
- **MinFoes** = 2: foes needed before they switch sides (2 to 10)
- **Range** = 30: how far the battle cry reaches in metres (5 to 60)

[h2]Compatibility[/h2]
- Replaces the three vanilla battle cry chat dialogues. Only a script call and the witness condition are added.
- Replaces the vanilla report, flee and return-with-help behaviours (**interrupt_report.xml**, **interrupt_flee.xml**, **interrupt_returnwithhelp.xml**). Only a notice to the script is added.
- Replaces **AI/npc/basic/switch/interrupt_mercy.xml**. Only a switch for women is added.
- Replaces **AI/npc/basic/switch/switch.xml**. This file already contains the hooks of my mods Silvertongue, Moneylender, Offering and Shackles, so they keep working.
- Adds a Storm rule that gives women the vanilla surrender chat role.
- **Load order:** Shouts must load after Shackles, Offering, Silvertongue and Moneylender.
- Conflicts with any other mod that replaces one of these files.

[h2]Changelog[/h2]
- **1.0.4:** Turncoats attack right away without the costly vanilla reconciliation, which caused a heavy frame drop.
- **1.0.3:** Only witnesses who want to report Henry count. Reports without a known culprit, such as a body found, no longer unlock the battle cry.
- **1.0.2:** Cowering women can be released with the vanilla quick chat. The battle cry is no longer available after a fight unless a witness is nearby. No more area scans during combat.
- **1.0.1:** Female witnesses cower in fear instead of fainting.
- **1.0.0:** Initial release.