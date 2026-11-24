# Unreal Essential Suite

> Modular, production-ready C++ & Blueprint plugins for Unreal Engine 5. Engineered for multiplayer replication, data-driven architecture, and rapid game development.

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](LICENSE)
[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.3%20--%205.5%20|%205.8%2B-black.svg?logo=unrealengine)](https://www.unrealengine.com)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen.svg)]()

---

## Suite Repositories

Each module is independently maintained, versioned, and packaged with pre-compiled Win64 binaries and full source code.

| Plugin | Category | Target UE | Architecture | Repository |
| :--- | :--- | :---: | :---: | :--- |
| **Plugin-CharacterLocomotionSystem** | Locomotion & Parkour | 5.3 – 5.5 | Replicated C++ / CMC | [1SHAMAY1/Plugin-CharacterLocomotionSystem](https://github.com/1SHAMAY1/Plugin-CharacterLocomotionSystem) |
| **Plugin-EnhancedCameraSystem** | Dynamic Camera Stack | 5.3 | Data-Driven Modifier Stack | [1SHAMAY1/Plugin-EnhancedCameraSystem](https://github.com/1SHAMAY1/Plugin-EnhancedCameraSystem) |
| **Plugin-GameplayQuestFramework** | Quest State Machine | 5.8+ | Zero-Tick GameplayTags | [1SHAMAY1/Plugin-GameplayQuestFramework](https://github.com/1SHAMAY1/Plugin-GameplayQuestFramework) |
| **Plugin-GameplayInteractionFramework** | Contextual Interactions | 5.8+ | Authoritative RepNotify | [1SHAMAY1/Plugin-GameplayInteractionFramework](https://github.com/1SHAMAY1/Plugin-GameplayInteractionFramework) |
| **Plugin-GameplayInventoryFramework** | Replicated Inventory | 5.8+ | FFastArray / MassEntity | [1SHAMAY1/Plugin-GameplayInventoryFramework](https://github.com/1SHAMAY1/Plugin-GameplayInventoryFramework) |
| **Plugin-CommonFrontendUI** | CommonUI Menus & Navigation | 5.8+ | CommonUI / EnhancedInput | [1SHAMAY1/Plugin-CommonFrontendUI](https://github.com/1SHAMAY1/Plugin-CommonFrontendUI) |
| **Plugin-ValidateAllAssets** | Asset Quality & Linting | 5.3 – 5.5 | Editor Utility / Linter | [1SHAMAY1/Plugin-ValidateAllAssets](https://github.com/1SHAMAY1/Plugin-ValidateAllAssets) |

---

## Quick Installation

### For UE 5.8+ Modules (Root Plugins)
Clone directly into your project's `Plugins/` folder:
```bash
cd YourProject/Plugins
git clone https://github.com/1SHAMAY1/<Plugin-Name>.git
```

### For UE 5.3 – 5.5 Modules (Version-Foldered Plugins)
Clone the repository, then copy the matching engine version directory (`5.3/`, `5.4/`, or `5.5/`) into your project's `Plugins/` folder:
```bash
git clone https://github.com/1SHAMAY1/<Plugin-Name>.git
# Copy the version-specific inner folder to your project's Plugins/ directory:
cp -r <Plugin-Name>/<Version>/<PluginFolder> YourProject/Plugins/
```

Pre-compiled Win64 binaries (`.dll` and `.modules`) are included in each repository so Blueprint developers can launch immediately without building C++.

## Live Showcase

Explore interactive demonstrations and documentation on the [Unreal Essential Suite Web Portal](https://1shamay1.github.io/Unreal-Essential-Suite/).

## License

Distributed under the [MIT License](LICENSE). Free for commercial and personal Unreal Engine projects.
