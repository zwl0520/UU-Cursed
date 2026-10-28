# UU Cursed — Unstable SMP

A Minecraft Java **1.21.11 Fabric** fan mod with Unstable SMP / Unstable Universe character mobs, meme voices, combat potions, faction armies, and a Far Lands expedition.

Created by **筑梦-星空 (Bilibili) / DreaminStars (YouTube)**.

[中文介绍](README.zh-CN.md) · [Download 2.0.0](https://github.com/zwl0520/UU-Cursed/releases/tag/v2.0.0) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/unstable-smp-cursed) · [Report a bug](https://github.com/zwl0520/UU-Cursed/issues)

## Downloads

| Version | Official GitHub download | China acceleration proxy |
| --- | --- | --- |
| **2.0.0 — current** | [Fabric 1.21.11 JAR](https://github.com/zwl0520/UU-Cursed/releases/download/v2.0.0/UU_Cursed_v2.0.0_Fabric_1.21.11.jar) | [Accelerated JAR](https://ghfast.top/https://github.com/zwl0520/UU-Cursed/releases/download/v2.0.0/UU_Cursed_v2.0.0_Fabric_1.21.11.jar) |
| **1.0.1 — previous 1.0 release** | [Fabric 1.21.11 JAR](https://github.com/zwl0520/UU-Cursed/releases/download/v1.0.1/UU_Cursed_v1.0.1_Fabric_1.21.11.jar) | [Accelerated JAR](https://ghfast.top/https://github.com/zwl0520/UU-Cursed/releases/download/v1.0.1/UU_Cursed_v1.0.1_Fabric_1.21.11.jar) |

The acceleration service forwards the official GitHub asset and is operated by a third party. Availability varies by network. Use the release's SHA-256 checksum to verify the file.

The public **2.0.0** release includes all gameplay and fixes from the latest development build, **2.0.9**. The JAR's embedded version is `2.0.0+mc1.21.11`.

## What can you play?

### Fight the cast

- **Wemmbu phantoms:** rocket-trailed mace dives, orbital strikes, bunker busters, totems, and Eggchan tail cargo. Exhausting both cannon supplies leaves them using only the mace.
- **Jaden drowned:** Riptide tridents, aerial mace attacks in rain, and underwater combat.
- **Spoke withers:** a revival totem, NULL soldiers emerging from portals, and concentric wither-skull bombardments.
- **Flame blazes and ghasts:** a forming fire sword, armored wolf reinforcements, totems, and TNT-minecart projectiles.
- Meet character parrots, axolotls, cats, wolves, wardens and slimes, including **Spoke cod** and **4CViT, Wifies and PlanetLord slimes**.

The mobs also fight one another. Discover voice triggers, unusual relationships, and **38 purple challenge advancements** through play.

### Use character powers

| Character | Playstyle |
| --- | --- |
| Wemmbu | Elytra/mace combat with orbital and bunker-buster rods |
| Flame | Sword/axe combat, fire bows and TNT minecart combos |
| Jaden | Repeated Riptide movement and falling mace attacks |
| Spoke | NULL guard escort |
| Lettuce | LAW guard escort |
| Ashswagg | Mafia guard escort |

For Wemmbu, Flame and Jaden, **I** provides assistance, **II** provides automatic control, and **III** permanently unlocks their modes in the **H** menu. Permanent bottles unlock abilities; activate a mode in H to use it. Guard roles have timed and permanent unlock bottles.

Active forms lend equipment and limited supplies. Your original inventory, name and appearance are restored when the form ends. Permanent unlocks also establish alliances with the matching character mobs.

[Read the potion recipes and ability guide](docs/ABILITIES.md).

### Explore beyond ten million blocks

The Overworld Far Lands begin where `max(abs(X), abs(Z)) >= 10,000,000`. Travel through towering walls, repeating terrain and dungeons, gravel, snowy spires, cherry forests, floating islands, biome mosaics, a void ocean, grass-block fractals and the void.

Follow the four coordinate-axis routes toward the **Golden City**. Its circular interior includes a resource library, meeting room, dormitory, arena, End Portal room and enclosed miniature world with classic Beta-era textures. Find looping story echoes along the way.

Inside the Far Lands, **M** opens a rotating navigation map. Beyond the first 500 blocks, fireworks stop boosting elytra; wind charges and ender pearls remain useful.

### Bring a pocket engineer

Village cartographers sell coordinate maps to the Mist and Far Lands. Show a map to a **4CViT slime**, or provide destination coordinates, to build a pearl cannon. Throw a pearl into the marked launch position and teleport after approximately ten seconds. Carry 4CViT in a slime bucket for later journeys.

## Install

1. Use **Minecraft Java 1.21.11**, **Java 21+** and **Fabric Loader 0.19.5+**.
2. Install **Fabric API 0.141.6+1.21.11**, or a newer Fabric API build specifically for Minecraft 1.21.11.
3. Put the release JAR and Fabric API into the instance's `mods` folder. Remove the previous UU Cursed JAR.
4. For multiplayer, update both the client and server.

Character textures, models and sounds are included. No separate resource pack, ETF, EMF or Unstable Generation installation is required. Far Lands terrain applies to newly generated standard Overworld chunks.

## Default controls

| Key | Action |
| --- | --- |
| **H** | Choose, activate or stop an unlocked character mode |
| **Shift** | Pause automatic control while retaining the active effect |
| **G** | Resume automatic control / select a pointed target where supported |
| **M** | Open the map while inside the Far Lands |
| **Milk** | Clear the active potion effect |

Key bindings can be changed in Minecraft's controls settings. For a quick look, use Creative search to find the character potions; cannon rods also appear in the Combat tab.

## Optional local music

Put your own `wemmbu.mp3`, `flame.mp3` and `war.mp3` files, or corresponding Ogg Vorbis files, in `config/uu_cursed/music/`. The fifth combined successful orbital or bunker-buster use in one Wemmbu activation switches to the war track. **No battle songs are bundled.**

[Music setup](docs/LOCAL_BATTLE_MUSIC.md) · [Challenge guide](docs/CHALLENGES.md) · [Release changes](CHANGELOG.md)

## Credits and reports

This is an unofficial fan project. It does not imply endorsement by the featured creators. Original code and third-party assets have separate terms; see [LICENSE](LICENSE), [CREDITS.md](CREDITS.md), and the attribution files bundled in the JAR.

Please credit **筑梦-星空 / DreaminStars** when sharing gameplay videos. Include your Minecraft/Fabric/mod versions, reproduction steps and relevant logs when [reporting a bug](https://github.com/zwl0520/UU-Cursed/issues).
