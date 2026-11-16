# Immersive Timeskip

# Wait with the time wheel **without the black screen**. Watch the world move on while the hours pass.

## What it does

- The vanilla time wheel stays exactly as it is: the turning clock, the effects on hunger, energy and health, the fade-out at the end.
- Behind the wheel, the world stays visible while time passes. The sun and the shadows move.
- People nearby stay visible and go about their day: people sitting at tables keep their routines, people who arrive walk normally. (The game would hide and freeze them.)
- Sleeping works the same way: the view stays where Henry lies, without the black screen when he lies down and wakes up.
- The wooden disc in the middle of the wheel is transparent, so you see the world behind the numbers and icons.
- When the wheel closes, the world returns to its normal brightness right away.
- Reading and forced time skips keep the vanilla black screen.

## Safe by design

- Every setting the mod changes is restored as soon as the wheel closes, and again whenever a save is loaded.
- If the mod's script is not running for any reason, the game simply falls back to the vanilla black screen.
- The mod does not change your save files.
- Emergency reset in the console: **immersive_timeskip_reset**

## Settings
Open **mod.cfg** in the mod folder. Changes take effect the next time a save is loaded.

- **Enabled**: 1 = world visible while waiting, 0 = vanilla black screen
- **UpdatesPerFrame**: 1 = smooth time-lapse (default). Higher values make waiting faster but choppier (up to 45, the game's own value).
- **KeepPeopleVisible**: 1 = people near Henry stay visible and keep moving while waiting (default), 0 = the game's behaviour
- **Sleep**: 1 = sleeping works the same way (default), 0 = vanilla black screen while sleeping

## FastForward users
If you also use the FastForward mod (hold Y to speed up the game), Immersive Timeskip watches the Y key. If the game misses the moment you let go of Y, it resets the game speed for you.

## Compatibility
Replaces these files, so it does not work together with other mods that change them:

- Libs/UI/SkipTime.gfx
- Libs/UI/UIElements/SkipTime.xml
- Libs/UI/Textures/SkipTime/skip_time_body.dds

The transparent wheel centre applies to every time wheel (sleeping and reading as well).

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3834043837)
