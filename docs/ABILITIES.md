# Role potions — Java 1.21.11 / Fabric, public release 2.0.0

## Durations and controls

| Role | I / timed bottle | II | Permanent bottle |
| --- | --- | --- | --- |
| Wemmbu | 5 minutes, elytra/mace assistance | 3 minutes, elytra/mace autopilot | III unlocks both modes in H |
| FlameFrags | 5 minutes, sword/axe and requested minecart assistance | 3 minutes, sword/fire-bow/minecart autopilot | III unlocks both modes in H |
| Jaden_MAN | 5 minutes, falling-mace assistance | 3 minutes, riptide/mace autopilot | III unlocks both modes in H |
| SpokeIsHere | 5 minutes, NULL guard escort | No tiers | Permanent escort unlock in H |
| LettuceK | 5 minutes, LAW guard escort | No tiers | Permanent escort unlock in H |
| ashswagg | 5 minutes, Mafia guard escort | No tiers | Permanent escort unlock in H |

H opens individual role pages. Permanent bottles only unlock that role: they never activate a form, play a transition or change equipment. Unlocks persist across saves and death.
Choose a mode to activate it, or Return to yourself to stop it. Shift releases
automatic control while keeping the active potion and loan gear; G resumes.
Milk removes the current effect (release automatic control with Shift first).
Flame and Jaden leave the ninth hotbar slot free
for your own tools, milk or other items. Only one character form controls the player at a time.

Every active character form grants native Strength II (+6 melee attack damage), including I/II and the three guard roles. H-enabled permanent forms grant the same buff. Unlock-only bottles do not activate combat buffs. Disabling a form expires only its temporary Strength; existing stronger effects are preserved and a hidden weaker original effect resumes with its naturally remaining duration.

Both I and II provide temporary character equipment. Original occupied inventory
slots, armor, offhand, names and skins are restored when the effect ends. The
cinematic keeps the original equipment visible until the image covers the scene.
Consumable supplies are finite and their remaining quantities survive saving.

## Combat and guards

Wemmbu I and II each receive ten orbital-cannon rods and ten bunker-buster rods in the hotbar. Each use consumes one rod, including in creative mode; player rods have no ten-second cooldown and can be fired consecutively or alternated immediately. I permits manual aiming at a block within 64 blocks. II selects artillery for groups of at least four grounded enemies: orbital rings for exposed groups, the dimension’s complete build-height drill column for covered groups (Overworld Y−64 through Y319). It retreats before firing and holds clear until the charges finish; this safety maneuver does not block manual firing. Ammunition is finite across I/II switches and real save/reopen, and the original displaced hotbar contents return when the form ends. Drill block destruction uses ordinary TNT resistance: obsidian and similarly resistant blocks survive, and liquids retain their native blast shielding. Its column still covers the complete dimension build height. Phantom artillery retains its ten-second cooldown. A successful orbital or bunker-buster use also starts the local Wemmbu battle track; the fifth combined successful use in one activation switches to the local war track. Failed launches consume no ammunition and do not count; payload size does not multiply the count. Client and server must both run this update.

Flame has The Flame, Inferno, Incendiary, trimmed netherite armor, rails, TNT
minecarts, pearls, golden apples, 256 arrows and ten ordinary totems. In I, hold a rail or TNT minecart, aim at a target 5–15 blocks away and hold Use: assistance places a real rail/cart and ignites it with the supplied fire bow without taking over movement. Keep at least 2.5 blocks clear; after the shot the original hotbar slot is restored. II places a
real rail and TNT cart, faces it while withdrawing, and ignites it with a real 10-tick Flame-bow shot. Server placement cooldown is 24 ticks; ground support, reach, ammunition and an unobstructed firing lane still apply. Placement favors multiple enemies in blast range. If a body or shield blocks the ignition lane, it resumes melee instead of wasting repeated weak shots.
It uses charged sword/axe attacks up close and pearls away to eat when low.
Its own loan carts cannot damage the caster. Dropped maces and elytra attract
Flame blazes/ghasts; the mobs deliberately destroy these items, including the
normally fireproof mace. Items inside a player's inventory are unaffected.

