> ⚠️ **Important Note & Disclaimer**
> - **AI Assistance:** The projects listed below were developed with the assistance of various AI agents. As a result, they may contain unexpected bugs, unhandled edge cases, or incomplete features.
> - **Platform:** All C++/C# projects are targeted and compiled specifically for **Windows**. They have **never** been tested on Linux environments.
> - **Development Status:** Version numbers are just numbers — all projects are continuously work-in-progress to some extent. Project READMEs within individual repositories may contain typical AI-generated claims about "completeness" or "stability". **Please treat these claims with caution** — most projects are in experimental development and are not production-ready.

---

## 🛠️ Repositories Overview

### MetaHookSV
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **ChatForwarder** | Forwards engine and game chat messages to/from a UDP port. | - |
| **RadialMenu** | Customizable JSON-driven radial menu powered by ImGui. | Built on top of `IMGUIExtension`. |
| **IMGUIExtension** | Integrates Dear ImGui into the Half-Life (SC) VGUI2 interface. | Core framework for ImGui-based MetaHookSV plugins. |
| **MyResourceReplacer** | Per-server resource replacement extension. | ⚠️ **WIP / Broken:** Currently does not function as intended. |
| **VeloHUD** | Lightweight HUD element displaying player velocity. | - |
| **uwFPS** | Dynamically modifies FPS limits when submerged in water. | The FPS toggle relies on `WaterLevel`. However, changing maps, switching to OBSERVER mode, or server-side plugins can cause `WaterLevel` checks to misbehave, unintendedly shifting the FPS. |

### HammerTime
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **Brush-Builder** | Set of tools designed to connect and bridge 2 brushes together. | - |
| **Face-Tool** | Tools for aligning and orienting brush faces relative to one another. | - |

### NodeJS
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **GSRP** | Parses console output from `status` command into an interactive player table with tags, badges, and colors. | Requires a Steam Web API Key to operate. |
| **SCPM** | Sven Co-op AngelScript plugin manager for `default_plugins.txt`. | - |

### Metamod
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **SemiclipML** | Metamod server-side plugin for player semiclip functionality. | - |

### Misc
| Repository | Description | Status & Notes |
| :--- | :--- | :--- |
| **TDR2000-Pack-Extractor** | Scripts for extracting files from Carmageddon TDR 2000 game archives. | Current scripts do not account for the recursive Trie index in `.DIR` or the XOR-encrypted 8-byte `zIG`/`RAW` headers inside `.PAK`. Archive parsing and extraction logic require updating |
| **TDR2000-Track2OBJ** | Converts TDR 2000 track files into a single OBJ model for use in 3D editors like Blender. | - |
| **Unepic-Tools** | Sprite viewer and built-in editor map unlocker (toggles the multiplayer map availability bit) | - |
| **H3MLibCS** | Early-stage .NET library for converting *Heroes of Might and Magic III* map files into ML-ready formats. | ⚠️ **Incomplete:** Lacks map object type IDs and data mappings. |


### **Forks:**

All repositories are open for forking and further modification. If you use or develop the code further, please maintain a link back to the original repository
