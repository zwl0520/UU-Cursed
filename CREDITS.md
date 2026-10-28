# Project author / 模组作者

- Bilibili / B站：**筑梦-星空**
- YouTube：**DreaminStars**

These are the project author's accounts. The third-party creators and sources below retain their own credits and rights.

# Sources

Local MP3 playback uses unmodified JLayer 1.0.1 (JavaZoom and contributors),
LGPL-2.0-or-later. The separately replaceable library, full corresponding source,
license and notice are bundled under `META-INF/jars/` and
`META-INF/licenses/jlayer/`. This library is not covered by the project's MIT
license. User-supplied music is not included or transmitted by this mod.

This is an unofficial Unstable Universe fan project.

- SpokeIsHere: pinned public account skin, UUID
  `734abedf785e4424a42b32f953c3c78d`.
- 4CVIT: pinned public account skin, UUID
  `7663199ff927422da38a065b0d26121f`.
- Wemmbu: pinned public account skin, UUID
  `8af6c50833d54861b5c2dce1c16c6fae`.

Exact Mojang texture URLs and SHA-256 hashes are recorded in
`references/sources.json`. Head and clothing pixels are reprojected into new UV
layouts. Their rights remain with the respective creators. No textures from
another fan resource pack are included.

The cod retains vanilla part names, pivots, and tail animation through the
Minecraft renderer; its wider body and face are this project's model design.
Slime scaling, squish, hurt overlay, and invisibility follow the vanilla
renderer. The Minecraft game and its assets belong to Mojang/Microsoft. The
bucket item loads the game's cod-bucket texture beneath a fish-only skin-pixel
overlay. The source ZIP contains one 16x16 Mojang bucket reference for UV
placement, plus one vanilla elytra texture reference used for the optional gray
wing material. Those references and their pixel derivatives retain
Mojang/Microsoft's rights. No game binaries are redistributed.

The cod, phantom, drowned, and pig spawn eggs reference the game's own egg models and
textures unchanged. Their face decals reuse the pinned Spoke/Wemmbu/Jaden/SirPig skin
avatar textures through composite item models.
The axolotl spawn egg uses the game's own egg base with a three-frame portrait
decal of Wemmbu, PrinceZam, and Fantst.

Fabric API and Fabric Loader are external dependencies, not bundled here.

The 1.2-second **"MACE ATTACK!"** voice clip is attributed to Wemmbu by its
public community source, uploaded by ChannelMajorMajor37674 on Voicemod Tuna:
https://tuna.voicemod.net/sound/542b5ebe-33ba-4664-9394-80cbacfa122c
The original source video/timecode has not been independently established.
The MP3 was downloaded directly from that sound page's public audio URL, then
converted to mono 48 kHz Ogg Vorbis for Minecraft's positional audio; timing
and pitch are unchanged. Source URL, uploader and both file hashes are pinned
in `references/audio/sources.json`. The recording remains third-party content
and is excluded from this project's MIT license. No other resource pack's
audio files were extracted or reused.

Gradle wrapper: Gradle, Apache-2.0. Documentation:
https://docs.gradle.org/9.2.1/userguide/gradle_wrapper.html

## Jaden_MAN

- 使用之前保留的 43 人图鉴中的 `Jaden_MAN` 皮肤，UUID `c4c1ab67898a4476ba941b1d42f89981`。
- 原始 PNG 固定于 `references/Jaden_MAN.png`，来源 URL 与 SHA-256 记录在 `references/sources.json`。
- 贴图通过原始皮肤 UV 转换和衣服外层合并得到，脸部像素保持原样；所有溺尸均使用该 Jaden 贴图。
- 这份素材对应公开账号快照，未另行核对具体视频时间点；fan-made，无官方关联。皮肤素材不适用代码的 MIT 许可。

## SirPig_

- 使用保留的 43 人图鉴中 `SirPig_` 的绿色猪头、黑西装、红领带皮肤，UUID `3f4eeb1df1804e29a3bd962e32dee828`。
- 原始 PNG 固定于 `references/SirPig_.png`，来源 URL 与 SHA-256 记录在 `references/sources.json`。
- 原始头像像素重投影到原版猪头及突出鼻子 UV；服装适配温带、暖地、寒带猪和幼猪。猪刷怪蛋复用同一原始头像。
- 上一轮生成的猪／青蛙对比图仅为外观方向参考。模组内的纹理由原皮肤 UV 转换得到，使用原版猪的实际几何。
- 皮肤素材的权利仍属于原作者，不适用代码的 MIT 许可。

## PrinceZam、Fantst 与美西螈

- `PrinceZam`，UUID `cae282bbaf8e4b26822f556100c1d215`：使用之前图鉴筛选的黄色皇冠历史皮肤 `reference/PrinceZam_fd6bcfdf381f9caf.png`，固定副本位于 `references/PrinceZam.png`；当前账号的其他换装不用于本次制作。
- `Fantst`，UUID `2c3dc4e92c7b44e7941b5004b3cee426`：使用图鉴保留的紫色、蓝围巾账号快照，固定副本位于 `references/Fantst.png`。该固定 PNG 的前脸没有白眼；没有自行补绘五官。
- `Wemmbu` 美西螈复用已有 `references/Wemmbu.png`。
- 原脸像素与衣服重投影到美西螈原版 UV。原版鳃、尾巴、脚部的透明轮廓来自 Minecraft 1.21.11 的 `axolotl_lucy.png`；参考副本固定于 `references/art/vanilla_axolotl_lucy_1.21.11.png`，其像素衍生保留 Mojang/Microsoft 的权利。
- 皮肤来源、选择及 SHA-256 在 `references/sources.json`，轮廓参考哈希在 `preview/asset-report.json`。人物皮肤素材保留原作者权利。

