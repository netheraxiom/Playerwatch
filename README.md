# PlayerWatch — Minecraft Java 1.21.11 (Fabric)

Starter project for an in-game real-world smartwatch clock.

## Included in this starter
- Fabric mod metadata for Minecraft 1.21.11
- Java 21 / Fabric Loom project
- `playerwatch:smartwatch` item registered in the Tools & Utilities tab
- Client HUD clock showing India Standard Time (Asia/Kolkata)
- Starter item model JSON

## Important scope note
This is **Phase 1**, not the finished 3D wrist-watch mod. The clock HUD and item registration are the starter foundation. A small placeholder icon is included for the item. The custom 3D watch attached to the player's wrist, brand-specific watch faces, glow animation, and selection screen still need their renderer/assets and in-game testing. This project does not claim those features are already implemented.

## Build
Requires JDK 21 and Gradle:
```bash
gradle build
```
The built mod jar will be in `build/libs/`.

## Test in Minecraft
1. Install Fabric Loader for Minecraft 1.21.11.
2. Install Fabric API matching Minecraft 1.21.11.
3. Copy the built `playerwatch-0.1.0.jar` into the `.minecraft/mods` folder.
4. Launch the Fabric profile.
5. The clock appears at the top-left. The item is in Tools & Utilities.

You can also test the item command:
```mcfunction
/give @s playerwatch:smartwatch
```

## Android-only workflow
An Android phone cannot run the normal desktop Minecraft Java modding client locally. Use GitHub in your mobile browser to upload this project and let GitHub Actions build it in the cloud. To test the mod in-game, you will still need a Java Edition environment that supports Fabric.

## Branding
The names Apple Watch and Samsung Galaxy Watch are used only as design references. This starter contains no official logos or copied proprietary watch artwork.
