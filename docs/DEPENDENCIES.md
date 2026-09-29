# Tested Dependency Profile — Saga Unbound 1.0.0

This is the dependency profile used to build/test the 1.0 release. Manifest dependency versions are minimum versions under the package-manager format; this table records the versions actually tested.

## Hexium

| Package | Tested version |
|---|---:|
| `Azumatt-AzuAutoStore` | 3.1.6 |
| `Azumatt-AzuCraftyBoxes` | 1.8.26 |
| `Azumatt-AzuExtendedPlayerInventory` | 2.6.1 |
| `Azumatt-Build_Camera_Custom_Hammers_Edition` | 1.3.3 |
| `Azumatt-PetPantry` | 1.0.7 |
| `Azumatt-Recycle_N_Reclaim` | 1.4.5 |
| `blacks7ar-CookingAdditions` | 1.3.3 |
| `Marlthon-OdinShip` | 0.8.5 |
| `Marlthon-TheFisher` | 0.3.9 |
| `Smoothbrain-Backpacks` | 1.3.10 |
| `Smoothbrain-CreatureLevelAndLootControl` | 5.0.5 |

## Thunderstore

| Package | Tested version |
|---|---:|
| `Advize-PlantEasily` | 2.2.2 |
| `Advize-PlantEverything` | 1.21.3 |
| `Azumatt-Unshamed` | 1.0.5 |
| `blacks7ar-BetterStations` | 1.0.9 |
| `blacks7ar-FineWoodPieces` | 1.6.7 |
| `blacks7ar-Herbalist` | 1.5.0 |
| `blacks7ar-MagicRevamp` | 1.5.1 |
| `blacks7ar-OreMines` | 1.2.1 |
| `blacks7ar-TorchesAreFires` | 1.1.0 |
| `cjayride-InstantMonsterLootDrop` | 0.8.2 |
| `Digitalroot-Max_Dungeon_Rooms` | 2.0.40 |
| `Digitalroot-Triple_Bronze_JVL` | 1.1.54 |
| `KlownKiller-EpicLootContainerBridge` | 1.0.0 |
| `MaxFoxGaming-Better_Beehives` | 1.3.0 |
| `ModdedWolf-BowTrajectory` | 1.1.1 |
| `Qmds-FishTrap` | 1.1.4 |
| `Radamanto-Hunters_Instinct` | 1.0.1 |
| `Radamanto-Vikings_Archer` | 1.2.5 |
| `Radamanto-Vikings_Summoner` | 1.5.2 |
| `Radamanto-Vikings_Warrior` | 1.0.8 |
| `RandyKnapp-AdvancedPortals` | 1.2.0 |
| `RandyKnapp-EpicLoot` | 0.14.13 |
| `shudnal-ConditionalConfigSync` | 1.0.9 |
| `shudnal-Seasons` | 1.10.2 |
| `southsil-SouthsilArmor` | 3.1.9 |
| `Therzie-Monstrum` | 1.6.0 |
| `Therzie-Warfare` | 1.9.4 |
| `Therzie-Wizardry` | 1.2.2 |
| `ValheimModding-Jotunn` | 2.30.2 |
| `ValheimModding-JsonDotNET` | 13.0.4 |
| `ValheimModding-YamlDotNet` | 16.3.1 |
| `VentureValheim-Venture_Location_Reset` | 1.1.1 |
| `warpalicious-More_World_Locations_AIO` | 5.1.5 |

## Intentionally not mandatory public dependencies

- `JereKuusela-Server_devcommands` — server administration/tooling.
- `JereKuusela-Upgrade_World` — optional world-maintenance tool.
- LoadTimeProfiler — diagnostic tooling; not present in the public dependency manifest.
- BepInEx is handled by the modding platform/manager rather than treated as Saga Unbound gameplay content.
