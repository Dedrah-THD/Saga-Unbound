# Dedicated Server Notes

Saga Unbound is designed to work on persistent dedicated servers as well as solo games.

- Use the same Saga Unbound release/configuration on the server and clients where required by the underlying mods.
- Keep regular world backups, especially before Valheim updates, modpack updates, or world-generation maintenance.
- Crossplay/PlayFab behavior can affect heavily modded connection/config-sync timing; validate changes in your own hosting environment.
- Administrative tools such as **Upgrade World** and **Server Devcommands** are intentionally not mandatory public dependencies. Install them separately only if the server administrator needs them and understands their use.
- **LoadTimeProfiler** is diagnostic tooling and is not part of the public gameplay dependency set.
- Do not reset or regenerate explored zones merely to make an existing world mathematically identical to a fresh world. Back up first and use world-upgrade tools surgically if needed.

Saga Unbound's public configuration intentionally favors outward exploration: settlement automation is convenient, while mines, dungeons and locations regenerate more slowly.
