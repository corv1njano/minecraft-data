# Additional Notes
This file contains supplemental information that is not included in the main data files. It serves as documentation for removed, unobtainable, or special entries that are relevant for historical or technical context.

These entries are **not part of the official dataset** because they are:
- no longer obtainable in the game
- inaccessible via commands or NBT editing
- experimental or unreleased (e.g. snapshots, April Fools content)

This document is meant for reference only and does not reflect the current state of Minecraft gameplay or data.

## Unobtainable Items
Some items, such as `minecraft:fire`, can no longer be obtained via **/give** and are also inaccessible through NBT editing. However, `minecraft:fire` is still available as a block using **/setblock**.

Full list of all lost/removed items :

> **Note**: This list is currently in development and not updated frequently.

| Item | Name | Reason |
|------|------|--------|
| minecraft:fire | Fire | No longer available as an item since version x.x.x. |

## Special Entities
`minecraft:fishing_bobber` and `minecraft:player` can be targeted using the entity type selector argument **@e[type=...]**, but they cannot be summoned via **/summon**, nor are they stored as standalone entities in NBT data.
