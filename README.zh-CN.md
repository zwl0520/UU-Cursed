# UU Cursed — Unstable SMP 人物与梗模组

Minecraft Java **1.21.11 / Fabric**。把 Unstable SMP / Unstable Universe 的人物、生物、梗语音、战斗方式、军队和边境探索带进 Minecraft。

作者：**B站「筑梦-星空」／YouTube「DreaminStars」**。

[English](README.md) · [2.0.0 发布页](https://github.com/zwl0520/UU-Cursed/releases/tag/v2.0.0) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/unstable-smp-cursed) · [反馈问题](https://github.com/zwl0520/UU-Cursed/issues)

## 下载

| 版本 | 国外／GitHub 官方直链 | 国内代理加速 |
| --- | --- | --- |
| **2.0.0 最新版** | [下载 JAR](https://github.com/zwl0520/UU-Cursed/releases/download/v2.0.0/UU_Cursed_v2.0.0_Fabric_1.21.11.jar) | [加速下载 JAR](https://ghfast.top/https://github.com/zwl0520/UU-Cursed/releases/download/v2.0.0/UU_Cursed_v2.0.0_Fabric_1.21.11.jar) |
| **1.0.1 旧版（此前的 1.0 系列正式版）** | [下载 JAR](https://github.com/zwl0520/UU-Cursed/releases/download/v1.0.1/UU_Cursed_v1.0.1_Fabric_1.21.11.jar) | [加速下载 JAR](https://ghfast.top/https://github.com/zwl0520/UU-Cursed/releases/download/v1.0.1/UU_Cursed_v1.0.1_Fabric_1.21.11.jar) |

代理转发的是 GitHub 官方附件，由第三方运营，不同网络的连通情况会有差异；可用发布页的 SHA-256 文件核对下载结果。

本次公开发布统一编号为 **2.0.0**，包含此前开发构建 **2.0.9** 的全部玩法和修复。安装包内部版本号为 `2.0.0+mc1.21.11`。

## 有什么玩法？

### 和 UU 人物生物战斗

- **Wemmbu 幻翼**：烟花尾迹俯冲、重锤、轨道炮与钻地弹、图腾，以及身后挂成一串的 Eggchan 鸡蛋和雪球。两种炮的弹药都耗尽后固定使用重锤。
- **Jaden 溺尸**：激流三叉戟配合重锤，雨中空战和水下战斗。
- **Spoke 凋灵**：附魔图腾、从传送门出场的 NULL 士兵，以及同心圆凋零炮。
- **Flame 烈焰人／恶魂**：烈焰棒聚合火剑、召唤穿狼铠的狼、图腾与 TNT 矿车攻击。
- 还有人物鹦鹉、美西螈、猫、狼、坚守者、Spoke 鳕鱼，以及 4CViT／Wifies／PlanetLord 史莱姆等。

生物之间也会战斗。通过游玩发现角色关系、特殊互动、语音触发条件和 **38 项紫色挑战成就**。

### 喝药水使用角色能力

| 角色 | 能力方向 |
| --- | --- |
| Wemmbu | 鞘翅锤、轨道炮和钻地炮 |
| Flame | 剑斧、火弓与 TNT 矿车连招 |
| Jaden | 连续激流位移与下落重锤 |
| Spoke | NULL 军队护卫 |
| Lettuce | LAW 军队护卫 |
| Ashswagg | Mafia 军队护卫 |

Wemmbu／Flame／Jaden 的 **I 为辅助，II 为自动操控，III 为永久解锁**。III 喝下后在 **H** 菜单选择能力，不会直接启用变身。军队角色有五分钟瓶和永久解锁瓶。

能力生效时会借用临时装备并提供有限补给；结束后恢复原有物品、名字和皮肤。永久解锁后，对应角色生物也会成为潜在援军。

[查看药水配方与能力说明（英文）](docs/ABILITIES.md)

### 探索边境之地与黄金城

主世界 `max(abs(X), abs(Z)) >= 10,000,000` 开始进入边境之地。依次探索高墙与孔洞、重复地形和地牢、砂砾地带、雪地尖峰、樱花林、悬浮岛、群系拼块、虚空海洋、单草方块分形和纯虚空。

沿正负 X／Z 四条坐标轴路线，可以寻找**虚空黄金城**：圆形资源库、会议室、宿舍、带看台的竞技场、末地传送门房间，以及进入后切换 Beta 时代材质的封闭小世界。沿途还有循环播放的剧情回声。

进入边境后按 **M** 打开随朝向旋转的地图，查看区域、路线和结构位置。深入 500 格后，烟花不再推进鞘翅，风弹与末影珍珠仍可使用。

### 把 4CViT 工程师装进口袋

向村庄制图匠购买迷雾地图和边境地图。把地图交给 **4CViT 史莱姆**，或提供目的地坐标，让它建造珍珠炮；在标记处向上投掷末影珍珠，约十秒后传送到目的地附近的安全地面。

可以用桶带走 4CViT，需要时再释放。更多角色互动、人物物品和梗语音可在普通生存世界中发现。

## 安装要求

1. Minecraft Java **1.21.11**、**Java 21 或更新版本**、**Fabric Loader 0.19.5 或更新版本**。
2. 安装适用于 1.21.11 的 **Fabric API 0.141.6+1.21.11 或更新构建**。
3. 把本模组 JAR 和 Fabric API 放进游戏实例的 `mods` 文件夹；更新时移除旧版 UU Cursed JAR。
4. 联机时客户端和服务器都安装并更新。

纹理、模型和声音已包含在模组中，无需单独安装材质包、ETF、EMF 或 Unstable Generation。边境地形作用于标准主世界尚未生成的区块。

## 常用操作

| 按键 | 功能 |
| --- | --- |
| **H** | 角色能力选择、开启或关闭 |
| **Shift** | 暂停自动操控，保留当前效果 |
| **G** | 恢复自动操控／在支持的模式下选择瞄准目标 |
| **M** | 在边境之地内打开地图 |
| **喝牛奶** | 清除当前药水效果 |

可在原版按键设置中改键。想快速体验，可在创造模式搜索角色药水；轨道炮和钻地炮鱼竿也位于「战斗」栏。

## 可选本地战斗音乐

将自备 `wemmbu.mp3`、`flame.mp3`、`war.mp3` 或对应 Ogg Vorbis 文件放到 `config/uu_cursed/music/`。一次 Wemmbu 能力启用期间，两种炮累计成功使用满五发切换到 war。**模组不附带战斗歌曲。**

[音乐设置说明](docs/LOCAL_BATTLE_MUSIC.md) · [完整成就条件](docs/CHALLENGES.md) · [版本更新说明](CHANGELOG.md)

这是非官方粉丝作品，不代表角色创作者授权背书。原创代码与第三方素材适用不同条款，见 [LICENSE](LICENSE)、[CREDITS.md](CREDITS.md) 及包内来源说明。发布游玩视频等内容时，请标注 **B站「筑梦-星空」／YouTube「DreaminStars」**。
