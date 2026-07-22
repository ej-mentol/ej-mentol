> ⚠️ **Important Note & Disclaimer**
> - **AI Assistance:** The projects listed below were developed with the assistance of various AI agents. As a result, they may contain unexpected bugs, unhandled edge cases, or incomplete features.
> - **Platform:** All C++/C# projects are targeted and compiled specifically for **Windows**. They have **never** been tested on Linux environments.
> - **Development Status:** Version numbers are just numbers — all projects are continuously work-in-progress to some extent. Project READMEs within individual repositories may contain typical AI-generated claims about "completeness" or "stability".

---

## 🛠️ Repositories Overview

### MetaHookSV
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **[ChatForwarder](https://github.com/ej-mentol/Chat-Forwarder)** | Forwards engine and game chat messages to/from a UDP port. | - |
| **[RadialMenu](https://github.com/ej-mentol/RadialMenu)** | Customizable JSON-driven radial menu powered by ImGui. | Built on top of `IMGUIExtension`. |
| **[IMGUIExtension](https://github.com/ej-mentol/IMGUIExtension)** | Integrates Dear ImGui into the Half-Life (SC) VGUI2 interface. | Core framework for ImGui-based MetaHookSV plugins. |
| **[MyResourceReplacer](https://github.com/ej-mentol/MyResourceReplacer)** | Per-server resource replacement extension. | ⚠️ **WIP / Broken:** Currently does not function as intended. |
| **[VeloHUD](https://github.com/ej-mentol/VeloHUD)** | Lightweight HUD element displaying player velocity. | - |
| **[uwFPS](https://github.com/ej-mentol/uwFPS)** | Dynamically modifies FPS limits when submerged in water. | The FPS toggle relies on `WaterLevel`. However, changing maps, switching to OBSERVER mode, or server-side plugins can cause `WaterLevel` checks to misbehave, unintendedly shifting the FPS. |

### HammerTime
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **[Brush-Builder](https://github.com/ej-mentol/Brush-Builder)** | Set of tools designed to connect and bridge 2 brushes together. | - |
| **[Face-Tool](https://github.com/ej-mentol/Face-Tool)** | Tools for aligning and orienting brush faces relative to one another. | - |

### NodeJS
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **[GSRP](https://github.com/ej-mentol/GSRP)** | Parses console output from `status` command into an interactive player table with tags, badges, and colors. | Requires a Steam Web API Key to operate. |
| **[SCPM](https://github.com/ej-mentol/SCPM)** | Sven Co-op AngelScript plugin manager for `default_plugins.txt`. | - |

### Metamod
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **[SemiclipML](https://github.com/ej-mentol/SemiclipML)** | Metamod server-side plugin for player semiclip functionality. | - |

### Misc
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **[TDR2000-Pack-Extractor](https://github.com/ej-mentol/Random-Scripts/tree/main/TDR2000%20PAK%20Extractor)** | Scripts for extracting files from Carmageddon TDR 2000 game archives. | Current scripts do not account for the recursive Trie index in `.DIR` or the XOR-encrypted 8-byte `zIG`/`RAW` headers inside `.PAK`. Archive parsing and extraction logic require updating |
| **[TDR2000-Track2OBJ](https://github.com/ej-mentol/Random-Scripts/tree/main/TDR2000%20Track2OBJ)** | Converts TDR 2000 track files into a single OBJ model for use in 3D editors like Blender. | - |
| **[Unepic-Tools](https://github.com/ej-mentol/Random-Scripts/tree/main/Unepic)** | Sprite viewer and built-in editor map unlocker (toggles the multiplayer map availability bit) | - |
| **[H3MLibCS](https://github.com/ej-mentol/H3MLibCS)** | Early-stage .NET library for converting *Heroes of Might and Magic III* map files into ML-ready formats. | ⚠️ **Incomplete:** Lacks map object type IDs and data mappings. |


### **Forks:**

All repositories are open for forking and further modification. If you use or develop the code further, please maintain a link back to the original repository