## Spoke 凋零、Saparata 与人物鹦鹉

- Spoke 凋零三颗头和凋零之首复用固定的 `references/SpokeIsHere.png`。
- Saparata（Saps）使用 Mojang 公开账号 `saparata` 的皮肤快照，UUID `296d434fe7814d449b66469eab9d9bfe`；原始皮肤与账号资料在 `references/Saparata.png`、`references/Saparata-profile.json`。皇冠直接复用皮肤帽子层的镂空金纹和红色宝石像素，使用单独渲染层以支持剪下；成年乐魂的挽具只显示为皇冠。
- ParrotX2、TheobaldTheBird（Theo）复用之前核对并保留的皮肤图鉴素材，固定为 `references/ParrotX2.png`、`references/TheobaldTheBird.png`；Wemmbu 沿用已有快照。
- V0.6.1 将 Parrot 的原帽子层独立绘制，使其能与 Saparata 小乐魂互换；两种皇冠均保持各自原始像素。V0.8.0 的全部雪球统一采用 Eggchan 圆形头像，替换早期 Saparata 方头雪球。
- 新增素材 URL、UUID 和哈希在 `references/crowned-sources.json`，原脸与贴图校验在 `preview/crowned-asset-report.json`。没有从别人的材质包提取贴图。原版凋零、雪傀儡、乐魂、鹦鹉参考纹理及其像素衍生仍保留 Mojang/Microsoft 的权利；人物素材保留各自原作者的权利。

## 鹦鹉梗语音

三段录音来自 Voicemod Tuna 公开社区声音页，分别裁成 1.68、1.92、1.35 秒并转为单声道 48 kHz Ogg Vorbis，未改变音高。Biggest Bird 使用原录音后面的一句（1.90～3.82 秒）。来源 MP3、URL、剪辑区间与 SHA-256 均在 `references/audio/parrot-sources.json`。

## V0.8.0 物品、人物外观与 SargeLAW 语音

- 固定使用先前人物图鉴中的 SargeLAW、Arachnid（`arachn1d_`）、Yungyx、Eggchan、FlameFrags、ClownPierce、MinuteTech、JumperWho、ItzRealMe、ManePear、LettuceK。Arachnid 来自图鉴归档的紫色蜘蛛脸皮肤；其余使用保留的原始 PNG。
- 十一份原始皮肤位于 `references/`，图鉴来源路径及 SHA-256 固定在 `references/extended-sources.json`。没有从别人的材质包提取纹理，也没有补画原头像的五官。
- 生物贴图按照 Minecraft 1.21.11 原版模型的实际 UV 重投影。圆形物品保留原版透明轮廓，时钟保留金色外框和动态表盘，ManePear 梨为原头像像素适配出的物品轮廓。原版纹理参考和像素衍生保留 Mojang/Microsoft 的权利；人物皮肤素材保留原作者权利，均不适用代码的 MIT 许可。
- “For my brother!” 原始录音来自 https://tuna.voicemod.net/sound/cf52e488-0c24-4694-bf27-b963478a6450 ，社区页面标注为 SargeLAW。录音短句已用本地识别核对，但未独立核实原视频说话者和时间点。
- 源录音裁取 0～1.75 秒并转为单声道 48 kHz Ogg Vorbis，音高不变，结尾淡出 20 ms。MP3、转换结果和哈希记录在 `references/audio/sarge-source.json`；该第三方录音不适用项目代码的 MIT 许可。

- “No, it's Thursday, bro.”：https://tuna.voicemod.net/sound/6649fb9f-fd0e-43c3-91b1-cbd10c3e5367
- “I'm the biggest bird.”：https://tuna.voicemod.net/sound/a32e1c5b-a542-40bf-8bd4-a09c5a8c236c
- “it's all yours”：https://tuna.voicemod.net/sound/608a0f51-1c48-49c3-a6bc-bd89da77ef75

本地语音识别用于核对短句和剪辑点，未独立核实原视频的说话者及时间点。社区录音不适用项目代码的 MIT 许可。


## V0.8.0 人物扩展

- ManePear → 豹猫；Ashswagg → 末影龙；Boosfer → 流浪商人；TheG0DofWar → 凋零骷髅；Lomedy → 村民；WyLL_ → 青蛙；Marlowww → 监守者；Spongs → 苦力怕。
- 使用保留的 43 人图鉴素材。Ashswagg 和 Boosfer 使用已核对的历史皮肤，其他人物使用图鉴固定皮肤；未重新编造脸部五官。八份原始 PNG、图鉴路径、来源 URL、UUID 与 SHA-256 在 `references/expansion-sources.json`。
- 保留全部原版几何、UV、动画与对应交易、变种机制。龙的面部标记与监守者心跳发光层来自对应人物原皮肤像素；原版透明翼膜、脚掌、肋骨和触须遮罩仍保留 Mojang/Microsoft 的权利。人物素材保留各自原作者的权利。
- 三次图腾使用 Minecraft 原生 death-protection 机制，没有提取其他模组或材质包实现。

## V1.0.0 Wifies、PlanetLord 与原生行为