Jaden has diamond armor, a Riptide III / Impaling V trident, a Density V / Wind
Burst III mace, sword, water bucket, pearls, golden apples and ten ordinary
totems. II uses native Riptide physics in rain or water and lands falling mace
attacks. It uses the native ten-tick charge and aims for one Riptide every twenty ticks while wet, repeatedly charging and releasing the trident to gain the needed height and correct lateral drift toward the target. It then commits to the predicted falling-mace intercept instead of cancelling the strike with another Riptide. Snowfall and dry air retain the vanilla restriction on Riptide. An imminent reachable mace strike takes priority over the bucket, while missed dives begin ground checks early and flick down within actual bucket reach. On dry Overworld ground it uses its real water bucket and recovers its placed
source at takeoff when still within native bucket reach; water cannot be
placed in the Nether, where it falls back to melee. I leaves movement and aiming
to the player and assists a qualifying falling-mace attack. Both modes place water through the native bucket action when a missed descent approaches solid ground; their own water source can be recovered once landed.

Support roles initially summon twenty friendly guards. When fewer than ten
remain alive, the group replenishes to twenty; exactly ten does not trigger reinforcements. NULL first opens a visible, owner-facing Nether portal after the transition, then sends soldiers out through the purple interior in batches. They physically leave the floating gate before gravity and normal combat AI resume. NULL reinforcements and replacements after distant travel use the same portal route. LAW and Mafia appear directly at safe nearby positions for both initial summoning and refills. They defend the
owner, attack the owner's chosen enemy and follow across ordinary travel. LAW
and Mafia retain their no-block-building behavior. Turning the ability off
retires its guards. Each support kit has ten ordinary totems, followed by one
face-themed enchanted totem that restores half health when consumed. Native
protection does not reset the potion timer or grant a fresh kit.

## Brewing

Start with an Awkward Potion:

| Ingredient | Result |
| --- | --- |
| Firework Rocket | Wemmbu I (5:00) |
| Wolf Armor | Flame I (5:00) |
| Raw Cod | Jaden I (5:00) |
| Mace | Wemmbu III (unlock only) |
| Netherite Sword | Flame III (unlock only) |
| Trident | Jaden III (unlock only) |
| Totem of Undying | Spoke (5:00) |
| Shield | Lettuce (5:00) |
| Invisibility Potion (regular or extended) | Ashswagg (5:00) |

Wemmbu I + Elytra → Wemmbu II (3:00).
Flame I + TNT Minecart → Flame II (3:00).
Jaden I + Water Bucket → Jaden II (3:00).
A support role's timed potion + Nether Star → that role's permanent unlock.
Ash requires a drinking potion containing Invisibility; water or any other potion will not work.
Ordinary native Gunpowder / Dragon's Breath conversions give splash / lingering versions.
The public catalog exposes only the longest Wemmbu I and II bottles. Legacy
short-duration registry IDs remain readable for existing worlds.

## Art and equipment sources

Approved character skins are reused from the project's existing references.
New role images are rendered with Minecraft's own player model and equipment;
the selector reuses the transition image, blurred and darkened, with an actual
rotating armored player preview on the right.

Flame weapon names and enchantments were checked against:
https://unstable-universe-mc.fandom.com/wiki/FlameFrags

Trident/mace character association:
https://unstable-universe-mc.fandom.com/wiki/Tridents
https://unstable-universe-mc.fandom.com/wiki/I_Got_BETRAYED_on_a_Hardcore_Minecraft_SMP

Armor material, model width and known trims match the project's previously
approved echo actors. Jaden's implemented weapon enchantments are gameplay
choices, not a claim of an exact inventory from a particular episode.

## Permanent alliances (2.0.2)

Permanent potion unlocks also establish diplomacy while the active ability is off. Wemmbu: phantoms, Wemmbu parrots and axolotls; Jaden: drowned; Flame: blazes, ghasts and their wolves; Spoke: cod, withers and their NULL troops; Lettuce: Lettuce cats and their LAW troops; Ash: dragons and their Mafia troops. Guards belonging to another player are not reassigned.

When an unlocked player is actually attacked, matching, AI-enabled creatures within a 50-block sphere defend that player. Nearby allies sharing that protected player do not target or hurt each other. Distress calls expire after 30 seconds, upon the attacker dying, or when the player leaves; they do not tame or make wild mobs persistent. Permanent friendly status survives logout and death through the existing unlock save data. Manual player attacks remain possible; friendly creatures do not retaliate, and automatic ability pilots skip them.

Phantoms and drowned ignore sunlight ignition only; ordinary fire damage remains. Native phantom spawning no longer reads insomnia as a requirement, including on the first night, and uses the original 60–120 second interval and group sizes. Spawn attempts stop once six live phantoms are within 96 blocks of the player (a final group can take the local total up to nine). Creative and spectator players do not attract spawns; explicit spawn settings and peaceful difficulty remain respected.
