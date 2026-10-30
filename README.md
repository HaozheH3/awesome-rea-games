# 🎮 Awesome REA/Decompiled Games

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/reacher-z/Awesome-REA"><img src="https://raw.githubusercontent.com/reacher-z/Awesome-REA/main/assets/featured-by-awesome-rea-inline.svg" alt="Featured by Awesome REA" width="184" height="20"></a>
  <a href="#inventory"><img src="https://img.shields.io/badge/games-103-2f81f7.svg" alt="103 games"></a>
  <a href="#inventory"><img src="https://img.shields.io/badge/projects-140-1f9d8a.svg" alt="140 projects"></a>
  <a href="#inventory"><img src="https://img.shields.io/badge/categories-8-ed9a45.svg" alt="8 categories"></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg" alt="Contributions welcome"></a>
</p>

**Motivation**: Game decompilations and rebuilds are scattered across repositories, demo sites, and social posts. Finding the projects for a particular game and understanding what each one does can take a lot of digging. Awesome REA-Decompiled Games brings that work together by game, starting with projects made with [REA](https://github.com/morluto/rea) (reverse-engineer-anything) and extending to other decompilations, source reconstructions, recompilations, ports, and playable demos.

Each game has one representative image, a short introduction to the original release, and a table comparing related projects. Players can find playable builds, developers can explore source code and techniques, and game preservationists can follow work on games they care about. The goal is to make these projects easier to find, understand, and carry forward.

**Contributing**: If you are building a project like this, or know one worth sharing, [contribute to the collection](CONTRIBUTING.md) and help others discover it.

<a id="inventory"></a>
## 🗂️ Inventory

| Browse | Games | What you will find |
|:--|--:|:--|
| [🧭 Platformers & action adventures](#platformers--action-adventures) | 32 | Platforming, exploration, and story-led action. |
| [🧙 RPGs & roguelikes](#rpgs--roguelikes) | 20 | Role-playing games, action RPGs, and roguelikes. |
| [⚔️ Action, shooters & fighting](#action-shooters--fighting) | 14 | Open-world action, shooters, and fighting games. |
| [👻 Horror & suspense](#horror--suspense) | 5 | Survival horror and suspense. |
| [🏁 Racing & sports](#racing--sports) | 13 | Racing, driving, skating, football, and other sports. |
| [🏗️ Strategy & simulation](#strategy--simulation) | 7 | Management, simulation, and tactical strategy. |
| [🕹️ Arcade & casual](#arcade--casual) | 10 | Arcade games, browser runners, and smaller reconstruction efforts. |
| [🎪 Playable showcases](#playable-showcases) | 2 | Creator-shared browser games and demos. |

[✨ Quick tour](#a-quick-tour) · [🤝 Contributing](#contributing)

> **How to read this list:** One representative image sits under each game heading. Some headings cover closely related editions. The table underneath compares source projects, ports, launchers, and demos. 📸 marks titles from a collection screenshot; 🔬 marks REA-assisted work; ◈ marks related engine or compatibility work; ▶ marks a playable showcase. Release years refer to the edition described and may vary by region.

<a id="a-quick-tour"></a>
## ✨ A quick tour

- [Super Mario 64](#super-mario-64) shows how one game can have reconstructed source, native ports, and a multiplayer descendant.
- [Metroid Prime](#metroid-prime) separates an engine reimplementation from a disc-based native port.
- [Touhou 8: Imperishable Night](#touhou-8-imperishable-night) pairs a documented REA-assisted reconstruction with a browser build.

<a id="platformers--action-adventures"></a>
## 🧭 Platformers & action adventures

Platforming, exploration, and story-led action games.

<a id="super-mario-64"></a>
### 🍄 Super Mario 64

<a href="https://thegamingemporium.com/Images/Games/super-mario-64-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/super-mario-64-pc-port.webp" alt="Super Mario 64 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Nintendo launched this 3D platformer with the Nintendo 64 in Japan in 1996. Its “64” names the console; analog movement, an explorable castle, and open stages made it a reference point for later 3D games. [Nintendo history](https://www.nintendo.com/jp/character/mario/en/history/index.html)

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **sm64pc/sm64ex** | [sm64ex](https://github.com/sm64pc/sm64ex) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | An expanded native PC port built on the reconstructed Super Mario 64 codebase. It is a playable port project rather than the original decompilation repository. |
| **n64decomp/sm64** | [sm64 source reconstruction](https://github.com/n64decomp/sm64) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A source reconstruction of the Nintendo 64 release. This is the decompilation lineage that several PC ports build upon. |
| **HarbourMasters/Ghostship** | [HarbourMasters/Ghostship](https://github.com/HarbourMasters/Ghostship) | A separate native PC port from the reconstructed Nintendo 64 code; the project requires a user-supplied ROM. |
| **coop-deluxe/sm64coopdx** | [coop-deluxe/sm64coopdx](https://github.com/coop-deluxe/sm64coopdx) | A multiplayer source port built on the Super Mario 64 reconstruction, rather than a new decompilation. |

---

### 🍄 Super Mario Sunshine

<a href="https://thegamingemporium.com/Images/Games/super-mario-sunshine-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/super-mario-sunshine-pc-port.webp" alt="Super Mario Sunshine game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Released for GameCube in 2002, this tropical Mario adventure centers on Isle Delfino and the FLUDD water device. Its GameCube codebase has both reconstruction work and later PC-facing projects.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **doldecomp/sms** | [doldecomp/sms](https://github.com/doldecomp/sms) | The upstream Super Mario Sunshine decompilation project; it focuses on reconstructing the GameCube game source. |
| **chasem-dev/sms-english** | [chasem-dev/sms-english](https://github.com/chasem-dev/sms-english) | A North American Super Mario Sunshine decompilation fork. It belongs to the same project chain as the port and launcher below. |
| **chasem-dev/sms-pc-port** | [chasem-dev/sms-pc-port](https://github.com/chasem-dev/sms-pc-port) | A native PC port derived from the Sunshine reconstruction work. |
| **chasem-dev/sms-launcher** | [chasem-dev/sms-launcher](https://github.com/chasem-dev/sms-launcher) | A setup and play launcher for the Sunshine PC port. It is a companion application, not a separate decompilation. |

---

### 🍄 Super Mario Galaxy

<a href="https://thegamingemporium.com/Images/Games/super-mario-galaxy-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/super-mario-galaxy-recompilation.webp" alt="Super Mario Galaxy game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Nintendo's 2007 Wii platformer moves Mario between small planets with gravity-driven movement. The project here studies the original Wii game's code rather than offering an official PC edition.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **SMGCommunity/Petari** | [SMGCommunity/Petari](https://github.com/SMGCommunity/Petari) | A source reconstruction project for the 2007 Wii game. |

---

### 🍄 Super Mario 64 DS

<a href="https://thegamingemporium.com/Images/Games/super-mario-64-ds-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/super-mario-64-ds-pc-port.webp" alt="Super Mario 64 DS game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2004 Nintendo DS reworking of Super Mario 64 adds playable characters and handheld-specific features. Its source project targets the DS version, which differs from the 1996 Nintendo 64 game above.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **tangosdev/sm64ds-decomp** | [tangosdev/sm64ds-decomp](https://github.com/tangosdev/sm64ds-decomp) | A source reconstruction effort for the Nintendo DS version of Super Mario 64. |

---

### 🗡️ The Legend of Zelda: Breath of the Wild

<a href="https://en.wikipedia.org/wiki/File:The_Legend_of_Zelda_Breath_of_the_Wild.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/c/c6/The_Legend_of_Zelda_Breath_of_the_Wild.jpg" alt="The Legend of Zelda: Breath of the Wild game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:The_Legend_of_Zelda_Breath_of_the_Wild.jpg)</sub>

Nintendo released this open-world Zelda adventure for Wii U and Switch in 2017. The listed work concerns the Switch game's source reconstruction; its existence does not imply a finished native port.

<sub>Project target: Switch release.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zeldaret/botw** | [zeldaret/botw](https://github.com/zeldaret/botw) | A source reconstruction of the Switch 1.5.0 release. |

---

### 🗡️ The Legend of Zelda: Skyward Sword

<a href="https://en.wikipedia.org/wiki/File:Legend_of_Zelda_Skyward_Sword_boxart.png"><img src="https://upload.wikimedia.org/wikipedia/en/9/99/Legend_of_Zelda_Skyward_Sword_boxart.png" alt="The Legend of Zelda: Skyward Sword game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Legend_of_Zelda_Skyward_Sword_boxart.png)</sub>

Originally a 2011 Wii adventure built around motion-controlled swordplay, Skyward Sword precedes the later HD edition. The listed repository investigates the Wii release's code.

<sub>Original platform: Wii.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zeldaret/ss** | [zeldaret/ss](https://github.com/zeldaret/ss) | A decompilation project for the original Wii game. |

---

### 🗡️ The Legend of Zelda: Ocarina of Time

<a href="https://thegamingemporium.com/Images/Games/ship-of-harkinian-zelda-ocarina-of-time-port.webp"><img src="https://thegamingemporium.com/Images/Games/ship-of-harkinian-zelda-ocarina-of-time-port.webp" alt="The Legend of Zelda: Ocarina of Time game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Released on Nintendo 64 in 1998, this was Zelda's move into 3D exploration. Its reconstructed source and later native PC port are different stages of the same broader project lineage. [Nintendo developer interview](https://iwataasks.nintendo.com/interviews/3ds/zelda-ocarina-of-time/4/0/)

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **HarbourMasters/Shipwright** | [Shipwright / Ship of Harkinian](https://github.com/HarbourMasters/Shipwright) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | Ship of Harkinian is a native port of Ocarina of Time built from reconstructed game code, with a focus on running the game on modern systems. |
| **zeldaret/oot** | [oot source reconstruction](https://github.com/zeldaret/oot) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A source reconstruction of the Nintendo 64 Ocarina of Time release; a different artifact from the Ship of Harkinian port. |

---

### 🗡️ The Legend of Zelda: Twilight Princess

<a href="https://thegamingemporium.com/Images/Games/dusklight-the-legend-of-zelda-twilight-princess-recompilation-for-android.webp"><img src="https://thegamingemporium.com/Images/Games/dusklight-the-legend-of-zelda-twilight-princess-recompilation-for-android.webp" alt="The Legend of Zelda: Twilight Princess game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

First released for GameCube and Wii in 2006, this Zelda entry has both source reconstruction and separate port or recompilation efforts. The rows distinguish the original code work from later runtime targets.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **TwilitRealm/dusklight** | [TwilitRealm/dusklight](https://github.com/TwilitRealm/dusklight) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A Twilight Princess recompilation effort aimed at Android. The destination platform differs from the GameCube and Wii source releases. |
| **zeldaret/tp** | [zeldaret/tp](https://github.com/zeldaret/tp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A Twilight Princess source reconstruction project. It is listed separately from the Android-focused project above. |

---

### 🗡️ The Legend of Zelda: The Wind Waker (including HD)

<a href="https://thegamingemporium.com/Images/Games/the-legend-of-zelda-the-wind-waker-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/the-legend-of-zelda-the-wind-waker-decompilation.webp" alt="The Legend of Zelda: The Wind Waker game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The Wind Waker began as a GameCube seafaring adventure in 2002, with an HD edition later released for Wii U. The projects below target different versions, so version scope matters when comparing them.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zeldaret/tww** | [zeldaret/tww](https://github.com/zeldaret/tww) | A source reconstruction of the GameCube version of The Wind Waker. |
| **ZeldaWWHDRecomp/ZeldaWWHDRecomp** | [ZeldaWWHDRecomp/ZeldaWWHDRecomp](https://github.com/ZeldaWWHDRecomp/ZeldaWWHDRecomp) | A recompilation project for The Wind Waker HD. It targets a different original edition from the GameCube source reconstruction. |

---

### 🗡️ The Legend of Zelda: Majora’s Mask

<a href="https://thegamingemporium.com/Images/Games/zelda-64-recompiled-majoras-mask-with-mod-support.webp"><img src="https://thegamingemporium.com/Images/Games/zelda-64-recompiled-majoras-mask-with-mod-support.webp" alt="The Legend of Zelda: Majora’s Mask game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2000 Nintendo 64 sequel is built around a repeating three-day cycle. Its entries span original-game source reconstruction, static recompilation, and a separate PC port.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Zelda64Recomp/Zelda64Recomp** | [Zelda64Recomp](https://github.com/Zelda64Recomp/Zelda64Recomp) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Nintendo 64 static recompilation project for Majora’s Mask, intended to run the game natively on modern systems. |
| **zeldaret/mm** | [mm source reconstruction](https://github.com/zeldaret/mm) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A source reconstruction of the Nintendo 64 Majora’s Mask release. |
| **2ship2harkinian/2ship2harkinian** | [2ship2harkinian/2ship2harkinian](https://github.com/2ship2harkinian/2ship2harkinian) | A native PC port of Majora’s Mask. It belongs beside the existing static recompilation and source reconstruction. |

---

### 🗡️ The Legend of Zelda: The Minish Cap

<a href="https://en.wikipedia.org/wiki/File:TLOZ-_Minish_Cap_NA_Box_art.png"><img src="https://upload.wikimedia.org/wikipedia/en/0/0a/TLOZ-_Minish_Cap_NA_Box_art.png" alt="The Legend of Zelda: The Minish Cap game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:TLOZ-_Minish_Cap_NA_Box_art.png)</sub>

A 2004 Game Boy Advance Zelda adventure whose shrinking mechanic changes how Link explores Hyrule. The listed project reconstructs the handheld game's original code.

<sub>Original platform: Game Boy Advance.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zeldaret/tmc** | [zeldaret/tmc](https://github.com/zeldaret/tmc) | A matching source reconstruction of the Game Boy Advance release. |

---

### 🗡️ Zelda II: The Adventure of Link

<a href="https://en.wikipedia.org/wiki/File:Zelda_II_The_Adventure_of_Link_box.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/f/fd/Zelda_II_The_Adventure_of_Link_box.jpg" alt="Zelda II: The Adventure of Link game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Zelda_II_The_Adventure_of_Link_box.jpg)</sub>

The second Zelda game appeared on the Famicom Disk System in 1987 and later on NES. Its side-view combat and experience system differ from the first game; the listed browser-capable project is a clean-room reimplementation.

<sub>Original release: Famicom Disk System; later NES edition. ◈ Adjacent reconstruction.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **troyedwardsjr/z2rs** | [troyedwardsjr/z2rs](https://github.com/troyedwardsjr/z2rs) · [Play in browser](https://z2rs.com/) | A Rust recreation with a public browser build. |

---

### 🗡️ The Legend of Zelda: Link's Awakening

<a href="https://thegamingemporium.com/Images/Games/the-legend-of-zelda-links-awakening-switch-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/the-legend-of-zelda-links-awakening-switch-recompilation.webp" alt="The Legend of Zelda: Link's Awakening game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Link's Awakening began on Game Boy in 1993 and received a Switch remake in 2019. The project below concerns the remake, so it should not be read as a decompilation of the original Game Boy release.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **peiikai/LASRecomp** | [peiikai/LASRecomp](https://github.com/peiikai/LASRecomp) | A recompilation effort for the Nintendo Switch version of Link’s Awakening. |

---

<a id="metroid-prime"></a>
### 🚀 Metroid Prime

<a href="https://thegamingemporium.com/Images/Games/metroid-prime-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/metroid-prime-recompilation.webp" alt="Metroid Prime game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2002 GameCube adventure translated Metroid exploration into a first-person view. The listed projects cover an engine reimplementation and a native port.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **AxioDL/metaforce** | [metaforce](https://github.com/AxioDL/metaforce) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A native reimplementation of the Metroid Prime engine. It is an adjacent engine project, not a claim that the original game source was fully decompiled. |
| **Odrannnn/MetroidPrimePort** | [GitHub](https://github.com/Odrannnn/MetroidPrimePort) · [Releases](https://github.com/Odrannnn/MetroidPrimePort/releases/latest) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A native Linux, Windows, and Android port built from PrimeDecomp. Its README describes widescreen, modern controls, and a randomizer; users supply their own GameCube disc image. |

---

### 🦔 Sonic Mania

<a href="https://thegamingemporium.com/Images/Games/sonic-mania-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/sonic-mania-decompilation.webp" alt="Sonic Mania game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Released in 2017, Sonic Mania revisits the series' side-scrolling design with Retro Engine technology. The game-specific decompilation and the broader engine reconstruction are related but different projects.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **RSDKModding/Sonic-Mania-Decompilation** | [RSDKModding/Sonic-Mania-Decompilation](https://github.com/RSDKModding/Sonic-Mania-Decompilation) | A decompilation of Sonic Mania’s Retro Engine game code, useful to readers interested in native builds and modding. |
| **RSDKModding/RSDKv5-Decompilation** | [RSDKModding/RSDKv5-Decompilation](https://github.com/RSDKModding/RSDKv5-Decompilation) | A decompilation of Retro Engine v5, the engine used by Sonic Mania; its scope is the engine rather than one game alone. |

---

### 🦔 Sonic Unleashed

<a href="https://thegamingemporium.com/Images/Games/sonic-unleashed-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/sonic-unleashed-recompilation.webp" alt="Sonic Unleashed game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Sonic Unleashed debuted in 2008 with high-speed daytime stages and Werehog sections. The entry here recompiles a console release for a different runtime.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **hedge-dev/UnleashedRecomp** | [hedge-dev/UnleashedRecomp](https://github.com/hedge-dev/UnleashedRecomp) | A recompilation project for Sonic Unleashed. Its approach is separate from a conventional source reconstruction. |

---

### 🦍 Donkey Kong 64

<a href="https://thegamingemporium.com/Images/Games/donkey-kong-64-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/donkey-kong-64-recompilation.webp" alt="Donkey Kong 64 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Nintendo's 1999 Nintendo 64 platformer spreads collectibles and character-specific challenges across large levels. The listed project is a recompilation effort for that original game.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Rainchus/Donkey-Kong-64-Recompiled** | [Donkey-Kong-64-Recompiled](https://github.com/Rainchus/Donkey-Kong-64-Recompiled) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A Donkey Kong 64 recompilation project. |

---

### 🌀 Crash Bandicoot

<a href="https://thegamingemporium.com/Images/Games/crash-bandicoot-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/crash-bandicoot-decompilation.webp" alt="Crash Bandicoot game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1996 PlayStation platformer introduced Crash through corridor-like 3D stages. The listed repository studies the first game, rather than a later remake or sequel.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **wurlyfox/c1** | [wurlyfox/c1](https://github.com/wurlyfox/c1) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A source reconstruction project for the first Crash Bandicoot game. |

---

### 🌀 Crash Bandicoot 2: Cortex Strikes Back

<a href="https://thegamingemporium.com/Images/Games/crash-bandicoot-2-cortex-strikes-back-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/crash-bandicoot-2-cortex-strikes-back-recompilation.webp" alt="Crash Bandicoot 2: Cortex Strikes Back game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1997 PlayStation sequel expands the original Crash formula with new levels and moves. Two separate code projects are grouped below so their claims can be compared.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Zumbo06/Crash2Recomp** | [GitHub](https://github.com/Zumbo06/Crash2Recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A native recompilation with a launcher for a user-owned PlayStation disc. The author describes it as completable but still a preview, with minor sound and graphics issues and an experimental 60 FPS mode. |
| **ughman/c2c** | [GitHub](https://github.com/ughman/c2c) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | An older C conversion and manual decompilation effort using PlayStation emulation for I/O. Its README says the build is not intended for regular players. |

---

### 🧭 Conker's Bad Fur Day

<a href="https://github.com/sciaschi/CBFD-Recompiled"><img src="https://github.com/user-attachments/assets/abb979d7-24a5-44f8-98d3-088ba2054a74" alt="Conker's Bad Fur Day recompilation project banner" width="400"></a><br><sub>[Project banner](https://github.com/sciaschi/CBFD-Recompiled)</sub>

Rare's 2001 Nintendo 64 game mixes platforming with adult comedy and frequent genre shifts. The listed project recompiles that N64 release.

<sub>Original platform: Nintendo 64.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **sciaschi/CBFD-Recompiled** | [sciaschi/CBFD-Recompiled](https://github.com/sciaschi/CBFD-Recompiled) | A Nintendo 64 static recompilation with published builds; users provide their own ROM. |

---

### 🐻 Banjo-Kazooie

<a href="https://thegamingemporium.com/Images/Games/banjo-kazooie-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/banjo-kazooie-recompilation.webp" alt="Banjo-Kazooie game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 1998 Nintendo 64 adventure follows Banjo and Kazooie through collectible-focused worlds. Recompilation and native-port projects below share the game but have different technical aims.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **BanjoRecomp/BanjoRecomp** | [GitHub](https://github.com/BanjoRecomp/BanjoRecomp) · [Releases](https://github.com/BanjoRecomp/BanjoRecomp/releases) | An N64: Recompiled native port for Windows, Linux, and macOS. Its README highlights high frame rates, widescreen, dual-analog camera control, and mods; an original game copy is required. |
| **HarbourMasters/Lighthouse** | [GitHub](https://github.com/HarbourMasters/Lighthouse) · [Releases](https://github.com/HarbourMasters/Lighthouse/releases) | A separate PC port with a built-in randomizer, ROM-hack support, and language packs. It extracts assets from a user-provided ROM and belongs to the source-reconstruction project chain. |

---

### 🏰 Castlevania: Symphony of the Night

<a href="https://thegamingemporium.com/Images/Games/castlevania-symphony-of-the-night-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/castlevania-symphony-of-the-night-recompilation.webp" alt="Castlevania: Symphony of the Night game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Konami's 1997 PlayStation game centers on Alucard exploring a connected castle. The rows separate source decompilation from a later recompilation project.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **BlackLabelHQ/SymphonyRecomp** | [BlackLabelHQ/SymphonyRecomp](https://github.com/BlackLabelHQ/SymphonyRecomp) | A recompilation effort for Castlevania: Symphony of the Night. |
| **Xeeynamo/sotn-decomp** | [Xeeynamo/sotn-decomp](https://github.com/Xeeynamo/sotn-decomp) | A source reconstruction covering PlayStation, PSP, and Saturn variants; it is distinct from the recompilation above. |

---

### 🏰 Castlevania 64

<a href="https://thegamingemporium.com/Images/Games/castlevania-64-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/castlevania-64-recompilation.webp" alt="Castlevania 64 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 1999 Nintendo 64 Castlevania game brought the series into 3D. Two independent recompilation projects appear below; neither should be conflated with the original game's source.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **RevoSucks/CV64Recomp** | [GitHub](https://github.com/RevoSucks/CV64Recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | An N64 recompilation work in progress. Its README explicitly says it does not yet build, so it is a research project rather than a playable release. |
| **spacefarergames/CV64-Recomp** | [GitHub](https://github.com/spacefarergames/CV64-Recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A separate Windows x64 recompilation and remaster effort. Its README describes 60 FPS play, manual camera control, and graphics changes; those are author-reported features. |

---

### 🧭 Sly Cooper and the Thievius Raccoonus

<a href="https://thegamingemporium.com/Images/Games/sly-cooper-and-the-thievius-raccoonus-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/sly-cooper-and-the-thievius-raccoonus-recompilation.webp" alt="Sly Cooper and the Thievius Raccoonus game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The first Sly Cooper game arrived on PlayStation 2 in 2002, combining stealth and platforming. Its entries are distinct reverse-engineering and port-related efforts.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **theclub654/ProjectCane** | [ProjectCane](https://github.com/theclub654/ProjectCane) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A playable PC reconstruction of the first Sly Cooper game built through reverse engineering. |
| **TheOnlyZac/sly1** | [sly1](https://github.com/TheOnlyZac/sly1) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A separate Sly Cooper source reconstruction, listed alongside ProjectCane. |

---

### 🧭 Ratchet & Clank

<a href="https://en.wikipedia.org/wiki/File:Ratchet_%26_Clank_screenshot.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/0/00/Ratchet_%26_Clank_screenshot.jpg" alt="Ratchet &amp; Clank game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Ratchet_%26_Clank_screenshot.jpg)</sub>

The 2002 PlayStation 2 original pairs platforming with a large arsenal of gadgets and weapons. The repository below is a matching decompilation in progress.

<sub>Original platform: PlayStation 2.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenRAC/rac1-decomp** | [OpenRAC/rac1-decomp](https://github.com/OpenRAC/rac1-decomp) | An in-progress matching source decompilation of the first PS2 game. |

---

### 🧭 Jak and Daxter series

<a href="https://thegamingemporium.com/Images/Games/opengoal-jak-daxter-jak-2-and-jak-3-native-pc-ports.webp"><img src="https://thegamingemporium.com/Images/Games/opengoal-jak-daxter-jak-2-and-jak-3-native-pc-ports.webp" alt="Jak and Daxter series game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Naughty Dog's PlayStation 2 trilogy runs from The Precursor Legacy through Jak II and Jak 3. OpenGOAL works across these games, so this heading is a clearly marked series group rather than one release. [OpenGOAL FAQ](https://opengoal.dev/docs/faq/)

| Project | Resources | What makes it different |
|:--|:--|:--|
| **open-goal/jak-project** | [open-goal/jak-project](https://github.com/open-goal/jak-project) | OpenGOAL reconstructs the Jak and Daxter games’ GOAL code and supports native PC play. Its scope covers multiple games in the series. |

---

### 🧭 The Simpsons Game (2007)

<a href="https://en.wikipedia.org/wiki/File:The_Simpsons_Game_XBOX_360_Cover.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/a/a2/The_Simpsons_Game_XBOX_360_Cover.jpg" alt="The Simpsons Game (2007) game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:The_Simpsons_Game_XBOX_360_Cover.jpg)</sub>

Released across several platforms in 2007, this action platformer sends the Simpsons family through parodies of game genres. The listed project focuses on recompiling a console version.

<sub>Listed project's target: Xbox 360 edition. Distinct from The Simpsons Wrestling.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **YesterMester/TheSimpsonsGameRecomp** | [YesterMester/TheSimpsonsGameRecomp](https://github.com/YesterMester/TheSimpsonsGameRecomp) | A static recompilation targeting native Linux, Steam Deck, and Windows builds. The README reports playable releases with different testing depth by platform. |

---

### 🧭 The Lord of the Rings: The Two Towers

<a href="https://github.com/user-attachments/assets/40906651-76c2-4405-ab39-2425bb26baa7"><img src="https://github.com/user-attachments/assets/40906651-76c2-4405-ab39-2425bb26baa7" alt="The Lord of the Rings: The Two Towers game image" width="400"></a><br><sub>[Project image](https://github.com/Gumpolas/TooTawersRecomp)</sub>

This 2002 action game adapts battles from the first two film installments. The repository below targets a particular original game build, not the film itself.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Gumpolas/TooTawersRecomp** | [TooTawersRecomp](https://github.com/Gumpolas/TooTawersRecomp) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A recompilation project focused on The Lord of the Rings: The Two Towers. |

---

### 🧭 LEGO Island

<a href="https://thegamingemporium.com/Images/Games/lego-island-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/lego-island-pc-port.webp" alt="LEGO Island game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1997 Windows game lets players explore LEGO Island and complete small missions. Its source reconstruction and portable follow-on project serve different purposes.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **isledecomp/isle** | [isledecomp/isle](https://github.com/isledecomp/isle) | A source reconstruction of LEGO Island, including work on the original game and its engine. |
| **isledecomp/isle-portable** | [isledecomp/isle-portable](https://github.com/isledecomp/isle-portable) · [Browser edition](https://isle.pizza/) | A portable build derived from the LEGO Island decompilation, with a browser edition available from the project site. |

---

### 🧭 MediEvil

<a href="https://thegamingemporium.com/Images/Games/medievil-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/medievil-recompilation.webp" alt="MediEvil game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Sony's 1998 PlayStation action adventure follows Sir Daniel Fortesque through Gallowmere. Its decompilation and recompilation efforts are shown together for comparison.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **BlackLabelHQ/MediEvilRecomp** | [MediEvilRecomp](https://github.com/BlackLabelHQ/MediEvilRecomp) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A MediEvil recompilation project, distinct from the source decompilation listed below. |
| **MediEvilDecompilation/medievil-decomp** | [medievil-decomp](https://github.com/MediEvilDecompilation/medievil-decomp) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A source-decompilation project for the original MediEvil. |

---

### 🧭 ICO

<a href="https://thegamingemporium.com/Images/Games/ico-recompilation-for-android.webp"><img src="https://thegamingemporium.com/Images/Games/ico-recompilation-for-android.webp" alt="ICO game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2001 PlayStation 2 adventure follows a boy and Yorda through a stark castle. The listed PC-oriented project is distinct from an official release.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **nathanialf/ico-pc** | [ico-pc](https://github.com/nathanialf/ico-pc) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A PC port project for ICO. |

---

### 🧭 Peter Jackson’s King Kong

<a href="https://thegamingemporium.com/Images/Games/peter-jacksons-king-kong-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/peter-jacksons-king-kong-recompilation.webp" alt="Peter Jackson’s King Kong game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Released in 2005 alongside the film, this action game alternates between human and Kong sequences. The listed effort recompiles an existing game version.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **TekRantGaming/king-kong-recompiled** | [king-kong-recompiled](https://github.com/TekRantGaming/king-kong-recompiled) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A recompilation project for Peter Jackson’s King Kong. |

---

<a id="rpgs--roguelikes"></a>
## 🧙 RPGs & roguelikes

Role-playing games, action RPGs, and roguelikes.

### ⚡ Pokémon Red & Blue

<a href="https://en.wikipedia.org/wiki/File:Pok%C3%A9mon_Red_and_Blue_cover_art.webp"><img src="https://thumb.wikimedia.org/wikipedia/en/thumb/a/af/Pok%C3%A9mon_Red_and_Blue_cover_art.webp/500px-Pok%C3%A9mon_Red_and_Blue_cover_art.webp" alt="Pokémon Red &amp; Blue game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Pok%C3%A9mon_Red_and_Blue_cover_art.webp)</sub>

These first-generation Game Boy Pokémon games established collecting, trading, and turn-based battles. Their assembly reconstruction represents original handheld code, not a new PC game.

<sub>Original platform: Game Boy.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokered** | [pret/pokered](https://github.com/pret/pokered) | A source reconstruction of the original Game Boy games in assembly. |

---

### ⚡ Pokémon Crystal

<a href="https://pokemondb.net/crystal"><img src="https://img.pokemondb.net/boxes/lg/crystal-large.jpg" alt="Pokémon Crystal game image" width="400"></a><br><sub>[Original box art](https://pokemondb.net/crystal)</sub>

This Game Boy Color follow-up expanded the Gold and Silver era with new story material and features. Its repository reconstructs the original handheld game's code.

<sub>Original platform: Game Boy Color.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokecrystal** | [pret/pokecrystal](https://github.com/pret/pokecrystal) | A source reconstruction of the Game Boy Color game in assembly. |

---

### ⚡ Pokémon Ruby & Sapphire

<a href="https://en.wikipedia.org/wiki/File:PokemonRubySapphireBox.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/b/be/PokemonRubySapphireBox.jpg" alt="Pokémon Ruby &amp; Sapphire game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:PokemonRubySapphireBox.jpg)</sub>

The 2002 Game Boy Advance pair brought Pokémon into the Hoenn region. The source project covers the original paired releases.

<sub>Original platform: Game Boy Advance.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokeruby** | [pret/pokeruby](https://github.com/pret/pokeruby) | A source reconstruction covering Ruby and Sapphire. |

---

### ⚡ Pokémon Emerald

<a href="https://pokedexgenerator.com/game-box-art/11-pokemon-emerald-version.jpg"><img src="https://pokedexgenerator.com/game-box-art/11-pokemon-emerald-version.jpg" alt="Pokémon Emerald game image" width="400"></a><br><sub>[Original cover](https://pokedexgenerator.com/walkthroughs/pokemon-emerald)</sub>

Emerald revisited Hoenn on Game Boy Advance in 2004 with a revised story and Battle Frontier. Its source reconstruction is separate from the earlier Ruby and Sapphire project.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokeemerald** | [pret/pokeemerald](https://github.com/pret/pokeemerald) | A Pokémon Emerald source reconstruction used for studying and rebuilding the Game Boy Advance game. |

---

### ⚡ Pokémon FireRed

<a href="https://img.pokemondb.net/boxes/lg/firered-large.jpg"><img src="https://img.pokemondb.net/boxes/lg/firered-large.jpg" alt="Pokémon FireRed game image" width="400"></a><br><sub>[Original cover](https://pokemondb.net/firered-leafgreen)</sub>

This 2004 Game Boy Advance remake revisits the first generation's Kanto adventure. The listed work targets the remake, rather than the original Game Boy games.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokefirered** | [pret/pokefirered](https://github.com/pret/pokefirered) | A source reconstruction for Pokémon FireRed. This is a distinct game repository from pokeemerald. |

---

### ⚡ Pokémon HeartGold

<a href="https://img.pokemondb.net/boxes/lg/heartgold-large.jpg"><img src="https://img.pokemondb.net/boxes/lg/heartgold-large.jpg" alt="Pokémon HeartGold Nintendo DS box art" width="400"></a><br><sub>[Original box art](https://pokemondb.net/heartgold-soulsilver)</sub>

HeartGold is a 2009 Nintendo DS remake of Pokémon Gold. The listed matching source project concerns this DS game, not a generic Pokémon port.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokeheartgold** | [pret/pokeheartgold](https://github.com/pret/pokeheartgold) | A work-in-progress Nintendo DS disassembly that builds the US HeartGold and SoulSilver ROMs; both games share this repository. |

---

### ⚡ Pokémon SoulSilver

<a href="https://img.pokemondb.net/boxes/lg/soulsilver-large.jpg"><img src="https://img.pokemondb.net/boxes/lg/soulsilver-large.jpg" alt="Pokémon SoulSilver Nintendo DS box art" width="400"></a><br><sub>[Original box art](https://pokemondb.net/heartgold-soulsilver)</sub>

SoulSilver is the Nintendo DS companion remake to HeartGold. The entry is kept separate because its game build and source target differ.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokeheartgold** | [pret/pokeheartgold](https://github.com/pret/pokeheartgold) | A work-in-progress Nintendo DS disassembly that builds the US HeartGold and SoulSilver ROMs; both games share this repository. |

---

### ⚡ Pokémon Platinum

<a href="https://thegamingemporium.com/Images/Games/pokemon-platinum-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/pokemon-platinum-pc-port.webp" alt="Pokémon Platinum game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2008 Nintendo DS revision of Diamond and Pearl changes parts of Sinnoh's story and roster. The repositories below cover different development efforts.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **pret/pokeplatinum** | [pokeplatinum](https://github.com/pret/pokeplatinum) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Pokémon Platinum source reconstruction for the Nintendo DS release. |
| **cybervisi0n/pokeplatinum** | [GitHub](https://github.com/cybervisi0n/pokeplatinum) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A 64-bit PC port based on pret's decompilation and libntr. Unlike the original DS source project, it aims to compile and debug both a PC build and a DS ROM from one source tree. |

---

### ⚡ Pokémon Ultra Sun

<a href="https://cdn.wikimg.net/en/strategywiki/images/thumb/f/fa/Pokemon_Ultra_Sun_Box_Art.jpg/300px-Pokemon_Ultra_Sun_Box_Art.jpg"><img src="https://cdn.wikimg.net/en/strategywiki/images/thumb/f/fa/Pokemon_Ultra_Sun_Box_Art.jpg/300px-Pokemon_Ultra_Sun_Box_Art.jpg" alt="Pokémon Ultra Sun game image" width="400"></a><br><sub>[Original cover](https://strategywiki.org/wiki/File:Pokemon_Ultra_Sun_Box_Art.jpg)</sub>

Released for Nintendo 3DS in 2017, Ultra Sun revises the Alola adventure. The listed REA-associated work is partial; it is not a full-game reconstruction.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **tylergraydev/UltraSunnyMoon** | [tylergraydev/UltraSunnyMoon](https://github.com/tylergraydev/UltraSunnyMoon) | A partial, hybrid reconstruction of Pokémon Ultra Sun. |

---

### 🗝️ Kingdom Hearts 358/2 Days

<a href="https://en.wikipedia.org/wiki/File:Kingdom_Hearts_358_2_Gameplay.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/5/51/Kingdom_Hearts_358_2_Gameplay.jpg" alt="Kingdom Hearts 358/2 Days game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Kingdom_Hearts_358_2_Gameplay.jpg)</sub>

The 2009 Nintendo DS entry follows Roxas during the gap between major Kingdom Hearts stories. Its matching decompilation and experimental PC runtime are separate projects.

<sub>Original platform: Nintendo DS.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Yokimitsuro/khdays-decomp** | [Yokimitsuro/khdays-decomp](https://github.com/Yokimitsuro/khdays-decomp) | A matching DS decompilation; its README says it does not by itself produce a playable build. |
| **Yokimitsuro/khdays-port** | [Yokimitsuro/khdays-port](https://github.com/Yokimitsuro/khdays-port) | A PC runtime built on the decompiled C source. The author labels the port as work in progress. |

---

### 🔥 Diablo II: Resurrected

<a href="https://github.com/jhaizhou-ops/d2r-mobile/blob/main/dm/ios/Assets.xcassets/AppIcon.appiconset/AppIcon1024.png"><img src="https://raw.githubusercontent.com/jhaizhou-ops/d2r-mobile/main/dm/ios/Assets.xcassets/AppIcon.appiconset/AppIcon1024.png" alt="D2R Mobile project app icon for Diablo II: Resurrected" width="400"></a><br><sub>[Project app icon](https://github.com/jhaizhou-ops/d2r-mobile/blob/main/dm/ios/Assets.xcassets/AppIcon.appiconset/AppIcon1024.png)</sub>

Blizzard's 2021 remaster rebuilds Diablo II's presentation for modern systems. The listed D2R Mobile project targets compatibility with the Switch release; an expansion is content within this game, not a second game.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **jhaizhou-ops/d2r-mobile** | [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | A compatibility and targeted program-rewriting project for the Nintendo Switch release of Diablo II: Resurrected on iOS and macOS. The expansion is content within the same game. |

---

### 🔥 Diablo / DevilutionX

<a href="https://thegamingemporium.com/Images/Games/devilutionx-diablo-1-android-port.webp"><img src="https://thegamingemporium.com/Images/Games/devilutionx-diablo-1-android-port.webp" alt="Diablo / DevilutionX game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Diablo is the late-1990s action RPG set beneath Tristram. DevilutionX and its browser descendant bring the game to modern systems.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **diasurgical/DevilutionX** | [diasurgical/DevilutionX](https://github.com/diasurgical/DevilutionX) | A modern source port and reimplementation for the original Diablo and Hellfire, shown here as adjacent work rather than an REA case. |
| **d07RiV/diabloweb** | [d07RiV/diabloweb](https://github.com/d07RiV/diabloweb) · [Browser edition](https://d07riv.github.io/diabloweb/) | A browser port built from Devilution source. The public web page is reachable; play was not independently tested. |

---

### 🧙 The Elder Scrolls III: Morrowind / OpenMW

<a href="https://thegamingemporium.com/Images/Games/openmw-morrowind-port.webp"><img src="https://thegamingemporium.com/Images/Games/openmw-morrowind-port.webp" alt="The Elder Scrolls III: Morrowind / OpenMW game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Bethesda's 2002 RPG takes place on Vvardenfell. OpenMW is a separate engine implementation for Morrowind content, so its row is labeled as adjacent compatibility work.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenMW/openmw** | [OpenMW/openmw](https://github.com/OpenMW/openmw) | An open-source reimplementation of the Morrowind engine. It runs the original game content but is not the original engine’s decompiled source. |

---

### 🧙 Final Fantasy Tactics Advance

<a href="https://en.wikipedia.org/wiki/File:FinalFantasyTacticsAdvanceGBAScreenshot.png"><img src="https://upload.wikimedia.org/wikipedia/en/7/7f/FinalFantasyTacticsAdvanceGBAScreenshot.png" alt="Final Fantasy Tactics Advance game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:FinalFantasyTacticsAdvanceGBAScreenshot.png)</sub>

This 2003 Game Boy Advance tactics RPG places turn-based battles under a system of changing laws. The listed project recompiles the handheld release for newer platforms.

<sub>Original platform: Game Boy Advance.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Jorge262007/FFTARecomp** | [Jorge262007/FFTARecomp](https://github.com/Jorge262007/FFTARecomp) | A native recompilation for Windows, Linux, and Steam Deck built from the user’s own ROM. |

---

### 🧙 Ultima Underworld: The Stygian Abyss

<a href="https://en.wikipedia.org/wiki/File:Ultima_underworld_1_screenshot.png"><img src="https://upload.wikimedia.org/wikipedia/en/0/0d/Ultima_underworld_1_screenshot.png" alt="Ultima Underworld: The Stygian Abyss game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Ultima_underworld_1_screenshot.png)</sub>

The 1992 DOS dungeon RPG presented a continuous first-person world beneath Britannia. Its shared project with the sequel should be read as covering two distinct original games.

<sub>Original platform: DOS.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **abedegno/underworld-exhumed** | [abedegno/underworld-exhumed](https://github.com/abedegno/underworld-exhumed) · [Web build](https://abedegno.github.io/underworld-exhumed-web/) | A byte-matching source reconstruction and modern native port. The shared repository also covers Ultima Underworld II. |

---

### 🧙 Ultima Underworld II: Labyrinth of Worlds

<a href="https://en.wikipedia.org/wiki/File:Ultima-underworld-II-box.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/9/9b/Ultima-underworld-II-box.jpg" alt="Ultima Underworld II: Labyrinth of Worlds game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Ultima-underworld-II-box.jpg)</sub>

The 1993 DOS sequel sends the player between multiple worlds beyond Britannia. It shares a source and port project with the first Ultima Underworld, but remains a separate game.

<sub>Original platform: DOS.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **abedegno/underworld-exhumed** | [abedegno/underworld-exhumed](https://github.com/abedegno/underworld-exhumed) · [Web build](https://abedegno.github.io/underworld-exhumed-web/) | A second game in the same byte-matching source and native-port repository; users provide original game files. |

---

### 🧙 Vandal Hearts

<a href="https://en.wikipedia.org/wiki/File:Vandal_Hearts_Coverart.png"><img src="https://upload.wikimedia.org/wikipedia/en/2/26/Vandal_Hearts_Coverart.png" alt="Vandal Hearts game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Vandal_Hearts_Coverart.png)</sub>

This 1996 tactical RPG began on PlayStation and uses grid-based battles. The listed PC port builds on a matching decompilation effort.

<sub>Original platform: PlayStation.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **HalmyLyseas/VandalHearts-PcPort** | [HalmyLyseas/VandalHearts-PcPort](https://github.com/HalmyLyseas/VandalHearts-PcPort) | A native PC port built from a matching reconstruction of the PlayStation game. |

---

### 🧙 Paper Mario

<a href="https://thegamingemporium.com/Images/Games/paper-mario-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/paper-mario-decompilation.webp" alt="Paper Mario game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Nintendo's 2000 Nintendo 64 RPG uses a flat-paper look within a 3D world. Its reconstructed source, recompilation, and native-port projects each occupy a different step in the project chain.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **lucyawrey/Paper_Mario_64_Recomp** | [Paper_Mario_64_Recomp](https://github.com/lucyawrey/Paper_Mario_64_Recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A Paper Mario 64 recompilation project, separate from the source reconstruction below. |
| **pmret/papermario** | [pmret/papermario](https://github.com/pmret/papermario) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A source reconstruction of the Nintendo 64 Paper Mario game. |
| **HarbourMasters/PaperBoat** | [HarbourMasters/PaperBoat](https://github.com/HarbourMasters/PaperBoat) | A native Paper Mario port built on reconstructed game code. |

---

### 🧙 The Binding of Isaac

<a href="https://thegamingemporium.com/Images/Games/the-binding-of-isaac-recompilation-for-android.webp"><img src="https://thegamingemporium.com/Images/Games/the-binding-of-isaac-recompilation-for-android.webp" alt="The Binding of Isaac game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 2011 indie roguelike combines randomized rooms, items, and permadeath. The listed project concerns recompiling an existing game build for a new runtime.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **whylurking/IsaacRecomp** | [whylurking/IsaacRecomp](https://github.com/whylurking/IsaacRecomp) | A C++ recreation of the original Flash-era Binding of Isaac. |

---

### 🧙 Lost Odyssey

<a href="https://thegamingemporium.com/Images/Games/lost-odyssey-for-android.webp"><img src="https://thegamingemporium.com/Images/Games/lost-odyssey-for-android.webp" alt="Lost Odyssey game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This Xbox 360 RPG debuted in 2007 and tells the story of the immortal Kaim. The cataloged project targets the original console game for a newer platform.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **freefrank/LostOdysseyRecomp** | [freefrank/LostOdysseyRecomp](https://github.com/freefrank/LostOdysseyRecomp) | A Lost Odyssey recompilation project. |

---

<a id="action-shooters--fighting"></a>
## ⚔️ Action, shooters & fighting

Open-world action, shooters, and fighting games.

### 🚗 Grand Theft Auto: Vice City Stories

<a href="https://thegamingemporium.com/Images/Games/gta-vice-city-stories-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/gta-vice-city-stories-recompilation.webp" alt="Grand Theft Auto: Vice City Stories game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Rockstar's 2006 PSP prequel returns to Vice City. The entries below cover a recompilation profile and a separate game project.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **PSPRecomp · Vice City Stories profile** | [PSPRecomp VCS profile](https://github.com/jessicanataliagta/PSPRecomp/tree/main/profiles/vcs) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Vice City Stories profile inside a broader PSP recompilation tool. This link points to configuration, not to a standalone finished port. |
| **codepdbh/PSPRecomp-VCS-Android** | [PSPRecomp-VCS-Android](https://github.com/codepdbh/PSPRecomp-VCS-Android) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | An Android-focused Vice City Stories project. Its target platform differs from the PC port shown in the archive screenshot. |

---

### 🚗 Grand Theft Auto: Liberty City Stories

<a href="https://thegamingemporium.com/Images/Games/gta-liberty-city-stories-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/gta-liberty-city-stories-recompilation.webp" alt="Grand Theft Auto: Liberty City Stories game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2005 PSP game revisits Liberty City before GTA III. The listed entry is a platform-specific recompilation effort.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **elmasas/lcs-recomp** | [lcs-recomp](https://github.com/elmasas/lcs-recomp) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Liberty City Stories recompilation project aimed at PC. |

---

### ⚔️ GoldenEye 007

<a href="https://en.wikipedia.org/wiki/File:GoldenEye_007_N64_cover.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/1/13/GoldenEye_007_N64_cover.jpg" alt="GoldenEye 007 game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:GoldenEye_007_N64_cover.jpg)</sub>

Rare's 1997 Nintendo 64 shooter adapts the James Bond film with mission objectives and local multiplayer. Its source reconstruction and PC-port work are different projects.

<sub>Original platform: Nintendo 64. An Archive upload with the same game title is a separate, unlinked artifact.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **n64decomp/007** | [n64decomp/007](https://github.com/n64decomp/007) · [GitLab upstream](https://gitlab.com/kholdfuzion/goldeneye_src) | A GitHub mirror of the in-progress GoldenEye source decompilation; follow the GitLab upstream for the original work. |
| **jkdansereau/goldeneye-pc-port** | [jkdansereau/goldeneye-pc-port](https://github.com/jkdansereau/goldeneye-pc-port) | A native PC port based on GoldenEye decompilation work, separate from the source reconstruction above. |

---

### 🛡️ Halo

<a href="https://thegamingemporium.com/Images/Games/halo-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/halo-decompilation.webp" alt="Halo game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Halo: Combat Evolved debuted on Xbox in 2001 and established the series' ringworld setting. The project below focuses on compatibility and porting work.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **chrissotraidis/projectreach** | [Halo: Combat Evolved related project](https://github.com/chrissotraidis/projectreach) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Halo: Combat Evolved compatibility and porting project. |

---

### 🥊 Super Smash Bros. Ultimate

<a href="https://github.com/Denkishi/ssbu-recomp/blob/main/media/menus.webp"><img src="https://raw.githubusercontent.com/Denkishi/ssbu-recomp/main/media/menus.webp" alt="Super Smash Bros. Ultimate game image" width="400"></a><br><sub>[Project menu screenshot](https://github.com/Denkishi/ssbu-recomp/blob/main/media/menus.webp)</sub>

Nintendo's 2018 Switch crossover fighter gathers characters from many game series. The project below recompiles a specific Switch version for Windows.

<sub>Original platform: Switch.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Denkishi/ssbu-recomp** | [Denkishi/ssbu-recomp](https://github.com/Denkishi/ssbu-recomp) · [Creator X post](https://x.com/dddenk_/status/2110936700281393413) | A Switch 13.0.4-to-Windows static recompilation. The creator posted a gameplay video; users supply their own game dump. Runtime was not independently tested. |

---

### ⚔️ Dragon Ball Z: Budokai Tenkaichi 3

<a href="https://en.wikipedia.org/wiki/File:DBZ_Budokai_Tenkaichi_3_Cover.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/d/df/DBZ_Budokai_Tenkaichi_3_Cover.jpg" alt="Dragon Ball Z: Budokai Tenkaichi 3 game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:DBZ_Budokai_Tenkaichi_3_Cover.jpg)</sub>

This 2007 PlayStation 2 and Wii arena fighter has a large Dragon Ball roster. Its PC-oriented project builds on matching source work and requires original game data.

<sub>Original platform: PlayStation 2.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **z3xox/Tenkaichi3Decomp** | [z3xox/Tenkaichi3Decomp](https://github.com/z3xox/Tenkaichi3Decomp) | A native PC port based on matching decompilation work; original disc data is required. |

---

### 🛡️ Halo 2

<a href="https://en.wikipedia.org/wiki/File:Halo_2_(screenshot).jpg"><img src="https://upload.wikimedia.org/wikipedia/en/0/0b/Halo_2_%28screenshot%29.jpg" alt="Halo 2 game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Halo_2_(screenshot).jpg)</sub>

The 2004 Xbox sequel adds dual-wielding and an expanded multiplayer mode. The listed decompilation targets Halo 2 specifically, not the first Halo game above.

<sub>Original platform: Xbox.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **kirklandsig/halo2-decompiled** | [kirklandsig/halo2-decompiled](https://github.com/kirklandsig/halo2-decompiled) | An Xbox game decompilation project. It is distinct from Halo: Combat Evolved. |

---

### 🥊 Super Smash Bros. Melee

<a href="https://thegamingemporium.com/Images/Games/super-smash-bros.-melee-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/super-smash-bros.-melee-decompilation.webp" alt="Super Smash Bros. Melee game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2001 GameCube fighting game became a lasting competitive title. Its original-code reconstruction and later PC-facing work should be compared as separate projects.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **doldecomp/melee** | [doldecomp/melee](https://github.com/doldecomp/melee) | A source-decompilation effort for Super Smash Bros. Melee on GameCube. |
| **Hero88go/melee-unlocked** | [Hero88go/melee-unlocked](https://github.com/Hero88go/melee-unlocked) | A Windows native source port, separate from the GameCube decompilation project above. |

---

### ⚔️ Saints Row

<a href="https://thegamingemporium.com/Images/Games/saints-row-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/saints-row-recompilation.webp" alt="Saints Row game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The first Saints Row launched on Xbox 360 in 2006 as an open-world crime game. The listed effort studies that initial release rather than later series entries.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **whompay/SaintsReborn** | [SaintsReborn](https://github.com/whompay/SaintsReborn) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A Saints Row port and reconstruction project. |

---

### 🦊 Star Fox 64

<a href="https://thegamingemporium.com/Images/Games/star-fox-64-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/star-fox-64-recompilation.webp" alt="Star Fox 64 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 1997 Nintendo 64 rail shooter follows Fox McCloud's team through branching missions. A recompilation and a native-port project are listed separately.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **sonicdcer/Starfox64Recomp** | [sonicdcer/Starfox64Recomp](https://github.com/sonicdcer/Starfox64Recomp) | A Star Fox 64 recompilation project, linked separately from decompilation projects for other Nintendo 64 games. |
| **HarbourMasters/Starship** | [HarbourMasters/Starship](https://github.com/HarbourMasters/Starship) | A native PC port of Star Fox 64, separate from the recompilation listed above. |

---

### ⚔️ Perfect Dark

<a href="https://thegamingemporium.com/Images/Games/perfect-dark-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/perfect-dark-pc-port.webp" alt="Perfect Dark game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Rare's 2000 Nintendo 64 spy shooter follows Joanna Dark. The source reconstruction and PC-oriented follow-on work have different project roles.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **perfect-dark-pc-port/perfect_dark** | [perfect-dark-pc-port/perfect_dark](https://github.com/perfect-dark-pc-port/perfect_dark) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A native PC port of Perfect Dark based on reconstructed game code. |
| **n64decomp/perfect_dark** | [n64decomp/perfect_dark](https://github.com/n64decomp/perfect_dark) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A source reconstruction of the Nintendo 64 Perfect Dark release. |

---

### 🕵️ Syphon Filter

<a href="https://thegamingemporium.com/Images/Games/syphon-filter-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/syphon-filter-recompilation.webp" alt="Syphon Filter game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1999 PlayStation action game follows agent Gabe Logan. The linked reverse-engineering work concerns the first title, apart from The Omega Strain below.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Madxbio97/SF-pc-port** | [SF-pc-port](https://github.com/Madxbio97/SF-pc-port) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A PC port project for Syphon Filter. |

---

### 🕵️ Syphon Filter: The Omega Strain

<a href="https://en.wikipedia.org/wiki/File:Syphon_Filter_The_Omega_Strain.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/9/9d/Syphon_Filter_The_Omega_Strain.jpg" alt="Syphon Filter: The Omega Strain game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Syphon_Filter_The_Omega_Strain.jpg)</sub>

The 2004 PlayStation 2 entry shifts the series toward created agents and mission-based play. Its decompilation is separate from the original Syphon Filter project.

<sub>Original platform: PlayStation 2.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zm2283145/syphon-filter-omega-strain-decomp** | [zm2283145/syphon-filter-omega-strain-decomp](https://github.com/zm2283145/syphon-filter-omega-strain-decomp) | A matching source decompilation of the PS2 entry, distinct from the first Syphon Filter. |

---

### ⚔️ The Darkness

<a href="https://thegamingemporium.com/Images/Games/the-darkness-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/the-darkness-recompilation.webp" alt="The Darkness game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2007 console shooter adapts the comic series around Jackie Estacado's supernatural powers. The project below focuses on recompiling the console release.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **portingpete/The-Darkness-Recomp** | [The-Darkness-Recomp](https://github.com/portingpete/The-Darkness-Recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A recompilation project for The Darkness. |

---

<a id="horror--suspense"></a>
## 👻 Horror & suspense

Survival-horror and suspense games.

### 👻 P.T.

<a href="https://github.com/LoreanXavier/pt-pc/blob/main/docs/media/lisa.gif"><img src="https://raw.githubusercontent.com/LoreanXavier/pt-pc/main/docs/media/lisa.gif" alt="P.T. PC port project image" width="400"></a><br><sub>[Project image](https://github.com/LoreanXavier/pt-pc/blob/main/docs/media/lisa.gif)</sub>

Konami's 2014 PlayStation 4 playable teaser became known for its looping hallway and its connection to Silent Hills. The listed PC port needs original game data; an Archive upload is a separate artifact.

<sub>Original platform: PlayStation 4.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **LoreanXavier/pt-pc** | [LoreanXavier/pt-pc](https://github.com/LoreanXavier/pt-pc) · [Archive item](https://archive.org/details/p.-t.-pc-port-) | A native PC port that reads data from the user’s own PS4 copy. The Archive item metadata names this repository, but the uploaded files have not been matched to a release. |

---

### 👻 Silent Hill

<a href="https://thegamingemporium.com/Images/Games/silent-hill-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/silent-hill-pc-port.webp" alt="Silent Hill game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1999 PlayStation horror game follows Harry Mason through the fog-bound town. The listed source work targets this first game, not the broader franchise.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **shdecompilations/silent-hill-decomp** | [silent-hill-decomp](https://github.com/shdecompilations/silent-hill-decomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A source-decompilation project focused on the original Silent Hill. |

---

### 🧟 Dead Rising 2: Case Zero

<a href="https://www.imdb.com/title/tt1744763/"><img src="https://m.media-amazon.com/images/M/MV5BNjdiZDlhNjQtNzFmMS00MmY5LTk1NzMtZDdlMTZmNDJmNjBiXkEyXkFqcGc%40._V1_.jpg" alt="Dead Rising 2: Case Zero game image" width="400"></a><br><sub>[Original game cover](https://www.imdb.com/title/tt1744763/)</sub>

This 2010 Xbox 360 prologue to Dead Rising 2 follows Chuck Greene before the main game. It has its own recompilation project and is distinct from Case West.

<sub>Original platform: Xbox 360.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **wivi514/Dead_Rising_2_Case_Zero_Xenon_Recomp** | [wivi514/Dead_Rising_2_Case_Zero_Xenon_Recomp](https://github.com/wivi514/Dead_Rising_2_Case_Zero_Xenon_Recomp) | A native PC static recompilation project for the Xbox 360 standalone prologue. |

---

### 🧟 Dead Rising 2: Case West

<a href="https://www.mobygames.com/game/87222/dead-rising-2-case-west/cover/group-139971/cover-396399/"><img src="https://cdn.mobygames.com/covers/2279002-dead-rising-2-case-west-xbox-360-front-cover.jpg" alt="Dead Rising 2: Case West game image" width="400"></a><br><sub>[Original game cover](https://www.mobygames.com/game/87222/dead-rising-2-case-west/cover/group-139971/cover-396399/)</sub>

This 2010 Xbox 360 epilogue pairs Chuck Greene with Frank West. Its recompilation project targets this separate episode, not Case Zero.

<sub>Original platform: Xbox 360.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **wivi514/Dead_Rising_2_Case_West_Xenon_Recomp** | [wivi514/Dead_Rising_2_Case_West_Xenon_Recomp](https://github.com/wivi514/Dead_Rising_2_Case_West_Xenon_Recomp) | A separate static recompilation project for the Xbox 360 standalone follow-up. |

---

### 👻 Fatal Frame

<a href="https://thegamingemporium.com/Images/Games/fatal-frame-decompilation.webp"><img src="https://thegamingemporium.com/Images/Games/fatal-frame-decompilation.webp" alt="Fatal Frame game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The first Fatal Frame debuted on PlayStation 2 in 2001 and makes a camera the player's main defense. The linked project concerns this original horror game.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Mikompilation/Himuro** | [Himuro](https://github.com/Mikompilation/Himuro) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A decompilation project for the first Fatal Frame game. |
| **Mikompilation/MikuPan** | [MikuPan](https://github.com/Mikompilation/MikuPan) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A native PC port of the first Fatal Frame, based on Himuro. The repository describes it as work in progress. |

---

<a id="racing--sports"></a>
## 🏁 Racing & sports

Racing, driving, skating, football, wrestling, and winter sports.

### 🏎️ Mario Kart 64

<a href="https://thegamingemporium.com/Images/Games/mario-kart-64-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/mario-kart-64-recompilation.webp" alt="Mario Kart 64 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Nintendo's 1996 Nintendo 64 racer brought Mario Kart into 3D tracks and four-player local races. Source reconstruction, recompilation, and native-port projects are grouped below. [Nintendo history](https://www.nintendo.com/jp/character/mario/en/history/index.html)

| Project | Resources | What makes it different |
|:--|:--|:--|
| **n64decomp/mk64** | [n64decomp/mk64](https://github.com/n64decomp/mk64) | A source reconstruction of Mario Kart 64. |
| **sonicdcer/MarioKart64Recomp** | [sonicdcer/MarioKart64Recomp](https://github.com/sonicdcer/MarioKart64Recomp) | A recompilation project for Mario Kart 64; it represents a different technical route from n64decomp/mk64. |
| **HarbourMasters/SpaghettiKart** | [HarbourMasters/SpaghettiKart](https://github.com/HarbourMasters/SpaghettiKart) | A native port in the Mario Kart 64 project chain, separate from the existing decompilation and recompilation projects. |

---

### 🏎️ Need for Speed: Most Wanted (2005)

<a href="https://github.com/SpeedBreakerProject/speedbreaker/blob/main/assets/screenshots/speedbreaker-00-ultrawide-chase-cam-race.jpg"><img src="https://raw.githubusercontent.com/SpeedBreakerProject/speedbreaker/main/assets/screenshots/speedbreaker-00-ultrawide-chase-cam-race.jpg" alt="Need for Speed: Most Wanted (2005) game image" width="400"></a><br><sub>[Project gameplay screenshot](https://github.com/SpeedBreakerProject/speedbreaker/blob/main/assets/screenshots/speedbreaker-00-ultrawide-chase-cam-race.jpg)</sub>

The 2005 street-racing game mixes police pursuits with a ranked rival list. The cataloged static recompilation targets the Xbox 360 version.

<sub>Original platform: Xbox 360.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **SpeedBreakerProject/speedbreaker** | [SpeedBreakerProject/speedbreaker](https://github.com/SpeedBreakerProject/speedbreaker) | A static recompilation and native PC port of the Xbox 360 release. |

---

### 🏎️ Need for Speed: Underground 2

<a href="https://en.wikipedia.org/wiki/File:Nfsu2-win-cover.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/1/10/Nfsu2-win-cover.jpg" alt="Need for Speed: Underground 2 game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Nfsu2-win-cover.jpg)</sub>

This 2004 racing sequel centers on car customization and an explorable city. The listed project recompiles the original PC code for other targets.

<sub>Original platform: Windows.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **codepdbh/nfsu2-recompiled** | [codepdbh/nfsu2-recompiled](https://github.com/codepdbh/nfsu2-recompiled) | A recompilation of the original Windows x86 game, with an Android build described in the README; original game data is required. |

---

### 🏁 Skate 3

<a href="https://github.com/mchughalex/skate3recomp/blob/main/banner-light.png"><img src="https://raw.githubusercontent.com/mchughalex/skate3recomp/main/banner-light.png" alt="Skate 3 game image" width="400"></a><br><sub>[Project banner](https://github.com/mchughalex/skate3recomp/blob/main/banner-light.png)</sub>

The 2010 skateboarding game focuses on tricks, spots, and team play. Its recompilation work is early-stage and should not be presented as a completed port.

<sub>Original platform: Xbox 360.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **mchughalex/skate3recomp** | [mchughalex/skate3recomp](https://github.com/mchughalex/skate3recomp) | An early Xbox 360 static recompilation. Renderer and full-game testing remain incomplete. |

---

### 🏁 Dead or Alive Xtreme Beach Volleyball

<a href="https://en.wikipedia.org/wiki/File:Doaxbvbox.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/8/8d/Doaxbvbox.jpg" alt="Dead or Alive Xtreme Beach Volleyball game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Doaxbvbox.jpg)</sub>

Released for the original Xbox in 2003, this spin-off shifts the Dead or Alive cast to beach sports. The listed project is a recompilation and native PC-port effort.

<sub>Original platform: Xbox.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **NoRain211/doaxvb-re** | [NoRain211/doaxvb-re](https://github.com/NoRain211/doaxvb-re) · [Archive item](https://archive.org/details/dead-or-alive-xtreme-beach-volleyball_202610) | A static recompilation with a hand-written runtime and native PC releases. A same-title Archive upload has not been linked to this repository. |

---

### 🏁 FIFA Street

<a href="https://thegamingemporium.com/Images/Games/fifa-street-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/fifa-street-pc-port.webp" alt="FIFA Street game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

EA's 2005 spin-off moves football into smaller street matches and trick-based play. The entry concerns a specific original console game, not the wider FIFA series.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **samuelit0davila/fifa-street-pc-port** | [fifa-street-pc-port](https://github.com/samuelit0davila/fifa-street-pc-port) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A PC port project for FIFA Street. |

---

### 🌀 Crash Team Racing

<a href="https://thegamingemporium.com/Images/Games/crash-team-racing-turbocharged.webp"><img src="https://thegamingemporium.com/Images/Games/crash-team-racing-turbocharged.webp" alt="Crash Team Racing game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1999 PlayStation kart racer brings Crash Bandicoot characters onto tracks with boost-focused driving. The listed effort targets the original game rather than its later remake.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **CameronRedmore/Crash-Team-Racing-Turbocharged** | [Crash-Team-Racing-Turbocharged](https://github.com/CameronRedmore/Crash-Team-Racing-Turbocharged) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A Crash Team Racing project called Turbocharged. |

---

### 🏁 Tony Hawk’s Pro Skater 1–4

<a href="https://thegamingemporium.com/Images/Games/tony-hawks-pro-skater-recompilation-2.webp"><img src="https://thegamingemporium.com/Images/Games/tony-hawks-pro-skater-recompilation-2.webp" alt="Tony Hawk’s Pro Skater 1–4 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The first four Tony Hawk's Pro Skater games appeared from 1999 to 2002 across several platforms. This is a clearly marked series grouping for a project covering multiple releases.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **LANCommander/TonyWasAProSkater** | [TonyWasAProSkater](https://github.com/LANCommander/TonyWasAProSkater) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A reconstruction of the first Tony Hawk’s Pro Skater game; the title refers to the first game in the series. |

---

### 🏁 WWE SmackDown vs. Raw 2011

<a href="https://thegamingemporium.com/Images/Games/wwe-smackdown-vs.-raw-2011-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/wwe-smackdown-vs.-raw-2011-recompilation.webp" alt="WWE SmackDown vs. Raw 2011 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 2010 wrestling game was released across several consoles with a large WWE roster. The linked project targets a particular game edition.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **shaneomac1337/SVR2011-Recomp** | [GitHub](https://github.com/shaneomac1337/SVR2011-Recomp) · [Releases](https://github.com/shaneomac1337/SVR2011-Recomp/releases) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A ReXGlue-based Windows recompilation of the Xbox 360 game. The author reports playable exhibition matches, while some other modes remain untested or may crash; a user-owned disc image is required. |
| **KaikoClanworth1/wwe-svr2011-pc** | [GitHub](https://github.com/KaikoClanworth1/wwe-svr2011-pc) · [Project guide](https://kaikoclanworth1.github.io/wwe-svr2011-pc/) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A separate native PC port using ReXGlue, with its own launcher and broader customization features. Its README describes high-resolution and ultrawide output, custom entrance media, and mod tools. |

---

### 🏁 The Simpsons Wrestling

<a href="https://thegamingemporium.com/Images/Games/the-simpsons-wrestling-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/the-simpsons-wrestling-recompilation.webp" alt="The Simpsons Wrestling game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

This 2001 PlayStation fighting game pits Simpsons characters against one another. It is a different game from The Simpsons Game (2007) listed earlier.

<sub>📸 [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **TekRantGaming/simpsons-wrestling-recompiled** | [simpsons-wrestling-recompiled](https://github.com/TekRantGaming/simpsons-wrestling-recompiled) · [X post screenshot](https://x.com/mdaman010/status/2109111127238230239?s=46) | A recompilation project for The Simpsons Wrestling. |

---

### 🚘 Driver: You Are the Wheelman

<a href="https://thegamingemporium.com/Images/Games/driver-recompilation.webp"><img src="https://thegamingemporium.com/Images/Games/driver-recompilation.webp" alt="Driver: You Are the Wheelman game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1999 driving game casts the player as an undercover getaway driver. Its project targets the first Driver game rather than its sequel.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **alexbeavs-ps1-ports/driver-recomp** | [driver-recomp](https://github.com/alexbeavs-ps1-ports/driver-recomp) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A recompilation project for the first Driver game. |

---

### 🚘 Driver 2

<a href="https://thegamingemporium.com/Images/Games/redriver2-driver-2-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/redriver2-driver-2-pc-port.webp" alt="Driver 2 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 2000 sequel expands Driver with on-foot movement between cars. Its code effort is tracked separately from the first game.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenDriver2/REDRIVER2** | [OpenDriver2/REDRIVER2](https://github.com/OpenDriver2/REDRIVER2) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A reverse-engineered PC port and engine project for Driver 2. |

---

### 🏁 Ski or Die: Snowball War

<a href="https://raw.githubusercontent.com/tuunanet/rea-ski-or-die-reconstruction/main/docs/snowball-war.gif"><img src="https://raw.githubusercontent.com/tuunanet/rea-ski-or-die-reconstruction/main/docs/snowball-war.gif" alt="Ski or Die: Snowball War game image" width="400"></a><br><sub>[Gameplay GIF](https://github.com/tuunanet/rea-ski-or-die-reconstruction)</sub>

Snowball War, also called “Snowball Blast” by the project, is one event in Electronic Arts' 1990 DOS winter sports game Ski or Die. The listed reconstruction covers that event, not a separate commercial game. [Project scope](https://github.com/tuunanet/rea-ski-or-die-reconstruction)

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **tuunanet/rea-ski-or-die-reconstruction** | [tuunanet/rea-ski-or-die-reconstruction](https://github.com/tuunanet/rea-ski-or-die-reconstruction) | A REA-assisted reconstruction of the Snowball War mode. It does not reconstruct the whole Ski or Die game. |

---

<a id="strategy--simulation"></a>
## 🏗️ Strategy & simulation

Simulation, management, and tactical or real-time strategy.

### 🏡 Animal Crossing

<a href="https://thegamingemporium.com/Images/Games/animal-crossing-pc-port.webp"><img src="https://thegamingemporium.com/Images/Games/animal-crossing-pc-port.webp" alt="Animal Crossing game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The series began on Nintendo 64 in Japan in 2001 and soon gained a GameCube edition. The listed projects here concern the GameCube game and its decompilation lineage.

<sub>📸 [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png)</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **ACreTeam/forest** | [ACreTeam/forest](https://github.com/ACreTeam/forest) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A source reconstruction of the GameCube-era Animal Crossing game. |
| **flyngmt/ACGC-PC-Port** | [ACGC-PC-Port](https://github.com/flyngmt/ACGC-PC-Port) · [collection screenshot](https://i.4cdn.org/vr/1791496164085175.png) | A separate PC port project for GameCube Animal Crossing. |
| **ACreTeam/ac-decomp** | [ACreTeam/ac-decomp](https://github.com/ACreTeam/ac-decomp) | A GameCube source reconstruction, separate from the existing port and engine projects. |

---

### 🏡 Animal Crossing: Wild World

<a href="https://en.wikipedia.org/wiki/File:Animal_Crossing_Wild_World_Gameplay.png"><img src="https://upload.wikimedia.org/wikipedia/en/3/36/Animal_Crossing_Wild_World_Gameplay.png" alt="Animal Crossing: Wild World game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Animal_Crossing_Wild_World_Gameplay.png)</sub>

Nintendo's 2005 DS installment brings the village life simulation to handheld play. Its matching source project targets a specific Nintendo DS build.

<sub>Original platform: Nintendo DS.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **banatic/acww-decomp** | [banatic/acww-decomp](https://github.com/banatic/acww-decomp) | A matching decompilation of the Korean Nintendo DS release. This is distinct from Animal Crossing for GameCube. |

---

### 🏠 The Sims Bustin' Out

<a href="https://www.walmart.com/ip/The-Sims-Bustin-Out-GBA-Electronic-Arts-Game-Boy-Advance-PC-Physical/2452766"><img src="https://i5.walmartimages.com/seo/The-Sims-Bustin-Out-GBA-Electronic-Arts-Game-Boy-Advance-PC-Physical_29295d15-67b8-47fd-875b-2902da9ac73c.d0ca84f50ec577226e0eac2090e03e13.jpeg" alt="The Sims Bustin&#x27; Out game image" width="400"></a><br><sub>[Original GBA cover](https://www.walmart.com/ip/The-Sims-Bustin-Out-GBA-Electronic-Arts-Game-Boy-Advance-PC-Physical/2452766)</sub>

The Game Boy Advance version of this early-2000s Sims spin-off has its own handheld adventure structure. The listed reconstruction targets that GBA game, not the console versions.

<sub>Original platform: Game Boy Advance.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **DaBrown95/tsbodp** | [DaBrown95/tsbodp](https://github.com/DaBrown95/tsbodp) | A matching decompilation project for the Game Boy Advance edition, not the console edition. |

---

### 🏗️ Command & Conquer / Dune 2000 / OpenRA

<a href="https://thegamingemporium.com/Images/Games/openra-command-conquer-red-alert-+-tiberian-dawn-+-dune-2000.webp"><img src="https://thegamingemporium.com/Images/Games/openra-command-conquer-red-alert-+-tiberian-dawn-+-dune-2000.webp" alt="Command & Conquer / Dune 2000 / OpenRA game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Command & Conquer and Dune 2000 are distinct real-time strategy games from the 1990s. OpenRA is a shared modern engine project for these classics; this heading is a multi-game grouping.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenRA/OpenRA** | [OpenRA/OpenRA](https://github.com/OpenRA/OpenRA) | An open-source real-time strategy engine for classic Command & Conquer games and Dune 2000. It is an engine reimplementation. |

---

### 🏗️ RollerCoaster Tycoon 2 / OpenRCT2

<a href="https://thegamingemporium.com/Images/Games/openrct2-rollercoaster-tycoon-2-for-android.webp"><img src="https://thegamingemporium.com/Images/Games/openrct2-rollercoaster-tycoon-2-for-android.webp" alt="RollerCoaster Tycoon 2 / OpenRCT2 game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 2002 Windows management game asks players to build and run theme parks. OpenRCT2 is a modern open-source implementation and extension of that game.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenRCT2/OpenRCT2** | [OpenRCT2/OpenRCT2](https://github.com/OpenRCT2/OpenRCT2) | An open-source reimplementation and extension of the RollerCoaster Tycoon 2 engine. |

---

### 🏗️ X-COM: UFO Defense / OpenXcom

<a href="https://thegamingemporium.com/Images/Games/openxcom.webp"><img src="https://thegamingemporium.com/Images/Games/openxcom.webp" alt="X-COM: UFO Defense / OpenXcom game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

The 1994 strategy game combines tactical combat with global research and defense. OpenXcom is a modern engine reimplementation for the original game's data.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **OpenXcom/OpenXcom** | [OpenXcom/OpenXcom](https://github.com/OpenXcom/OpenXcom) | A modern open-source engine implementation for X-COM: UFO Defense and related original data. |

---

### 🏗️ Theme Hospital / CorsixTH

<a href="https://thegamingemporium.com/Images/Games/corsixth-theme-hospital-port.webp"><img src="https://thegamingemporium.com/Images/Games/corsixth-theme-hospital-port.webp" alt="Theme Hospital / CorsixTH game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Bullfrog's 1997 hospital management game mixes economic simulation with absurd illnesses. CorsixTH recreates the runtime for original game assets.

<sub>◈ Engine reimplementation or compatibility work.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **CorsixTH/CorsixTH** | [CorsixTH/CorsixTH](https://github.com/CorsixTH/CorsixTH) | An open-source Theme Hospital engine reimplementation. |

---

<a id="arcade--casual"></a>
## 🕹️ Arcade & casual

Arcade games, browser runners, bullet-hell shooters, and small reverse-engineering cases.

### 🎲 Mario Party 4

<a href="https://en.wikipedia.org/wiki/File:Mario_Party_4_gameplay.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/2/22/Mario_Party_4_gameplay.jpg" alt="Mario Party 4 game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Mario_Party_4_gameplay.jpg)</sub>

The 2002 GameCube party game is built around board games and short competitive minigames. The listed project reconstructs its original console code.

<sub>Original platform: GameCube.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **mariopartyrd/marioparty4** | [mariopartyrd/marioparty4](https://github.com/mariopartyrd/marioparty4) | A work-in-progress GameCube decompilation; the repository reports matching progress. |

---

### ⚡ Pokémon Snap

<a href="https://github.com/JackandBeans/Snap64Recomp"><img src="https://repository-images.githubusercontent.com/1358365242/a4da5a86-5661-4c4a-aa58-bab0a60b78cb" alt="Pokémon Snap game image" width="400"></a><br><sub>[Project social preview](https://github.com/JackandBeans/Snap64Recomp)</sub>

This 1999 Nintendo 64 game asks players to photograph Pokémon from a moving vehicle. The listed project statically recompiles the original game.

<sub>Original platform: Nintendo 64.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **JackandBeans/Snap64Recomp** | [JackandBeans/Snap64Recomp](https://github.com/JackandBeans/Snap64Recomp) | A static recompilation of the Nintendo 64 photography game. |

---

### 🕹️ Chrome Dinosaur Runner

<a href="https://raw.githubusercontent.com/zhxunzh84/rea-dino-reverse-engineering/main/screenshots/dino-game.png"><img src="https://raw.githubusercontent.com/zhxunzh84/rea-dino-reverse-engineering/main/screenshots/dino-game.png" alt="Chrome Dinosaur Runner game image" width="400"></a><br><sub>[Project screenshot](https://github.com/zhxunzh84/rea-dino-reverse-engineering)</sub>

The browser's offline dinosaur runner is a compact endless-jump game rather than a packaged console release. The linked REA-assisted case infers some rules and demonstrates them independently.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **zhxunzh84/rea-dino-reverse-engineering** | [zhxunzh84/rea-dino-reverse-engineering](https://github.com/zhxunzh84/rea-dino-reverse-engineering) | A REA-assisted study of Chrome Dinosaur Runner rules with an independent demonstration. |

---

### 🕹️ 3D Pinball for Windows: Space Cadet

<a href="https://thegamingemporium.com/Images/Games/spacecadetpinball.webp"><img src="https://thegamingemporium.com/Images/Games/spacecadetpinball.webp" alt="3D Pinball for Windows: Space Cadet game image" width="400"></a><br><sub>[Image source](https://thegamingemporium.com/all/)</sub>

Space Cadet became familiar through Microsoft Windows' bundled 3D Pinball. The listed project is a modern source port or reconstruction, separate from the original Windows distribution.

| Project | Resources | What makes it different |
|:--|:--|:--|
| **k4zmu2a/SpaceCadetPinball** | [k4zmu2a/SpaceCadetPinball](https://github.com/k4zmu2a/SpaceCadetPinball) | A source port or reconstruction of the Windows Space Cadet pinball game. |

---

### 🌙 Touhou 6: Embodiment of Scarlet Devil

<a href="https://en.wikipedia.org/wiki/File:Th06cover.jpg"><img src="https://upload.wikimedia.org/wikipedia/en/8/8b/Th06cover.jpg" alt="Touhou 6: Embodiment of Scarlet Devil game image" width="400"></a><br><sub>[Original game image](https://en.wikipedia.org/wiki/File:Th06cover.jpg)</sub>

Released for Windows in 2002, Touhou 6 established the series' modern Windows-era bullet-hell style. The listed source project focuses on the original game.

<sub>Original platform: Windows.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **GensokyoClub/th06** | [GensokyoClub/th06](https://github.com/GensokyoClub/th06) | A source decompilation project for Touhou 6. |

---

<a id="touhou-8-imperishable-night"></a>
### 🌙 Touhou 8: Imperishable Night

<a href="https://raw.githubusercontent.com/N0zoM1z0/th08/master/resources/title-screen.png"><img src="https://raw.githubusercontent.com/N0zoM1z0/th08/master/resources/title-screen.png" alt="Touhou 8: Imperishable Night game image" width="400"></a><br><sub>[Title screen](https://github.com/N0zoM1z0/th08)</sub>

This 2004 Windows bullet-hell game uses paired characters and a night-themed story. A REA-assisted reconstruction and a separate browser build of that work appear below.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **N0zoM1z0/th08** | [N0zoM1z0/th08](https://github.com/N0zoM1z0/th08) | A REA-assisted reconstruction of Touhou 8 with a playable Linux and web result described by the project. |
| **N0zoM1z0/th08-web** | [N0zoM1z0/th08-web](https://github.com/N0zoM1z0/th08-web) · [Play in browser](https://th08-web.pages.dev/) · [original reconstruction](https://github.com/N0zoM1z0/th08) | A source-built WebAssembly browser port of the existing TH08 reconstruction; users supply their own game data. |

---

### 🌙 Touhou 9.5: Shoot the Bullet

<a href="https://raw.githubusercontent.com/N0zoM1z0/th095/main/resources/title-screen.jpg"><img src="https://raw.githubusercontent.com/N0zoM1z0/th095/main/resources/title-screen.jpg" alt="Touhou 9.5: Shoot the Bullet game image" width="400"></a><br><sub>[Title screen](https://github.com/N0zoM1z0/th095)</sub>

This 2005 Windows Touhou spin-off centers on photographing bullet patterns rather than ordinary stage clearing. The listed REA-associated reconstruction covers this specific game.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **N0zoM1z0/th095** | [N0zoM1z0/th095](https://github.com/N0zoM1z0/th095) | A REA-assisted reconstruction project for Touhou 9.5, with a Windows i386 build described by the project. |

---

### 🌙 Touhou 4: Lotus Land Story

<a href="https://raw.githubusercontent.com/N0zoM1z0/th04/main/resources/title-screen.png"><img src="https://raw.githubusercontent.com/N0zoM1z0/th04/main/resources/title-screen.png" alt="Touhou 4: Lotus Land Story game image" width="400"></a><br><sub>[Title screen](https://github.com/N0zoM1z0/th04)</sub>

Touhou 4 is a 1998 PC-98 bullet-hell game from the series' early era. Its reconstruction targets that older computer platform rather than the later Windows titles.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **N0zoM1z0/th04** | [N0zoM1z0/th04](https://github.com/N0zoM1z0/th04) | A REA-assisted reconstruction of the PC-98 era Touhou 4 game. |

---

### 🕹️ DX-Ball

<a href="https://raw.githubusercontent.com/N0zoM1z0/dx-ball/main/resources/dxball-title.png"><img src="https://raw.githubusercontent.com/N0zoM1z0/dx-ball/main/resources/dxball-title.png" alt="DX-Ball game image" width="400"></a><br><sub>[Title screen](https://github.com/N0zoM1z0/dx-ball)</sub>

The mid-1990s Windows brick-breaker DX-Ball adapts an arcade-style bat-and-ball formula. The linked REA-assisted reconstruction remains in progress.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **N0zoM1z0/dx-ball** | [N0zoM1z0/dx-ball](https://github.com/N0zoM1z0/dx-ball) | An in-progress REA-assisted reverse-engineering reconstruction of DX-Ball. |

---

### 🕹️ Larax & Zaco

<a href="https://www.old-games.ru/games/pc/larax_and_zaco/screenshots/11646_6179b40c56b44.png"><img src="https://www.old-games.ru/games/pc/larax_and_zaco/screenshots/11646_6179b40c56b44.png" alt="Larax & Zaco game image" width="400"></a><br><sub>[Original game image](https://www.old-games.ru/game/screenshots/11646.html)</sub>

This DOS-era game is represented by a project recovering selected game routines.

<sub>🔬 REA-assisted case; the notes below describe its actual scope.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Hubert-Rybak/lezac-decompilation** | [Hubert-Rybak/lezac-decompilation](https://github.com/Hubert-Rybak/lezac-decompilation) | A partial decompilation of Larax & Zaco routines, not a complete playable game. |

---

<a id="playable-showcases"></a>
## 🎪 Playable showcases

Creator-shared browser games and demos with direct play links.

### 🎪 The Little Prince: Among the Stars

<a href="https://littleprince.dev/keyart.031aa305131370a0e08c9cb92d1b1aaa.jpg"><img src="https://littleprince.dev/keyart.031aa305131370a0e08c9cb92d1b1aaa.jpg" alt="The Little Prince: Among the Stars site key art" width="400"></a><br><sub>[Game-site key art](https://littleprince.dev/)</sub>

A browser experience inspired by The Little Prince, shared by its creator as a playable demo.

<sub>▶ Playable browser showcase.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **The Little Prince browser experience** | [Play](https://littleprince.dev/) · [0xMovez post](https://x.com/0xMovez/status/2110046218034229730) · [creator launch post](https://x.com/Saccc_c/status/2109962425512734739) | A 3D browser experience inspired by *The Little Prince*, with a playable site and creator launch post. |

---

### 🎪 Roadster City

<a href="https://github.com/0xCodez/roadster-city/blob/main/assets/og.jpg"><img src="https://raw.githubusercontent.com/0xCodez/roadster-city/main/assets/og.jpg" alt="Roadster City project preview with a jumping car" width="400"></a><br><sub>[Project preview](https://github.com/0xCodez/roadster-city/blob/main/assets/og.jpg)</sub>

Roadster City is an original browser driving and stunt game shared through an X post, with public code and a playable demo.

<sub>▶ Playable browser showcase.</sub>

| Project | Resources | What makes it different |
|:--|:--|:--|
| **Roadster City browser game** | [Play](https://roadster-city.vercel.app/) · [public code](https://github.com/0xCodez/roadster-city) · [0xMovez post](https://x.com/0xMovez/status/2111113272535781854) · [repository configuration connecting the demo and X handle](https://github.com/0xCodez/roadster-city/blob/main/src/config.js) | An original browser driving and stunt game with GTA-style inspiration, public code, and a playable demo. |

---

<a id="contributing"></a>
## 🤝 Contributing

Have a project, demo, correction, or better image to share? See [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and submission guide.