- Wifies 使用之前已核对的历史皮肤 `references/Wifies.png`（NameMC `5e8bf06a25bbc1ab`），用于狼、史莱姆及两个成就图标。嘴来自底层原像素，按原帽子层的 9/8 几何扩张投影保留。
- PlanetLord 使用 Mojang 官方账号 `79cbd6b6eac942019ff5c029075fcace` 的皮肤 `references/PlanetLord.png`，资料快照、官方来源与 SHA-256 在 `references/PlanetLord-profile.json`、`references/expansion-sources.json`。该新增快照不是早先 43 人图鉴素材，未声称已核对 Unstable 视频帧。蓝紫头带与原嘴按同样方式投影。
- 月亮保留 1.21.11 八张原生月相的明暗遮罩；望远镜使用原版物品、导航／史莱姆跳跃、装备同步与存档；Spoke 凋零的手臂使用固定 Spoke 原皮肤像素。不从其他模组提取实现或纹理。
- 五段发行 Ogg 的本地解码与离线识别记录在 `references/audio/research/meme-audio-audit-1.0.0.json`。识别文字不构成原视频人物来源核实。

## V1.0.1 无战斗音乐发行版

Wemmbu、Flame 的两段邻近战斗音乐已移除，包括音频文件、声音注册和客户端自动播放逻辑。发行 JAR、启动器实例和源码 ZIP 不包含这两段音乐或它们的原始试听录音。五段梗语音及既有第三方素材权利说明保留。
# Far Lands expansion — 1.1.0

The classic Far Lands foundation is adapted from ThePotatoArchivist's **Classic Farlands 1.2.0+mc1.21.11** (MIT): https://github.com/ThePotatoArchivist/ClassicFarlands and https://modrinth.com/mod/classic-farlands/version/77buAuMT. Its original copyright and full MIT terms are shipped as `LICENSE-ClassicFarlands.txt`. The adaptation restores unwrapped Perlin sampling only around a dedicated, seeded old-blended-noise instance, relocates it to the UU route, and retains the old-overworld top/bottom density slides. It does not bundle Classic Farlands, its configuration libraries or its mod entrypoint.

The fallback region variants, repeated dungeons, golden-city architecture and atlas are independent UU implementations. Narrative/visual references include Wemmbu's 2025 Farlands/Fartherlands/END/Void exploration videos and public community screenshots. Unstable Generation's public gallery was used to compare terrain categories. No Unstable Generation source, class, resource or JAR is redistributed. Its published ARR metadata and inconsistent in-JAR CC0 label were not treated as permission to port its implementation. The generation is not a block-for-block recreation of the official UU world.

Optional UG compatibility invokes the separately installed **Unstable Generation 1.0.7** by Tsunddere at runtime, using detached native chunks and its own noise, surface and feature hooks. Reference build: https://modrinth.com/mod/unstable-generation/version/bZpYJZqW (original SHA-1 `9dd0baa1a601e433e5dfab71ba4c73b9168e9dc0`). Compatibility code adapts positions, orientation and route overlays; it neither embeds nor ports UG's terrain algorithms. The standalone fallback remains available without that dependency. Source-coordinate chunks are generated only in memory; they are not world downloads or upstream assets. Project: https://modrinth.com/mod/unstable-generation .

Source provenance is recorded in `research/classic-farlands-mit-2026-10-15` and `research/farlands-implementation-2026-10-15` in the project workspace. The golden city is an original interpretation, not an official build or a block-for-block copy.

`data/uu_cursed/loot_table/chests/repeating_dungeon.json` adapts Minecraft Java 1.21.11's vanilla simple-dungeon loot data, retaining its ordinary loot while guaranteeing exactly two enchanted golden apples. Minecraft blocks, models and original loot data belong to Mojang/Microsoft. No third-party terrain mod, world download, schematic or reference screenshot is embedded in the release.

## Golden palace reference and Java Beta 1.7.3 exhibit

The revised white-and-gold rotunda is informed by the original thumbnail of Wemmbu's **I Explored Beyond the Minecraft Void** (https://www.youtube.com/watch?v=QhxnImk2GFQ), publicly republished with a transcript at https://www.minenest.com/523627/. The thumbnail establishes the monumental white columns, golden domes and satellite cupolas; the transcript confirms the old-texture world exhibit. No complete interior reference or dimensioned floor plan was obtained. The stock library, meeting hall and 100×100 exhibit follow the user's requirements and are original interiors, not a verified replica of the original build. The reference image is not included in the mod.

The small-world exhibit temporarily selects a pack made locally from the official Minecraft Java Beta 1.7.3 client: https://launcher.mojang.com/v1/objects/43db9b498cb67058d2e12d394e6507722e71bb45/client.jar (SHA-1 `43db9b498cb67058d2e12d394e6507722e71bb45`, 1,465,375 bytes). The mod distributes only asset-name mappings, download/extraction logic and verification metadata; neither the old client nor its original texture pixels are bundled. Those assets remain Mojang/Microsoft's property and are outside the project's code license. Runtime extraction reads only whitelisted image entries and crops the original terrain atlas; it never executes old classes. Newer blocks retain modern textures, and old fluid animation is not reproduced.


## Far Lands echoes — 1.2.0

