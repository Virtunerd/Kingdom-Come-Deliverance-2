# Athleticus

**Download:** [athleticus.zip](https://github.com/Virtunerd/Kingdom-Come-Deliverance-2/releases/download/kcd2/athleticus.zip)

Henry gets a double jump and pulls himself up onto high ledges.

Press jump again in mid-air for a second jump. In the air, Henry grabs edges in front of him that are too high for the game's own vaults (rocks, walls, roofs) and climbs onto them, automatically when he faces the edge or with the jump key.

Invisible player-only walls are ignored - map edges, deep water and quest barriers stay.

## Settings

Settings in mod.cfg.

```
-- Double jump
#AthleticusCfg.DoubleJump = 1          -- 1 = on, 0 = off
#AthleticusCfg.AirJumps = 1            -- extra jumps in the air before Henry lands again
#AthleticusCfg.DoubleJumpHeight = 1.6  -- m, height of the extra jump
#AthleticusCfg.DoubleJumpDelay = 0.12  -- s in the air before the extra jump is possible

-- Ledge pull-up
#AthleticusCfg.LedgeGrab = 1           -- 1 = on, 0 = off
#AthleticusCfg.AutoGrab = 1            -- 1 = grab automatically when facing an edge in the air, 0 = only with the jump key
#AthleticusCfg.VanillaHeight = 1.5     -- m above the take-off ground; lower edges are left to the game's own vaults
#AthleticusCfg.MinLedgeHeight = 0.3    -- m above Henry's feet, lowest edge he grabs in the air
#AthleticusCfg.MaxLedgeHeight = 2.2    -- m above Henry's feet, highest edge he can reach
#AthleticusCfg.GrabReach = 0.9         -- m, how far in front of Henry the wall may be
#AthleticusCfg.ClimbSpeed = 1.0        -- speed of the pull-up (0.25 - 4)
```

---

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3832491790)