The five historical tableaux and their movement, route selection and projection logic are original implementations requested by the user. Episode references: Wemmbu's *I Explored Beyond the Minecraft Farlands* (https://www.youtube.com/watch?v=C2LjQWaKZek), *I Explored Beyond the Minecraft Fartherlands* (https://www.youtube.com/watch?v=kpUHhYpHolg), *I Explored to the END of the Minecraft Farlands* (https://www.youtube.com/watch?v=UC17MxP9b0A), and *I Explored Beyond the Minecraft Void* (https://www.youtube.com/watch?v=QhxnImk2GFQ). No episode video, speech, music or third-party replay mod is bundled.

The bundled replay skins are the six unchanged Wemmbu, eggchan, FlameFrags, Jaden_MAN, WyLL_ and conexion references already retained in the user's skin library. Creator identities and skins remain their respective owners' work. Representative equipment is informed by the fan-maintained armor-trim catalogue at https://unstable-universe-mc.fandom.com/wiki/Armor_Trims_%28by_Characters%29 and player discussions. User instructions explicitly prioritize iconic equipment over episode-date matching. The replay is a fan-made interpretation, not an official recreation or a frame-accurate replay.


## V1.3.0 story expansion

Village farming, crop-only Spongs sabotage, coordinate maps, pearl-cannon travel, the Mist, the Underworld and offset mushroom portals are independent implementations informed by public community descriptions. Castle and forest are original reconstructions; the pearl cannon imports the CC0 build credited below. These are not the official UU world map. See `STORY_REFERENCES.json` for URLs and verification limits. The initial white LAW sun used an unverified black fan emblem; v1.5.3 supersedes it with the community white/yellow native-layer recipe credited below. Native Minecraft block textures/models are referenced by identifier, not copied into these new build assets. No new music or voice recordings are added.


### Imported pearl cannon — mor_doc, CC0-1.0

[Breeze360FTL MKII](https://github.com/mor-doc/Breeze360FTL_MKII), commit `84974e91527c78213c228d23259fac8bfd18da8e`, schematic `360BreezeCannon MKII v1.0.0.litematic`, by **mor_doc**. Upstream dedicates the work to the public domain via CC0. Full dedication is included as `LICENSE-Breeze360FTL.txt` in the mod JAR. We import the34×43×17 block geometry, freeze circuit components as static visual blocks, strip all entities/block entities, commands, sign text and water, and add our dry, marked upward pearl chamber/base. Our map interaction and200-tick travel code provide the actual teleportation. No upstream calculator or executable is run or bundled. Source hash and changes are recorded in `STORY_REFERENCES.json`.

The revised portal forest is informed by the gameplay screenshot at https://www.reddit.com/r/Unstable_Universe/comments/1wnn3n1/was_this_parrots_civilization_or_is_this/ . The still was viewed for giant wooden trees, green crowns, pink/purple foliage and stone paths. Its destroyed foreground is not reproduced; exact portal-facade details remain an interpretation. The reference screenshot is not bundled in the mod JAR.

## Main menu slideshow and UU dialogue (1.3.1)

15 actual video covers by Wemmbu and FlameFrags, sourced from publicly posted
creator update screenshots, episode artwork on IMDb, and the Unstable Universe
community wiki. These are not generated replacements. Exact image URLs, source
pages, SHA-256 hashes, runtime source rectangles and image dimensions are pinned
in `MENU_REFERENCES.json`. The original cover pixels are converted losslessly to
PNG for Minecraft's decoder. Runtime UV framing removes surrounding video-list
UI; a native six-pass GPU blur is applied before the sharp title-screen widgets.
One FlameFrags entry is the creator's marathon stream cover.

The first 18 short splash lines are common community transcriptions cited individually
in that manifest, with punctuation/case normalized. They are not claimed to be an official frame-by-frame transcript; one
community line has no independently verified speaker. No voices or music were
added for this menu. Thumbnail artwork and dialogue retain their respective
creators' rights and are excluded from this project's code license.


## V1.4.0 battle expansion and local death notices

The faction AI, finite arsenals, hidden phantom revivals, per-pair ceasefires, gradual steering, blaze sword formation, cargo tail, drill-charge behavior and local notifications are independent implementations. New character textures project actual pinned skin pixels onto native models. Kenadian uses the public Mojang profile `_Kenadian_`; Leow0ok and Horace_Altman use the previously retained skin references. Texture source hashes are in `references/battle/sources.json`. Names in death notices follow the retained game-profile spelling, including Marlowww and WyLL_. The initial LAW shields reused that fan emblem. Version 1.5.3 replaces it with native yellow Flower Charge / white Bordure Indented layers and migrates old LAW soldier shields. No new recorded audio or music is included.

### External orbital machine geometry

[HyperOrbitalStrikeCannon MK.1](https://github.com/eronbubi/HyperOrbitalStrikeCannon), pinned commit `9eedcde4e8bca165f5bcf42859cc28b0d64b1fa8`, `out/osc_west_overworld.litematic`, repository maintainer **eronbubi**, schematic metadata author **Claude**. The complete 4,134-block, 69×52×49 geometry is retained and rotated for each border axis. No upstream Python generator, RCON client, fire-control calculator or executable is run or bundled. Circuit components are frozen native-model visual aliases, source water becomes light-blue glass, source TNT becomes inert display TNT, and container/entity data is omitted. Runtime attacks and pearl travel remain our server-side logic. The upstream repository does not include an explicit license; no redistribution license or authorship transfer is inferred, and this material is excluded from this project's code license. Exact source hash and changes are included as `ORBITAL_BLUEPRINT_SOURCE.json`.


### UNSTABLE SMP title artwork

The replacement title was generated as original UNSTABLE SMP lettering, using the installed Minecraft title as a visual reference for the stone faces, cracks and dark extrusion. It replaces the former chat-font rendering. Only the new title image is bundled; the reference logo file is not added to this mod. Runtime UV framing removes transparent margins.

## V1.5.0 Wemmbu potions

The six native potion registrations, real-stack equipment swaps, server-validated targeting, client-driven native elytra/mace pilot, temporary display-name and skin projection, and real-time cinematic compositor are original implementations. No equipment, rockets, or inventory backups are generated by the potion controller. Temporary identity display does not alter the authenticated game profile or UUID.

The player skin and two effect icons reuse the existing pinned Wemmbu skin and face already credited above. The transition reuses the already bundled Wemmbu video covers catalogued in `MENU_REFERENCES.json`; no new cover or recording is downloaded. Its impact sound references Minecraft's built-in `entity.warden.sonic_boom` event. All five existing meme Ogg files remain byte-identical to v1.4.0. No additional music or speech is included. Existing creator and Mojang asset rights remain unchanged and outside the code license.

## V1.5.1 borrowed kit and automatic defensive combat

Wemmbu II now lends marked, temporary equipment and provides native firework boost projectiles, replacing the v1.5.0 inventory-only rule for grade II. Persistent player-owned escrow holds only the displaced real slots, with native save/load codecs and ordinary death-drop handling. Threat selection reads native Mob targets and Brain attack memories; it does not infer hostility from a skin or a character name. The diamond/netherite-dune visual style reuses the existing echo equipment reference, while enchantments and the temporary Crucible mace are this mod's gameplay configuration, not a claim of episode-accurate inventory. No new external asset, recording or music is added. Grade I retains its real-inventory-only behavior.

## V1.5.2 faction NPC targeting

The existing NULL, LAW and Mafia `FactionSoldier` entity type is an explicit proactive target for Wemmbu II within 64 blocks, including native-invisible Mafia soldiers. Player-owned/allied NPCs are excluded through the NPC's existing friendly relationship check. This exception does not classify actual players as soldiers and does not change ordinary mobs' aggro requirement. No new asset, audio or external implementation is introduced.

## V1.5.3 LAW white banner, shield and square sun correction

The white-field design follows the public community recipe “Law unstable by Peytondino4”: https://www.planetminecraft.com/banner/law-unstable-by-peytondino4/ . Its editor code `gcbg8` represents a white base, yellow Flower Charge and white Bordure Indented: https://www.planetminecraft.com/banner/?e=gcbg8 . This is a decoded community reconstruction, not an official UU world export or verification of every episode’s flag variant. The user selected ordinary white banners; green/officer and black/yellow community variants are not substituted.

New LAW shields use vanilla banner components directly. The square sun and compatibility masks are deterministically compiled from the installed Minecraft 1.21.11 native flower/border masks; no rendered Planet Minecraft image is bundled. Mojang retains rights to native textures. `LAW_BANNER_SOURCE.json` records the recipe and input hashes. Old LAW soldier shield components migrate without changing their name, damage or enchantments. No voice, music, combat or potion behavior changes.

## V1.5.4 main-menu background crossfade

The existing 15 bundled covers now crossfade during the last 800 milliseconds of each five-second interval, using a smoothstep opacity curve and native GUI alpha blending. The opaque outgoing image prevents a dip to black; explicit GUI strata preserve texture draw order. Both images use their own aspect-preserving crops, then the existing GPU blur runs once on the combined background. The last-to-first transition uses the same path. Cover assets, attribution, quotes, audio and gameplay are unchanged.

## V1.5.5 darker title-screen background

The existing black overlay increases from alpha 61/255 to 128/255 after background compositing and blur. Menu widgets, title and splash are drawn afterward at their original brightness. The five-second cycle, 800ms crossfade, existing assets, sounds and gameplay remain unchanged.

## V1.5.6 world/server selection and menu button labels

The same cover compositor now runs behind the out-of-world SelectWorldScreen and JoinMultiplayerScreen, with their opaque native list backgrounds suppressed. Rows, scrolling, search fields, controls and click actions remain vanilla. The title screen's two existing buttons are relabeled with the user's exact English video titles; the labels do not replace global translations or modify networking/gameplay. Other screens and in-world overlays retain their native backgrounds. Existing cover/audio assets are unchanged.


## V1.5.7 native mace control, first-person view and food supply fixes

Wemmbu II now swaps two actual marked loan items between a spare inventory slot and the chest slot, prepares chest armor earlier, and checks the armed fall on each server tick using native player attack and mace damage. Successful attacks send the native hand-swing animation to the attacking client as well as observers. The loan escrow additionally preserves the original spare-slot stack and offhand, including across save/reopen and death cleanup. A single stack of 64 temporary golden apples is supplied in the offhand; low health starts native eating with normal regeneration and absorption, rather than direct health writes or unlimited stack refills. Client handling preserves this use without latching a physical key.

Pilot rotation updates run after the normal client simulation to retain old/current rotation interpolation; turn-in is latched rather than oscillating across a height threshold. A first-person camera hook smooths rendered rotation between ticks and tracks the target during dive/smash without changing flight physics or attack reach. Unchanged state packets and repeated hotbar selection/inventory synchronization are suppressed. These are original local implementation changes; no new third-party textures, audio, music or code are introduced. Client and server must both update for the extended control-state payload.

A single stack of 64 marked firework rockets is also supplied in a separately escrowed hotbar slot. Boosts briefly select that slot and call the native FireworkRocketItem use method, producing the attached rocket, native launch/trail and item consumption; the pilot then reselects the mace. Exhausted or replaced supply cannot generate a boost, original player-owned fireworks stay untouched, and leftover temporary rockets are reclaimed along with the original slot contents. Food-state start/finish updates are sent immediately so the first use tick is not cancelled while waiting for the periodic state heartbeat.


## V1.5.8 four firework stacks and original identity restoration

Wemmbu II supplies four actual stacks of 64 native rockets: one active hotbar stack and three visible reserves in separately escrowed inventory slots. Native boosts move an existing reserve stack into an exhausted active slot, consume one rocket normally, and never refill spent stacks. Reserve-slot escrow, remaining stacks and the one-time issuance flag persist with the player; older active kits receive only the three new reserves. Cleanup reclaims marked leftovers and restores original slot contents without rolling back unrelated inventory changes.

Death now explicitly clears the synchronized form, native tab display and local control state before the session is discarded. Normal expiry additionally repairs a stale form with no session. Loaded player entities govern the tab skin override, so a matching text label cannot leave their tab portrait overridden after the form ends. Native skin/profile/name providers remain the source of the original appearance and identity; no permanent skin or authenticated name mutation occurs. No new assets or external implementation are introduced.


## V1.6.0 retained enemy locks, tracked coordinates and dual-mace combat

Current community wiki gear excerpts identify Gambit as Density V / Wind Burst II / Fire Aspect II / Unbreaking III / Mending, and Crucible as Breach IV / Fire Aspect II / Unbreaking III / Mending, without Wind Burst. Older discussions contain different historical levels; these are recorded rather than merged into an unsupported Wind Burst III claim. References and confidence are in WEMMBU_COMBAT_SOURCE.json. The fully upgraded seven-enchantment netherite sword is a user-requested gameplay loadout, not an assertion about every historical inventory. Native Minecraft enchantment components and attacks implement the effects.

The initial acquisition radius is 128 blocks; eligible modified character mobs and hostile faction soldiers precede ordinary enemies, with nearest distance within a tier. Existing locks are retained through temporary aggro loss and nonfatal hits, with a 192-block maneuver retention limit. Synchronized target position, velocity and height allow flight before an entity enters client tracking. Collision rays detect low roofs and narrow corridors for native walking, full chest armor and sword/Crucible switching; open space retains Gambit elytra attacks. Extra weapon slots are escrowed and persist with existing loan supplies. No external combat implementation or new texture/audio asset is bundled.


## V1.6.4 menu, flight and cannon improvements

Shared cover rendering extends to vanilla menu/settings backgrounds, with one blur/composite per GUI frame. Gameplay containers/chat keep their useful world view. Original cover files and voice clips are unchanged. The mist color, circular city enclosure, removed corner cupolas, native-size phantom cargo, cached swimming-surface search, bounded dive preparation, and marked slime-bucket/book/sign pearl interactions are original implementation changes.

The decorative border-rift cannon now uses **Cubicmetre — The Orbital Strike Cannon Mk.6.1**, from the [published schematic](https://www.mediafire.com/file/vzgb1yd0b4wu6h6/The_Orbital_Strike_Cannon_Mk.6.1.litematic/file). Its embedded author field is `cubicmetre`. All 31 subregions, including negative-size regions, are imported: 13,501 source non-air placements merge to 12,694 unique blocks in a 58×68×47 envelope. Circuits are inert visual aliases; source entities, inventories and commands are excluded. Source water is represented with light-blue glass and powder snow with snow blocks. Hash, author, changes and source URL are bundled in ORBITAL_BLUEPRINT_SOURCE.json. No upstream control application is included. No new license is inferred from a public download. Original MK.1 registry IDs remain available for existing worlds.

Bunker-buster salvos place 165 stationary TNT entities at the target X/Z, one at every absolute block height from Y=100 through Y=-64, including inside solid walls. All share one world-tick detonation time. Only real simultaneous explosions open the bore, protecting bedrock and other unbreakable blocks. A short-lived, reference-counted simulation ticket prevents a charge disappearing before its first tick. Flame minecart projectiles retain native TNT fuses and impact detonation, with a fixed straight flight vector. The pearl-launch booster is real primed TNT with a non-destructive explosion; travel remains server-authoritative after 200 ticks.

## V1.6.5 control and retirement fixes

Original changes add native crawling exit paths, correctly charged sword/Crucible switching, frame-smoothed rotational hand inertia, per-assist grade-I hotbar restoration and proactive selection of all modified character entity types. Dragon attacks target the native damageable head part. Retired NULL troops continue native death updates instead of restarting retirement every tick, including NoAI soldiers and loaded corpses. Existing texture, audio, menu artwork and decorative schematic assets are unchanged. Test instrumentation is excluded from the distributed mod.

## V1.6.6 pearl cannon chat coordinates

Accepted native player chat can build or retarget a pearl cannon through the nearest living 4CViT slime within an inclusive ten-block three-dimensional distance. The original coordinate parser, machinery, safe arrival and alternate input methods are retained. Normal chat is not canceled or rewritten. This is original implementation; no new external assets are introduced.

## V1.6.7 Golden City gateway

The white-and-gold triumphal gateway, layered arch reveals, fluted piers, crown pediment, purple runner and light fixtures are original procedural block architecture. All four axis cities face back toward normal terrain. The open gate connects directly to the existing perimeter gallery. Previously generated entrances receive a bounded one-time chunk upgrade, comparing exact previous generated states and skipping player changes and block entities. Other city rooms and world chunks are not regenerated. No new external art, audio or schematic is bundled.

Original potion-control fixes use native multipart dragon damage, accepted player movement for grade-I falling-window prediction, temporary-kit selection from arbitrary held slots, food-only retreat recovery through the sixteen-health threshold, and upward-facing native ground relaunches. Dragon body/wing/tail damage retains the game's native reduction. No extended hit reach, direct target-health edits, direct healing, or movement teleportation is added by the controller. Test-only instrumentation is excluded from the production JAR.

## V1.6.8 contextual voices and cannon recovery

The v1.6.8 release introduced nine community-uploaded voice excerpts as complete mono Vorbis encodings: Wemmbu's Unstable SMP introduction, “Hey, buddy”, orbital-cannon introduction and Flame shout; Boosfer's stuttering “PEASANT”; Eggchan's molten-lava and “taste blood” lines; FlameFrags' “not most players” line; and a short generic “Well, well, well” reaction. Source pages, exact source and packaged hashes, durations, trigger mapping and encoding details are included in `VOICE_SOURCES_1.6.8.json` inside the release. These uploads are not represented as independently verified original-video sources or as permission grants. Creator voices and performances remain their respective owners' material. Existing meme clips and all previously removed standalone battle music remain unchanged.

The ten-second phantom cannon recovery, grouped explosion-voice dispatch, visible-world intro gate, lava-entry detection, player throw hooks, trader interval and persistent per-character first-meeting state are original code. Test-only probes, fixtures and audio recordings are excluded from the distributed mod.

## V1.7.0 character combat potions and role library

Character skins are the project's previously approved references. The five new
role images were rendered with Minecraft's own player model and armor; the
geometric backgrounds, interface, ability controllers and guard logic are
original code. The right-side preview is a live rotating player render, and the
background uses the matching transition image with native blur and a dark mask.
Flame weapon names/enchantments were checked against the community wiki; armor
materials/trims match the existing approved echo actors. Specific Jaden weapon
enchantments and support-role kits are gameplay choices. See HERO_REFERENCES.json.

Combat uses native player input, projectiles, Riptide, melee/mace damage, real
TNT minecarts and consumed food/totems. Borrowed equipment is held in persistent
escrow and restored; stock is finite. The enchanted reserve restores half health
after the ten ordinary native totems are exhausted. The caster is protected from
its own tagged loan-cart explosion; no extended melee reach or direct enemy
health edits are used. New gear-hunting Flame goals deliberately consume dropped
elytra/maces, including the normally fireproof mace. No new audio is included.

## V1.7.1 independent cannon designs

This section supersedes historical imported cannon geometry descriptions above.
Both current layouts are authored by tools/generate_original_cannons.py, using
only independent geometric primitives and native blockstate/model identifiers.
No schematic, upstream palette or imported layout is read. The pearl cannon
uses staggered timing towers and an open dry launch well; the orbital station
uses octagonal trusses and eight radial loading heads. Existing real pearl,
TNT boost, 200-tick travel and combat behavior are retained.

Public UU mechanism pages and the indexed Orbital Strike image informed only
general visual vocabulary. A clear verified UU pearl-cannon close-up was not
obtained, so this is an independent interpretation, not an episode-exact copy.
The current cannon JSON files contain no imported layout. Legacy inert block
IDs remain for save compatibility. Existing placed machines and generated
chunks are not destructively replaced. See ORIGINAL_CANNON_DESIGNS.json.

### Separate cover proposals — not bundled

Fifteen proposed covers combine AI-generated empty backgrounds with actual
Minecraft rendering of the retained skins and native equipment. These replace
an inaccurate all-AI draft in the separate review archive only. The user asked
not to apply these images to the mod. Consequently, the fifteen existing menu
PNGs, slide metadata and MENU_REFERENCES.json are retained byte for byte from
1.7.0, including the original third-party thumbnail attributions above. All
fourteen voice files and eighteen splash lines remain unchanged. The cover
proposals are fan posters, not gameplay photographs. No blanket permission for
character designs, skins, recordings or Minecraft assets is inferred.


## v1.7.2 voice and legacy-dimension changes

The unverified community-uploaded “taste blood” recording is no longer included or played. `VOICE_AUDIT_1.7.2.json` records the removed event and asset; thirteen existing OGG files remain unchanged. Player totem use retains its native activation sound and appends the existing Flame “most players” excerpt after the original 3.42-second sound. The old Underworld generator, protection and portal routes have been removed; the dimension-type identifier and inert portal block remain only for old-save compatibility. The corrected Spoke role image is a new native Minecraft rendering of the retained approved skin with its outer layer enabled, not one of the separately supplied candidate cover images.


## v1.7.3 Eggchan throw quote

The selected community clip tagged Eggchan is the full 2.16-second “Dude, I'm a lover, not a fighter, bro.” recording, not the removed unverified taste-blood clip. See VOICE_SOURCES_1.7.3.json for the source URL, original and packaged hashes, processing, attribution limits and trigger. The thirteen existing OGG files and all menu cover files remain unchanged.


## V2.0.6 Farlands orbital array and fishing-rod binding

This section supersedes the v1.7.1 description for the **current orbital**
layout only. The pearl cannon is unchanged and remains independently authored.
The former octagonal orbital layout is retained only to identify untouched
blocks when incrementally upgrading loaded saved chunks; player-modified
blocks and block entities with their inventories are preserved.

The new orbital body comes from [Farlands orbital strikes Unstable SMP](https://www.abfielder.com/Products/ProductDetails.php?id=11347),
uploaded by **AquaYAY**. The Litematic's embedded Author field is **ArcticF35**.
In [I Explored Beyond the Minecraft Void](https://www.youtube.com/watch?v=QhxnImk2GFQ),
**Wemmbu credits cubicmetre** as the orbital cannon designer. This verifies the
episode's design credit, not that this community upload is an official world
export or a specific Mk.4/Mk.6.1 revision.

Pinned source: `45ae242febbc_Orbitals.litematic`, SHA-256
`a88d40873e5edd03f82000ee93e9d9d605c55542525289aa60c45c03b4981d39`.
The source contains 205,438 non-air blocks across a long repeated array. We
select one source-scale 7,629-block body (source x30..99, y55..102, z70..169),
rotate it for the four border axes and repeat it every 100 blocks. Outlying
parallel rails and a distant walkway are omitted to fit the existing 70-block
rift; the remaining machine is not rescaled. Source entities, block-entity
NBT, inventories, signs and commands are excluded. Circuitry and TNT are inert
native-model aliases; water becomes light-blue glass, powder snow becomes a
snow block, and the closed ender chest uses a static native-texture shell.
Existing server-side combat and artillery effects are retained.

No explicit redistribution license is stated on the source listing. No
permission or new license over upstream geometry is asserted; it is excluded
from this project's MIT code license. Exact transformations and source URLs
are bundled in `ORBITAL_BLUEPRINT_SOURCE.json`.

Fishing-rod binding and saved-chunk upgrades are original project code. A real
ordinary fishing bobber touching one of the four original gold pressure plates
consumes that cast and replaces the rod in its hand with exactly one single-use
Wemmbu orbital cannon or bunker buster, with equal probability. Copied plates
elsewhere do not bind rods. No source redstone circuitry is executed, and no
new voice recording, music, character skin or menu thumbnail is added.


## V2.0.7 configurable eight-ring artillery and hidden minecart bunker busters

The world-persistent `/uu orbital rings` command, native eight-ring volley,
hidden TNT-minecart column, damage calculator and shield-specific protection
are original implementation. The default volley uses radii 4 through 32 in
four-block steps, with 8 times the ring index in TNT per circle (288 total).
The operator may select 1–16 rings; all standard player and character-mob
orbital shots share the saved setting across dimensions. Existing volleys
are unchanged by later settings.

The `uu_cursed:drill_charge` identifier and custom owner/deadline fields are
retained for saves, but its implementation is now a TNT-minecart subclass.
A no-model renderer and noninteractive, invisible, stationary nodes avoid
cart/TNT visuals and fuse smoke. The same 165 native explosion calls cover
Y=-64..100 in one tick. Native entity damage is multiplied by 1.5 without
increasing block-destruction radius. Holding a shield in either player hand
skips only this payload's direct damage; native knockback remains. Ordinary
TNT, other minecarts and their recordings are unchanged. Native damage owner,
cannon voice grouping and drill/orbital advancement attribution are retained;
drill kills do not count as Flame/Sarge combat-cart kills.

No new third-party image, schematic, skin, voice or music asset is introduced.
The v2.0.6 cannon-geometry attribution and licensing exceptions remain in force.


## V2.0.8 full-height drills, twelve-ring artillery and chained Riptide

The complete dimension-height minecart column, separate saved orbital/wither
ring settings, legacy-default migration and Jaden II chained-trident aiming
are original project code. Orbital and wither volleys default to twelve rings
(624 TNT and 540 skulls respectively). Existing wither timing is retained.
The Overworld drill has 384 simultaneous nodes at Y=-64 through Y=319.
Jaden II uses real vanilla wet-condition Riptide charge/release and survival
physics to gain altitude and reposition before committing to a mace dive.
No new third-party blueprint, image, character skin, voice or music asset is
introduced; existing geometry attribution and licensing exceptions remain.


## V2.0.9 combined cannon music triggers

Successful player orbital and bunker-buster rod uses now share the existing
server-owned per-activation battle-music counter. The fifth combined use
switches from the user's local Wemmbu track to their local war track. Native
launch validation, consumption, finite ability supplies and combat
fade/pause/cleanup rules are retained. The old generated README's two counting
instructions are updated without replacing user additions. This is original
project code; no song, voice recording, texture or third-party geometry is
added or changed. Native playback tests use generated sine tones only, which
are not included in the release.

The same update adds an original server flight ceiling for phantoms, drowned
and withers, bounded combat staging/cruise points, twenty-tick Jaden Riptide
cycles and native ten-tick player trident charges. Drill explosions now use
vanilla TNT block/fluid resistance rather than reduced resistance. Explicit
fluid protection retains source/flowing liquids and waterlogged contents.
Full-height payloads, native explosion strength, the damage multiplier and
shield/knockback rules are retained. No external assets are introduced.

Depleted phantom artillery now takes an explicit mace-only branch and clears
the rod. Riptide's short spin pose is excluded from the low-tunnel crawling
check; server-owned timing prevents redundant real charges and keeps the
intended twenty-tick cycle while client steering continues.
